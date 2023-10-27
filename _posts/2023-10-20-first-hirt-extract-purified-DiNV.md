---
layout: post
title: First Attempt at Hirt DNA Extraction from Samples from DiNV Purification 
---

## Using the Clarification Pellet Samples From DiNV Purification for Hirt DNA Extraction for Viral DNA

Based on Kent's qPCR results, the clarification pellet had the most virus DNA, it also has a lot of cellular DNA and likely cellular debris, so I thought at the time that the Hirt extraction method that is supposed to remove chromosomal DNA would be the best option. The clarification pellet is a lot of material, about 20mL, so I decided to take a couple different samples types and try them. Each sample was taken in the cell culture hood into 1.5mL tubes

| sample # | sample type                                                     |
|----------|-----------------------------------------------------------------|
| 1        | 50ul clarification pellet                                       |
| 2        | 50ul clarification pellet                                       |
| 3        | 500ul clarification pellet, centrifuged and supernatant removed |
| 4        | 500ul clarification pellet, centrifuged and supernatant removed |
| 5        | 50ul clarification pellet, centrifuged and supernatant removed  |
| 6        | 50ul clarification pellet, centrifuged and supernatant removed  |

For the samples that had the supernatant removed, they were spun at 1000g for 3 minutes, the supernatant pipetted off and saved at 4C. As you can see with the gel results, and something I thought about only after I had started this process, was that the clarification pellet was kept at 4C since generating weeks ago. During this time likely the cellular DNA became very degraded because it wasn't frozen, or the 3 rounds of freeze thaws that Kent did on the material broke up the DNA really bad. It is possible that the virus DNA is still in tact, especially if it was contained in puncta, but there is so much cellular DNA it did not get removed. I could have used too large a volume of liquid as starting material to properly do the Hirt extraction possibly to get the cellular DNA out. Either way, none of these samples are useful except as nice positive controls for future PCRs. 

Because the last time I did these extractions was over a year ago, I remade all of the solutions. This ended up taking a while and the titration of some of the pHs was tricky and possibly did not go well. All solutions were made in 50mL conicals and in the hood. 

3M NaOac 50mL
- Dissolved 12.3g sodium acetate in 35mL of molecular grade water
- Checked pH with test strips. Goal is to be 4.8-5.2 pH. It started close to 8! I used glacial acetic acid to move it down to what I thought was 5
- Increased the volume to 50ul with molecular grade water 

1M Tris 50mL 
- I looked up that 1 liter is 121.1g in 800mL water
- So for 50mL that is 6.055g Tris base
- 40mL molecular grade water 
- Used 1N HCl (that I had made some time ago and was in a smaller jar, easier to handle) to adjust the pH to around 7.5 
- Brought volume up to 50mL with molecular grade water 

