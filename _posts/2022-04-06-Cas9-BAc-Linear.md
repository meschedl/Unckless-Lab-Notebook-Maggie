---
Layout: post
title: Cas9 Site for BAC Linearization
---

## Randomly Generating a Set of Cas9 Sites to Use For Potential BAC Linearization - 2 Methods

**20220406**

Another method of linearizing the BAC before transfection would be to cut it with Cas9. For this, we would have to generate a random set of 23 bases and a PAM site to have synthesized in our BAC, so that it can split open in the correct place (between the left homology arm and the Amp resistance gene).

- I did not know how exactly to do this, but in Geneious I created a new folder with DiNV, pBACe3.6, pBeloBAC11, the GFP gene, and the AmpR gene and cat promoter (still not 100% on if I got that sequence correct)
- Then I picked a random region of DiNV: 57,074 to 58,001, and used the program to find Cas9 sites in that region
- The program should have checked those other files in the folder to see if there were any off target cuttings possible
- Then I picked 3 Cas9 sites that have the highest activity score to potentially use (however if the activity score takes into account surrounding DNA, this will not mean anything in the BAC context)
  - 1: 5' CAAAAGCTTATATTTCAATG**CGG** 3' activity 0.692
  - 2: 5' AAAGATTGCGAATTTAACGG**TGG** 3' activity 0.683
  - 3: 5' CCAGTCACACCAAAAACACT**GGG** 3' activity 0.628


**20220427**

After talking with Rob, we decided that a random species DNA should be used to insert a fragment into the BAC with a sgRNA site. We used the narwhal (_Monodon monoceros_)
which is incredibly different then a fly or a virus so there should be no chance of homology. Additionally, this sequence shouldn't be included in the BAC-DiNV so the DNA content shouldn't matter.


- Seached _Monodon monoceros_ in  NCBI Gene and picked the 1st gene: myoglobin Gene ID: 114885572
- Downloaded it into Geneious in a folder with:
  - DiNV sequence
  - GFP gene sequence
  - Ampicillin resistance gene sequence
  - pBeloBAC11 sequence
  - pBAce3.6 sequence
- The gene is ~14,000 bases long, so I picked a region between 7,001 and 7,542 bp to look for Cas9 sites
- Used the Geneious program to look for sgRNAs, hopefully checking everything in that folder for off target hits
- Picked the top 3 high scoring sgRNAs:
  - 64: 5' ACTTGGGGTATTGAGTCACG**GGG** 3' activity score 0.758
  - 61: 5' GATGTCTTGAAGGAGACTTG**GGG** 3' activity score 0.735
  - 70: 5' GGATCAGAGAGAACTGCCTG**GGG** 3' activity score 0.717
- These are all within ~90 bases of each other
- We probably want a 100-150bp sequence around these sites to add into the BAC?
- Extract out the sequence between 7,310 and 7,440
- Saved [here](https://github.com/meschedl/Unckless_Lab_Resources/blob/main/BAC-DiNV/Homology_Arm_Sequences/MB-114885572-130bp-linearisation-region-Mm.txt)
- I'm not sure exactly if we'll try one sgRNA to linearize or all 3, I'm not sure how I would be able to tell if the linearization happened properly with the BAC because it will just go from circular to linear...
