---
layout: post
title: Investigating Blunt End Restriction Enzymes
---

## Looking into Blunt End Restriction Enzymes to Use for Linearizing our BAC


#### List of Blunt End Restriction Enzymes
**Looking at [this table](https://www.neb.com/tools-and-resources/selection-charts/recleavable-blunt-ends) from NEB**
- **Afel: AGC'GCT**
- AluI: AG'CT
- BsaAI: YAC'GTR
- BstUI: CG'CG
- **EcoRV: GAT'ATC**
- **FspI: TGC'GCA**
- HaeIII: GG'CC
- **HapI: GTT'AAC**
- HincII: GTY'RAC
- **MscI: TGG'CCA**
- MspA1I: CMG'CKG
- **Nael: GCC'GGC**
- **Nrul: TCG'CGA**
- **Pmel: GTTT'AAAC**
- **Pmll: CAC'GTG**
- **Pvull: CAG'CTG**
- Rsal: GT'AC
- **Sfol: GGC'GCC**
- **Smal: CCC'GGG**
- **SnaBl: TAC'GTA**
- **Sspl: AAT'ATT**
- **Stul: AGG'CCT**
- **Swal: ATTT'AAAT**

I don't want to use any that only recognize 4 bases, and I don't want to use any that recognize degenerate bases. I am trying to find one that wouldn't be anywhere in our BAC, so it has to be long/specific. That leaves 16 to look through (in bold).   
I'll have to look through the BAC sequence, the homology arm sequence, the GFP sequence, and the ampicillin resistance gene sequence. We don't have promotors figured out for GFP or Amp so I can't look through those...

#### Using [NEBCutter](https://nc3.neb.com/NEBcutter/prj/) to Look for Restriction Sites in Our Sequences

- First started with pBACe3.6
  - Used the NCBI accession number as input U80929.2
  - And used the additional preferences to indicate the 16 blunt end restriction sites above
  - Indicate that it's circular
  - This found 2 restriction enzymes with 0 cuts: Pmll and Swal
- Try with pBeloBAC11 U51113.1
  - They save your list of restriction sites which is so nice!
  - 3 enzymes with 0 cuts: Pmel, Pmll, and Swal
- Now to check other DNA sequences
- GFP from NCBI  L29345.1
  - Afel, EcoRV, Fspl, Nael, Nrul, Pmel, Sfol, Smal, SnaVl, Sspl, Stul, and Swal
    - Right now, Swal is the only one that works with all, and Pmel for GFP and pBeloBAc11
- Ampicillin gene
  - I could not find a easily accessable Amp resistnace gene sequence by googling! I had to take the sequence from [this plasmid's](https://www.snapgene.com/resources/plasmid-files/?set=basic_cloning_vectors&plasmid=pEZSeq-Amp) picture, and copy it into a text file to put into NEBcutter. But this should be the right sequence (?) I also included the cat promotor that's in front of the sequence in this plasmid, it did not change the number of 0 cutter enzymes
  - Afel, EcoRV, Hapl, Mscl, Nael, Nrul, Pmel, Pmll, Pvull, Sfol, Smal, SnaBl, Sspl, Stul, Swal
- From now going forward I am only going to look at the Pmel and Swal
- Now to look at homology arm sequences [listed here](https://github.com/meschedl/Unckless_Lab_Resources/tree/main/BAC-DiNV/Homology_Arm_Sequences)
  - 42-150-L: Pmel and Swal
  - 42-150-R: Pmel and Swal
  - 42-500-L: Pmel **NO Swal**
  - 42-500-R: Pmel and Swal
  - 53-150-L: Pmel and Swal
  - 53-150-R: Pmel and Swal
  - 53-500-L: Pmel and Swal
  - 53-500-R: Pmel **NO Swal**
  - 86-150-L: Pmel and Swal
  - 86-150-R: Pmel and Swal
  - 86-500-L: Pmel and Swal
  - 86-500-R: Pmel and Swal
  - 92-150-L: Pmel and Swal
  - 92-150-R: Pmel and Swal
  - 92-500-L: Pmel and Swal
  - 92-500-R: Pmel and Swal
- So It looks like a blunt end restriction digest would work if we end up using the 130kb section as our homology section, no matter the spot. But we would only be able to use pBeloBAC11 as our BAC and use Pmel as the restriction site if we were going to use the 77kb region 
