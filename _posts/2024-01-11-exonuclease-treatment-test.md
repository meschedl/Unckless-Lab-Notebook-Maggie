---
layout: post
title: Testing Exonuclease Treatment on DNA Samples 
---

## Testing Exonuclease V on Hirt Extracts to Attemp to Remove Linear DNA 

The issue with the DNA extractions I've done to get DiNV DNA is that they always contain a lot of fly/cell DNA in the sample, even when I try the Hirt extraction which is supposed to enrich for epichromosomal DNA. I did some researching and I found that NEB sells an [exonuclease V](https://www.neb.com/en-us/products/m0345-exonuclease-v-recbcd#Protocols,%20Manuals%20&%20Usage) which is used for "Degradation of contaminating linear DNA in plasmid samples
and removal of residual gDNA after purification of low copy plasmid". That's not exactly what I've got, but similar, I want to remove the linear DNA and only keep DNA that is circular, which would be the intact DiNV genomes. I think the genomes are still circular and intact, but to be honest I'm not sure. Anyways, I thought I would try this out and see what I would get. I thought I could even try this on samples were the DNA is degraded, but I think it is just the cellular DNA that is degraded and that the capsids probably protected the virus DNA when the clarification pellet samples were in the fridge for weeks. I am using DNA from the most recent [hirt extraction](https://meschedl.github.io/Unckless-Lab-Notebook-Maggie/2024/01/10/week-15-exp-evo-sample.html) to test out this treatment.

**20230110 Qubit**

- First I quantified the DNA extractions 
- Followed this [Qubit protocol](https://docs.google.com/document/d/1ZCz0SBof6LHE3P_LbftawFyexl8iCECUlvjIcauPYwY/edit?usp=drive_link) 
- 16 : 56.2ng/ul
- 17: 58ng/ul 
- 18: 507ng/ul 
- 19: 443ng/ul

**20240111 Exonuclease Treatment**

- There are two protocols form NEB on how to use the exonuclease enzyme, they are pretty similar, so I ended up chosing one to go with because this one didn't use EDTA to inactivate stop the reaction (not sure why this is needed if you also heat inactivate it). I used [this protocol](https://www.neb.com/en-us/protocols/2017/11/28/removal-of-residual-gdna-after-purification-of-low-copy-plasmid-using-exonuclease-v-recbcd) starting with step 6. The other protocol is [this](https://www.neb.com/en-us/protocols/0001/01/01/a-typical-exonuclease-v-reaction-m0345) which recommends cleaning up the sample, which I'll need to do if it will go through the eletroporator, so I did cleanups as well
- I wanted to somewhat standardize the amount of DNA put into the treatment between the samples, although they do have very different concentrations depending on the original sample type 

|sample|DNA|10mM Tris to 30ul|total DNA|
|---|---|---|---|
|16|5.3ul|24.7ul|300ng|
|17|5.17ul|24.8ul|300ng|
|18|2ul|28ul|~900ng|
|19|2ul|28ul|~900ng|

- All DNA was kept on ice, flicked to mix, and spun down before use 
- All reagents were thawed on ice, vortexed to mix, and spun down before use 
- The enzyme was not frozen, and was spun down before use 
- DNA was diluted into 1.5mL tubes 
- To each diluted sample tube:
    - Added 4ul of NEBuffer 4
    - Added 4ul of ATP
    - Added 2ul of exonuclease V 
- Tubes were flicked to mix and spun down 
- Tubes were placed in the 37C heat block for 1 hour 
- Then tubes were placed in a 70C heat block for 30 minutes to inactivate the enzyme 
- Samples were kept on ice while awaiting cleanup

The NEB protocol recommended a spin column cleanup or a phenol-chloroform extraction on the DNA, I decided to try both (I worry that the spin column sheers DNA). If this works and I want to use DNA from this in an electroporation, then I need the enzyme and buffer out of the solution to prevent arching during electroporation, so I need to do some sort of cleanup. 

**NEB Monarch DNA Cleanup**

- Using samples 16 and 18 for this 
- Using [NEB Monarch PCR and DNA kit protocol](https://www.neb.com/en-us/protocols/2015/11/23/monarch-pcr-and-dna-cleanup-kit-protocol)
- Warmed DNA elution buffer to 50C in heatblock
- Increased the volume in the tubes from 40ul to 200ul with 160ul of 10mM tris 
- Added a 2:1 ratio of DNA binding buffer to the tubes: 400ul each 
- Pipette mixed the samples 4 times with clipped pipette tips 
- Added the total volume (~600) of each sample to their own spin column 
- Centrifuged the columns at 16,000rcf for 1 minute
- Discarded the flow through 
- Added 200ul DNA wash buffer to the columns
- Centrifuged the columns at 16,000rcf for 1 minute
- Discarded the flow through
- Added another 200ul DNA wash buffer to the columns
- Centrifuged the columns at 16,000rcf for 1 minute
- Discarded the flow through
- Centrifuged the columns at 16,000rcf for 1 minute "dry"
- Transferred the columns to new labeled 1.5mL tubes
- Added 20ul of warmed DNA elution buffer to the center of the filter and waited 2 minutes 
- Centrifuged the columns at 16,000rcf for 1 minute
- Placed the samples in the 4C for storage 

**Phenol-Chloroform Cleanup**

- Using samples 17 and 19
- Basing protocol off of what I've done in the hirt extractions ([see example](https://meschedl.github.io/Unckless-Lab-Notebook-Maggie/2024/01/10/week-15-exp-evo-sample.html) and this [document](https://www.mhh.de/fileadmin/mhh/genomics/download/methods/Genomics_Phenol-Chloroform-Extraction.pdf))
- All work was done in the fume hood
- Increased volume in samples to 300ul with 260ul of 10mM tris 
- Added equal volume (~300ul) of cold phenol-chloroform isoamy alcohol
- Inverted to mix
- Placed tubes on orbital shaker for 10 minutes 
- Centrifuged tubes for 15 minutes at 16,000rcf at room temp 
- Removed the top layer into new final labeled tubes:
    - 17: 300ul 
    - 19: 300ul 
- Added 0.1X volume (30ul) of 3M sodium acetate to each tube 
- Added 2-2.5X volume of cold 100% ethanol to each tube: I added 900ul and I now realize that was 3X so it might have been too much
- Mixed by inverting many times 
- Placed samples in the -20 overnight 
- Next day 20240112 
- Placed the centrifuge in the 4C for about an hour 
- Centrifuged tubes at 4C for 30 minutes at 16,000rcf 
    - I did not really see a pellet after this
- Poured off the supernatant into the waste 
- Added 500ul of cold fresh 80% ethanol 
- Inverted the tubes twice 
- Centrifuged the tubes at 4C for 30 minutes at 16,000rcf 
- Poured off the supernatant into the waste 
- Let tubes dry for ~15 minutes upside down 
- Resuspended the pellet in 19ul of 10mM tris 
- Let pellet resuspend for and hour or two at room temp 

**20240112 Qubit**

- High sensitivity Qubit of the exonuclease treated samples, there may not really be anything left in these
- Followed this [Qubit protocol](https://docs.google.com/document/d/1ZCz0SBof6LHE3P_LbftawFyexl8iCECUlvjIcauPYwY/edit?usp=drive_link) 
- 16: too low
- 17: 8.5
- 18: 3.91
- 19: too low

I am not sure what to make of this, there isn't a pattern between samples or methods of cleanup with who seemed to work and who didn't. I will try to qPCR all the samples anyways. 
