---
layout: post
title: CRISPR Guide RNA Planning and Design
---

## Using [EnGen® sgRNA Synthesis Kit, S. pyogenes (NEB #E3322)](https://www.neb.com/products/e3322-engen-sgrna-synthesis-kit-s-pyogenes#Product%20Information) and [Protocol](https://www.neb.com/protocols/2016/05/11/engen-sqrna-synthesis-kit-s-pyogenes-protocol-e3322) To Design Oligos Needed for Making sgRNAs for DiNV

**Need to design oligos with the 20 nucleotide guide sequence and the appropriate upstream and downstream sequences for the kit that we can then have synthesized for us.**

- Using the top 3 guide RNA sites generated from Geneious that are within the 77,000 and 78,000 region of the DiNV genome. These are #s 92, 27, and 86. However #27 seems to have an off target BLAST hit of the sgRNA sequence to the _D. virilis_ genome. So we might not want to use that one. Guide RNA #73 has a lower activity score but no off target hits. Sequences from [here](https://docs.google.com/spreadsheets/d/1acKEhtuik99a1GFYlptgCU2GOdYW_kzExTAM02zrQvQ/edit#gid=854661509)
- Guide RNA 92 sequence: 5' AAAAAATGCACTAAAACACA, activity score: 0.719, reverse direction
- Guide RNA 27 sequence: 5' TGTATTGTCAGTGTGGGAGA, activity score: 0.716, forward direction
- Guide RNA 86 sequence: 5' ACACAAGTGTTGTTATACGA, activity score: 0.713, reverse direction
- Guide RNA 73 sequence: 5' ATCTAAATAAATACAATCGA, activity score: 0.623, reverse direction

**Steps in synthesis kit [protocol]((https://www.neb.com/protocols/2016/05/11/engen-sqrna-synthesis-kit-s-pyogenes-protocol-e3322))**
1. Target sequences should be 20nt long (yes), and they don't include the PAM. PAM is on the 5' end
2. If there is not a G at the 5' end of the sequences, add 1 (need to add to all because they all have an A)
  - 92: 5' **G**AAAAAATGCACTAAAACACA
  - 27: 5' **G**TGTATTGTCAGTGTGGGAGA
  - 86: 5' **G**ACACAAGTGTTGTTATACGA
  - 73: 5' **G**ATCTAAATAAATACAATCGA
3. To the 5´ end add the T7 promoter sequence: TTCTAATACGACTCACTATA
  - 92: 5' **TTCTAATACGACTCACTATA**GAAAAAATGCACTAAAACACA
  - 27: 5' **TTCTAATACGACTCACTATA**GTGTATTGTCAGTGTGGGAGA
  - 86: 5' **TTCTAATACGACTCACTATA**GACACAAGTGTTGTTATACGA
  - 73: 5' **TTCTAATACGACTCACTATA**GATCTAAATAAATACAATCGA
4. To the 3´ end add the 14 nucleotide overlap sequence: GTTTTAGAGCTAGA
  - 92: 5' **TTCTAATACGACTCACTATA**GAAAAAATGCACTAAAACACA**GTTTTAGAGCTAGA**
  - 27: 5' **TTCTAATACGACTCACTATA**GTGTATTGTCAGTGTGGGAGA**GTTTTAGAGCTAGA**
  - 86: 5' **TTCTAATACGACTCACTATA**GACACAAGTGTTGTTATACGA**GTTTTAGAGCTAGA**
  - 73: 5' **TTCTAATACGACTCACTATA**GATCTAAATAAATACAATCGA**GTTTTAGAGCTAGA**
5. Check final sequence to make sure it's copied right
  - 92: 5' TTCTAATACGACTCACTATAGAAAAAATGCACTAAAACACAGTTTTAGAGCTAGA
  - 27: 5' TTCTAATACGACTCACTATAGTGTATTGTCAGTGTGGGAGAGTTTTAGAGCTAGA
  - 86: 5' TTCTAATACGACTCACTATAGACACAAGTGTTGTTATACGAGTTTTAGAGCTAGA
  - 73: 5' TTCTAATACGACTCACTATAGATCTAAATAAATACAATCGAGTTTTAGAGCTAGA
