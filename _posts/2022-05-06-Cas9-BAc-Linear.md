---
Layout: post
title: Cas9 Site for BAC Linearization
---

## Randomly Generating a Set of Cas9 Sites to Use For Potential BAC Linearization


Another method of linearizing the BAC before transfection would be to cut it with Cas9. For this, we would have to generate a random set of 23 bases and a PAM site to have synthesized in our BAC, so that it can split open in the correct place (between the left homology arm and the Amp resistance gene).

- I did not know how exactly to do this, but in Geneious I created a new folder with DiNV, pBACe3.6, pBeloBAC11, the GFP gene, and the AmpR gene and cat promoter (still not 100% on if I got that sequence correct)
- Then I picked a random region of DiNV: 57,074 to 58,001, and used the program to find Cas9 sites in that region
- The program should have checked those other files in the folder to see if there were any off target cuttings possible
- Then I picked 3 Cas9 sites that have the highest activity score to potentially use (however if the activity score takes into account surrounding DNA, this will not mean anything in the BAC context)
  - 1: 5' CAAAAGCTTATATTTCAATG**CGG** 3' activity 0.692
  - 2: 5' AAAGATTGCGAATTTAACGG**TGG** 3' activity 0.683
  - 3: 5' CCAGTCACACCAAAAACACT**GGG** 3' activity 0.628 