0.5M EDTA 50mL
- I looked up that 1 liter is 186.1g EDTA in 800mL water
- So for 50mL that is 9.305g EDTA solid (EDTA isodium salt is what we had)
- 40mL molecular grade water
- Used NaOH pellets to adjust pH to 8 (This took a long time, I over shot the pH, and brought it down with acetic acid, not sure if that was the right thing to do. The EDTA won't go into solution at a pH below 8)
- Brought volume up to 50mL with molecular grade water

1.2% SDS 50mL
- I purchased a new 10% solution from the Biostore 
- 6mL of 10% SDS
- 44mL of molecular grade water 

5M CsCl 10mL
- 9.318g CsCl
- Molecular grade water to 10mL (note adding water is cold reaction)

5M Potassium acetate 10mL
- 4.91g potassium acetate
- Molecular grade water to 10mL 

Mixed solutions:

50mM Tris HCl pH 7.5, 10mM EDTA 10mL
- 500ul 1M Tris HCl
- 200ul 0.5M EDTA
- 9.3mL molecular grade water 

3M CsCl, 1M potassium acetate, 0.67M acetic acid 10mL
- 6mL 5M CsCl
- 2mL 5M Potassium acetate
- 0.465mL glacial acetic acid 
- 1.18mL molecular grade water 

**Lysis and Chromosomal DNA Precipitation**

- Placed small centrifuge in fridge 
- Spun down samples 3,4,5,6 for 3 minutes at 1000g
- Removed supernatant and saved 
- Resuspended pellets in 147ul 50mM Tris HCl, 10mM EDTA 
- For samples 1 and 2 already in 50ul liquid, I added 100ul of 50mM Tris HCl, 10mM EDTA
- Prepared 5mg/mL RNase A
    - 12ul molecular grade water 
    - 12ul 10mg/mL RNase A
    - Vortexed and spun down to mix
- Added 3ul of 5mg/mL RNase A to each sample
- At this point I moved to the fume hood because the SDS kind of smelled bad and I wanted to be cautious 
- Added 150ul of 1.2% SDS to each tube
- Inverted tubes, gently resuspended pellet with clipped pipette tips to mix 
- Incubated tubes on bench for ~30 minutes to lyse/digest all cells
    - Very hard to tell, the 500ul samples did not fully lyse or digest, there was just too much material in there. The 50ul samples did sort of completely lyse, although there may have been a small amount of material still in them. I was inverting the samples frequently over the 30 minutes. I very briefly spun down the tubes after this
- Precipitated chromosomal DNA and cellular debris by added 210ul of 3M CsCl, 1M potassium acetate, 0.67M acetic acid
  - A white precipitate immediately started forming in the tubes, I pipette mixed the solution with clipped pipette tips
- Immediately placed tubes on ice for 35 minutes incubation 
- Centrifuged tubes for 15 minutes at 16,000rcf at 4 degrees C
- During this time I made fresh 80% and 100% ethanol and put them in the -20 freezer to cool
- Pipetted off supernatant into new 1.5mL tubes with clipped pipette tips
- Centrifuged new tubes for 15 minutes at 16,000rcf at 4 degrees C
  - There was basically no new precipitate here that pelleted
- Moved supernatant into new 1.5mL tubes ~500l

**Phenol Chloroform Extraction**

- Still in the fume hood
- Added equal volume (500ul) of cold phenol-chlorofomr-isoamy-alcohol to the tubes (Note!! phenol-chloroform-isoamy-alcohol is in two phases, I think you are supposed to use the bottom layer for this, see [x](https://hermanlab.unl.edu/protocols/phenolppt.html))
- Mixed tubes up and down and then put them on an orbital mixer in the hood for 10 minutes
- Centrifuged tubes at 16,000rcf at room temp for 15 minutes
- Looked for phase separation
  - Phase separation looked great, there were two distinct layers, and there was a white substance between the two (RNA?? protein??)
- Transferred top aqueous phase to new final labeled tubes
  - I did not try to get absolutely everything, I did not want to suck up both phases
  - 1: 430ul
  - 2: 430ul 
  - 3: 430ul 
  - 4: 440ul
  - 5: 445ul 
  - 6: 440ul
- Added 0.1X tube liquid volume of new 3M NaOAc to each tube
    - 1: 43ul
    - 2: 43ul 
    - 3: 43ul 
    - 4: 44ul
    - 5: 44.5ul
    - 6: 44ul
- Added 900ul of cold 100% ethanol to each tube
- Inverted tubes to mix
    - I immediately saw some precipitate form in samples 3 and 4, I thought it was DNA 
- Placed tubes in the -20 overnight

**DNA Precipitation 20231021**

- Took tubes out of the freezer and centrifuged tubes at max speed at 4C for 30 minutes
  - Tubes had not frozen in the freezer
  - All tubes had pellets, the pellets from 3 and 4 were really large and didn't look like all DNA...
- Pipetted off supernatant
- Added 500ul of cold fresh 80% ethanol and inverted twice to mix
- Centrifuged tubes at max speed at 4C for 30 minutes
- Removed all ethanol
- Let tubes dry ~60 minutes upside-down on the bench
- Resuspended pellets in 20ul of 10mM tris HCl and let resuspend in the 4C until Monday
- On Monday the DNA had not resuspended, so I placed them on the orbital shaker at room temp for ~8 hours, and that still did nothing 
- I decided to add more 10mM tris HCl
    - 30ul to tubes 1 and 2 
    - 50ul to tubes 3 and 4 
    - 5 and 6 did not need it, their pellet was resuspended it looked like
- Qubit:
  - 1: 191ng/ul
  - 2: 231ng/ul
  - 3: 925ng/ul
  - 4: 735ng/ul
  - 5: 183ng/ul
  - 6: 153ng/ul 

**TPI and p47 PCRs and Gels 20231024**

- There are 6 samples but the DNA concentrations are super large, so I need to dilute them for PCR
- I diluted each sample 1:10 and 1:50 in 10mM Tris HCl:
    - 2ul DNA in 18ul Tris 
    - 2ul DNA in 98ul Tris 
    - These were flick-mixed and spun down before use
- Include positive and negative control 
- Everything was thawed and kept on ice, and vortexed and spun down before use 
- TPI
    - 72.5ul GoTaq
    - 3.625ul TPI F
    - 3.625ul TPI R
    - 50.75ul molecular grade water 
- p47
    - 72.5ul GoTaq
    - 3.625ul p47 F
    - 3.625ul p47 R
    - 50.75ul molecular grade water
- Vortexed and spun down mixes 
- Added 9ul of mixes to strip tubes 
- Added 1ul of diluted DNA to tubes 
- Added 1ul of water for the negative control and 1ul known virus positive DNA for the positive control 
- Vortexed and spun down strip tubes 
- Placed tubes in PCR programs, 30 cycles for each. PCR program information can be found [here](https://docs.google.com/spreadsheets/d/1IaLLjsa4SXJr90wUi8xyE1dYvWmHsbThSz3d8N9KaK0/edit#gid=0)

I also wanted to gel the plain DNA to see the quality, but the concentrations are so high I wanted to dilute to ~100ng added to the well:
- 1: 2ul with 3ul water
- 2: 2ul with 3ul water
- 3: 1ul with 4ul water
- 4: 1ul with 4ul water
- 5: 2ul with 3ul water
- 5: 2ul with 3ul water

All samples were run on a 1% gel : large rectangle 70mL 1X TAE and 0.7g agarose, 1.5ul of Midori stain 

![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/20231024-gel.jpeg)



