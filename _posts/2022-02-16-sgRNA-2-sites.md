---
layout: post
title: Picking sgRNA Site, and Designing sgRNA Primers and Cas9 Digest Primers
---

## Picking 2 DiNV Regions for CRISPR Sites, Picking 2 sgRNAs From Each

Want to pick two regions of the DiNV genome to try for using CRISPR. And from each region, pick two sgRNAs that have good qualities. Potential sgRNAs from all regions were explored in [this notebook post](https://github.com/meschedl/Unckless-Lab-Notebook-Maggie/blob/master/_posts/2022-02-07-Recheck-DiNV-CRISPR-sgRNAs.md). Regions are named by their approximate location in the genome.

### sgRNA Choice

**"77kb Region"**
- ~76,800kb-78,400kb
- Intergenic region: 1,727bp
- No repeats within region
- GC% in intergenic region: 26%
- Flanking genes:
  - gp053 189bp
  - gp054 237bp
  - gp094-like 330bp

![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/77kb-region.png)

sgRNA 86  
- Basepairs with PAM: ACACAAGTGTTGTTATACGA**TGG**
- No off-target sites in DiNV or BACs (in CDS)
- No worrisome off-target hits in the _D. virilis_ genome, at most a 14bp match (compared to a 20bp long guide sequence), this is with all possible PAM sites
- Activity score: 0.713
- Reverse direction

sgRNA 92  
- Basepairs with PAM: AAAAAATGCACTAAAACACA**GGG**
- No off-target sites in DiNV or BACs (in CDS)
- No worrisome off-target hits in the _D. virilis_ genome, at most a 17/18bp match (compared to a 20bp long guide sequence), this is with all possible PAM sites
- Activity score: 0.719
- Forward direction

**130kb Region**
- ~129,750kb-132,300kb
- Intergenic region used to find CRISPR sites: 1,189bp
- Entire intergenic region between closest genes: 2,822bp
  - 123bp left side
  - 1589bp right side
- GC% in entire intergenic region: 30%
- 5 repeat regions within the larger region, but none within the CRISPR site region
- Flanking genes:
  - gp88 657bp
  - gp89 426bp
  - gp90 2748bp

![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/130kb-region.png)

sgRNA 42
- Basepairs with PAM: TCGATATTGGTCACCCAGAG**GGG**
- No off-target sites in DiNV or BACs (in CDS)
- No worrisome off-target hits in the _D. virilis_ genome, at most a 15/15bp match (compared to a 20bp long guide sequence), this is with all possible PAM sites
- Activity score: 0.701
- Forward direction

sgRNA 53  
- Basepairs with PAM: ATACATATACACTTGATGGG**TGG**
- No off-target sites in DiNV or BACs (in CDS)
- No worrisome off-target hits in the _D. virilis_ genome, at most a 14bp match (compared to a 20bp long guide sequence), this is with all possible PAM sites
- Activity score: 0.666
- Reverse direction


### Creating sgRNA templates for use with the [EnGen® sgRNA Synthesis Kit, S. pyogenes (NEB #E3322)](https://www.neb.com/products/e3322-engen-sgrna-synthesis-kit-s-pyogenes#Product%20Information) for these 4 sgRNAs

Need to design oligos with the 20 nucleotide guide sequence and the appropriate upstream and downstream sequences for the kit that we can then have synthesized for us by an oligo company. This will be a "primer" that can be put into the kit and will make sgRNAs

**Steps in synthesis kit [protocol]((https://www.neb.com/protocols/2016/05/11/engen-sqrna-synthesis-kit-s-pyogenes-protocol-e3322))**
1. Target sequences should be 20nt long (yes), and they don't include the PAM. PAM is on the 5' end
2. If there is not a G at the 5' end of the sequences, add 1
  - 86: 5' **G**ACACAAGTGTTGTTATACGA 3'
  - 92: 5' **G**AAAAAATGCACTAAAACACA 3'
  - 42: 5' **G**TCGATATTGGTCACCCAGAG 3'
  - 53: 5' **G**ATACATATACACTTGATGGG 3'
3. To the 5´ end add the T7 promoter sequence: TTCTAATACGACTCACTATA
  - 86: 5' **TTCTAATACGACTCACTATA**GACACAAGTGTTGTTATACGA 3'
  - 92: 5' **TTCTAATACGACTCACTATA**GAAAAAATGCACTAAAACACA 3'
  - 42: 5' **TTCTAATACGACTCACTATA**GTCGATATTGGTCACCCAGAG 3'
  - 53: 5' **TTCTAATACGACTCACTATA**GATACATATACACTTGATGGG 3'
4. To the 3´ end; append 14 nucleotide overlap sequence: GTTTTAGAGCTAGA
  - 86: 5' **TTCTAATACGACTCACTATA**GACACAAGTGTTGTTATACGA**GTTTTAGAGCTAGA** 3'
  - 92: 5' **TTCTAATACGACTCACTATA**GAAAAAATGCACTAAAACACA**GTTTTAGAGCTAGA** 3'
  - 42: 5' **TTCTAATACGACTCACTATA**GTCGATATTGGTCACCCAGAG**GTTTTAGAGCTAGA** 3'
  - 53: 5' **TTCTAATACGACTCACTATA**GATACATATACACTTGATGGG**GTTTTAGAGCTAGA** 3'
5. Check complete oligo sequence
  - 86: 5' TTCTAATACGACTCACTATAGACACAAGTGTTGTTATACGAGTTTTAGAGCTAGA 3'
  - 92: 5' TTCTAATACGACTCACTATAGAAAAAATGCACTAAAACACAGTTTTAGAGCTAGA 3'
  - 42: 5' TTCTAATACGACTCACTATAGTCGATATTGGTCACCCAGAGGTTTTAGAGCTAGA 3'
  - 53: 5' TTCTAATACGACTCACTATAGATACATATACACTTGATGGGGTTTTAGAGCTAGA 3'


### Designing PCR primers to amplify regions around sgRNAs to do Cas9 digestion assay on to test Cas9 activity

**There are primers for 77kb region [that I desgined previously](https://meschedl.github.io/Unckless-Lab-Notebook-Maggie/2022/02/01/DiNV-77000bp-primer-design.html)**

I decided on F-2 and R-2 primers because their Tms match closely. They are:   
- Candidate 2 for forward primer: 76,760 - 76,781bp (77-DiNV-F-2)
- Tm: 57.4 degrees C
  - GC content: 40.9%
  - No hairpin
  - Sequence: GTGCAAAGTCAAGTTGTCAGAT
- Canidate 2 for reverse primer: 78,659 - 78,651bp (77-DiNV-R-2)
  - Length: 23nt
  - Tm: 57.5 degrees C
  - GC content: 43.5%
  - No hairpin
  - Sequence: CCTCAGTAGCCGTATCAAGTATT
- The length of the PCR product should be 1,891bp

Now to determine what the banding pattern would be in a digest assay where Cas9 cuts the 1,891bp fragment at a site determined by our sgRNAs   
- sgRNA 86 cuts at about 77,459bp
  - Subtract the cutsite bp and the end to end primer locations to get the size fragments
  - 77,459 - 76,760 = 699bp
  - 78,651 - 77,459 = 1,192bp
  - These fragments are definitely different enough to be easily seen on a gel
- sgRNA 92 cuts at about 77,229bp
  - Subtract the cutsite bp and the end to end primer locations to get the size fragments
  - 77,229 - 76,760 = 469bp
  - 78,651 - 77,229 = 1,422bp
  - These fragments are definitely different enough to be easily seen on a gel

**I needed to design primers for the 130kb region, I used the same resources as I used previously ([Geneious Primer Design Tutorial](https://www.geneious.com/tutorials/primer-design-prime/), [guidelines for primer design from Addgene](https://www.addgene.org/protocols/primer-design/) and [Zymo Research](https://www.zymoresearch.com/blogs/blog/how-to-design-primers-for-pcr-experiments))**

- Candidate 2 for forward primer: 128,180 - 128,202bp (130-DiNV-F-2)
  - Length: 23nt
  - Tm: 59 degrees C
  - GC content: 39.1%
  - No hairpin
  - Sequence: AAGTCGCCATTCAACACCAATAT
- Candidate 1 for reverse primer: 131,095 - 131,117bp (130-DiNV-R-1)
  - Length: 23nt
  - Tm: 58 degrees C
  - GC content: 43.5%
  - No hairpin
  - Sequence: TTTGTGGAGGATAGGCAGATAAC
- The length of the PCR product will be 131,117 - 128,180 = 2,937bp

Determining the banding pattern with the Cas9 digest assay
- sgRNA 42 cuts at about 130,667bp
  - Subtract the cutsite bp and the end to end primer locations to get the size fragments
  - 130,667 - 128,180 = 2,487bp
  - 131,117 - 130,667 = 450bp
  - These fragments are definitely different enough to be easily seen on a gel
- sgRNA 53 cuts at about 130,182bp
  - Subtract the cutsite bp and the end to end primer locations to get the size fragments
  - 130,182 - 128,180 = 200,2bp
  - 131,117 - 130,182 = 935bp
  - These fragments are definitely different enough to be easily seen on a gel
