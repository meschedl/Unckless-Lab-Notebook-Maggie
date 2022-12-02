---
layout: post
title: Testing Different Ratios of Transfection Reagent to pAc5 GFP Plasmid in Dv-1 Cells
---

## Testing Transfection Reagent Volumes for Increased GFP in Dv-1 Cells 

With the recomended amounts of TransIT®-Insect Transfection Reagent](https://www.mirusbio.com/products/transfection/transit-insect-transfection-reagent) and the [TransIT®-2020 Transfection Reagent](https://www.mirusbio.com/products/transfection/transit-2020-transfection-reagent) for Dv-1 cells there was only a mild expression of GFP. The protocols say I can use 1-4ul of reagent per 1ug of DNA, so I will be testing the volumes of reagent I haven't previously used. 

**20221129 Plating S2 and DV-1 cells**

- I want to use S2 cells again as a control to show that the transfection works
- I want to plate these at a density of 0.8-3 * 10^5 cells as per the instructions for the transfection reagents. I have been doing 1.5 * 10^5 and it has been working well
- Need to count cells and then separate
- Plate layouts:
![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/20221201-plate-5-plate-6-transfection.png)
- This means I will need 3 wells of S2 cells (4.5mL total volume) and 18 wells of Dv-1 cells (27mL total volume)
- S2 cells 
- I cell scrapped one flask from 11/22 and centrifuged it at 800rpm 2 minutes, removed the supernatant, and resuspended the pellet in 6mL of 10% FBS Schneider's medium
- 20ul from the resuspention was added to a hemocytometer and counts from each section of the hemocytometer were taken:

|section|quadrant 1|quadrant 2| quadrant 3| quadrant 4|section average|
|---|---|---|---|---|---|
|1|310|235|262|382|297|
|2|287|378|330|339|333|

- Each section was averaged, and the average of the two sections was taken
  - Total S2 average: 315
- The cells per mL is the average * 10^4
  - 315 * 10^4 = 3,150,000 cells per mL 
- Now I need to dilute this so that I add ~1.5 * 10^5 cells to each well in 1.5mL aliquoits
- I used M1V1=M2V2 to determine how much volume would be needed to dilute the entire concentrated liquid, and then scaled down for the volume I actually needed
- (3.15 * 10^6 cells/mL)*(6mL) = (1.5 * 10^5 cells)(x mL)
  - x = 105mL 
- I don't need this much volume, so I divided the original volume (6mL) and dilution volume by 7 
    - Added 14.1mL medium to a new tube
    - Used 0.86mL of the concentrated cell suspension to that tube
- These were mixed and added to the A1, B1, and C1 wells of PLATE 5
- Dv-1
- I cell scrapped 1 Dv-1 cell flask, centrifuged them for 3 minutes at 800rpm, and removed the liquid. Then the cell pellet was resuspended in 5mL of 10% FBS Schneider's medium
- 20ul from the resuspention was added to a hemocytometer and counts from each section of the hemocytometer were taken:

|section|quadrant 1|quadrant 2| quadrant 3| quadrant 4|section average|
|---|---|---|---|---|---|
|1|348|356|343|365|353|
|2|261|284|339|304|297|

- Each section was averaged, and the average of the two sections was taken
  - Total Dv-1 average: 325
- The cells per mL is the average * 10^4
  - 325 * 10^4 = 3,250,000 cells per mL 
- I used M1V1=M2V2 to determine how much volume would be needed to dilute the entire concentrated liquid, and then scaled down for the volume I actually needed
- (3.25 * 10^6 cells/mL)*(5mL) = (1.5 * 10^5 cells)(x mL)
  - x = 108.3mL 
- I don't need this much volume, so I divided the original volume (5mL) and dilution volume by 3
    - Added 36mL medium to a new tube
    - Used 1.7mL of the concentrated cell suspension to that tube
- These were mixed and added to wells: 
    - PLATE 5: A2, B2, C2, A3, B3, C3, A4, B4, C4
    - PLATE 6: A1, B1, C1, A2, B2, C2, A3, B3, C3
- The plate was left to grow overnight in the 23 degree incubator

**20221130 Transfection**
- First I concentrated another extraction of the pAc5 plasmid to be ~1ug/ul, and added it to the previous concentration so that I would use a homogenous mixture of plasmid
- The total volume is 124ul 
- Tube 3 is 158ng/ul 
  - 158ng/ul in 124ul is 19,592ng total 
- I bead cleaned the sample and resuspended it in 19ul of 10mM tris HCl 
- I checked the densities of the cells before doing the transfections. There seem to be a few more cells in the S2 dishes than the Dv-1 dishes even though I tried to make them standardized 
- S2
![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/20221201-S2-BF.jpeg)
![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/20221201-S2-BF-2.jpeg)
- Dv-1
![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/20221201-Dv-1-BF.jpeg)
![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/20221201-Dv-1-BF-2.jpeg)
- Insect and 2020 reagents were thawed at room temp and vortexed and spun down 
- All work was done in the cell culture hood 
- All reaction mixes were made up beforehand:
- Tube 1
    - 700ul Schneider's medium 
- Tube 2
    - 100ul Schneider's medium 
    - 1ul concentrated pAc5 plasmid 
    - 2ul insect transfection reagent
- Tube 3
    - 100ul Schneider's medium 
    - 1ul concentrated pAc5 plasmid 
    - 3ul 2020 transfection reagent
- Tube 4
    - 200ul Schneider's medium 
    - 2ul concentrated pAc5 plasmid 
    - 2ul insect transfection reagent
- Tube 5
    - 200ul Schneider's medium 
    - 1ul concentrated pAc5 plasmid 
    - 6ul insect transfection reagent
- Tube 6
    - 200ul Schneider's medium 
    - 1ul concentrated pAc5 plasmid 
    - 8ul insect transfection reagent
- Tube 7
    - 200ul Schneider's medium 
    - 1ul concentrated pAc5 plasmid 
    - 2ul 2020 transfection reagent
- Tube 8
    - 200ul Schneider's medium 
    - 1ul concentrated pAc5 plasmid 
    - 4ul 2020 transfection reagent
- Tube 8
    - 200ul Schneider's medium 
    - 1ul concentrated pAc5 plasmid 
    - 8ul 2020 transfection reagent
- All reaction tubes were pipette mixed genetly
- Let tubes incubate in the hood for 30 minutes
- After the 30 minute incubation, all experimental reagents were added dropwise to the appropiate wells 
- 100ul tube 1 to P5 wells A1, A2, A3, A4, and P6 A1, A2, and A3
- 103ul tube 2 to P5 B1
- 104ul tube 3 to P5 C1
- 102ul tube 4 to P5 B2 and P5 C2
- 104ul tube 5 to P5 B3 and P5 C3 
- 105ul tube 6 to P5 B4 and P5 C4
- 102ul tube 7 to P6 B1 and P6 C1
- 103ul tube 8 to P6 B2 and P6 B2
- 105ul tube 9 to P6 B3 and P6 B3
- Plates were gently rocked back and forth and placed in the 23 degree incubator to be checked every 24 hours for a few days 

The plate was imaged ~every 24 hours with a scope capable of visualizing GFP. Images can be found [here](https://docs.google.com/presentation/d/1bNv9RPDE939QAX3hpzE6KaK424HyY-9GDZRhaFHa43I/edit#slide=id.p)
