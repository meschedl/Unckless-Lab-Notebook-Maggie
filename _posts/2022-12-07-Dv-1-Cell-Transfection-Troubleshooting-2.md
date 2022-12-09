---
layout: post
title: Testing Reduced Ratios of Transfection Reagent to pAc5 GFP Plasmid in Dv-1 Cells
---

## Testing 0.5-0.75ul 2020 Transfection Reagent Volumes for Increased GFP in Dv-1 Cells 

Using the [TransIT®-2020 Transfection Reagent](https://www.mirusbio.com/products/transfection/transit-2020-transfection-reagent) which had the best transfection at 1ul for the previous test, now I want to test less than 1ul transfection reagent volumes. I am not using the other reagent in this test. I will try 0.75ul 2020 reagent and 0.5ul 2020 reagent. 

**20221209 Plating S2 and DV-1 cells**

- I want to use S2 cells again as a control to show that the transfection works
- I need to use the same density I have used previously: 1.5 * 10^5 cells per well in a 12 well plate
- Need to count cells and then separate
- Plate layout:
![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/20221209-plate-7-layout.png)
- This means I will need 3 wells of S2 cells (4.5mL total volume) and 9 wells of Dv-1 cells (13.5mL total volume)
- S2 cells 
- I cell scrapped one flask from 11/29 and centrifuged it at 800rpm 2 minutes, removed the supernatant, and resuspended the pellet in 6mL of 10% FBS Schneider's medium
- 20ul from the resuspention was added to a hemocytometer and counts from each section of the hemocytometer were taken:

|section|quadrant 1|quadrant 2| quadrant 3| quadrant 4|section average|
|---|---|---|---|---|---|
|1|273|265|259|259|264|
|2|278|252|276|267|268|

- Each section was averaged, and the average of the two sections was taken
  - Total S2 average: 266
- The cells per mL is the average * 10^4
  - 266 * 10^4 = 2,660,000 cells per mL 
- Now I need to dilute this so that I add ~1.5 * 10^5 cells to each well in 1.5mL aliquoits
- I used M1V1=M2V2 to determine how much volume would be needed to dilute the entire concentrated liquid, and then scaled down for the volume I actually needed
- (2.66 * 10^6 cells/mL)*(5mL) = (1.5 * 10^5 cells)(x mL)
  - x = 89mL 
- I don't need this much volume, so I divided the original volume (5mL) and dilution volume by 5 
    - Added 16.8mL medium to a new tube
    - Used 1mL of the concentrated cell suspension to that tube
- These were mixed and added to the A1, B1, and C1 wells of PLATE 7
- The rest of the diluted S2 cells were seeded into new flasks 
- Dv-1
- I cell scrapped 1 Dv-1 cell flask, centrifuged them for 3 minutes at 800rpm, and removed the liquid. Then the cell pellet was resuspended in 5mL of 10% FBS Schneider's medium
- 20ul from the resuspention was added to a hemocytometer and counts from each section of the hemocytometer were taken:

|section|quadrant 1|quadrant 2| quadrant 3| quadrant 4|section average|
|---|---|---|---|---|---|
|1|310|365|336|294|326|
|2|377|357|286|344|316|

- Each section was averaged, and the average of the two sections was taken
  - Total Dv-1 average: 321
- The cells per mL is the average * 10^4
  - 321 * 10^4 = 3,210,000 cells per mL 
- I used M1V1=M2V2 to determine how much volume would be needed to dilute the entire concentrated liquid, and then scaled down for the volume I actually needed
- (3.21 * 10^6 cells/mL)*(5mL) = (1.5 * 10^5 cells)(x mL)
  - x = 107mL 
- I don't need this much volume, so I divided the original volume (5mL) and dilution volume by 4
    - Added 25.5mL medium to a new tube
    - Used 1.25mL of the concentrated cell suspension to that tube
- These were mixed and added to wells A2, B2, C2, A3, B3, C3, A4, B4, and C4
- The rest of the diluted Dv-1 cells were seeded into new flasks
- The plate was left to grow overnight in the 23 degree incubator

**20221208 Transfection**
- I am using the same concentration of the pAc5 plasmid as I used [previously](https://meschedl.github.io/Unckless-Lab-Notebook-Maggie/2022/11/30/Dv-1-Cell-Transfection-Troubleshooting.html)
- I checked the densities of the cells before doing the transfections. There seems to be similar amounts of cells in each plate, maybe a few more Dv-1 cells even though I tried to make them the same
- S2
![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/20221208-S2cells.jpeg)
- Dv-1
![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/20221208-Dv-1cells.jpeg)
- 2020 reagent was thawed at room temp and vortexed and spun down, so was the plasmid 
- All work was done in the cell culture hood 
- All reaction mixes were made up beforehand:
- Tube 1
    - 400ul Schneider's medium 
- Tube 2
    - 300ul Schneider's medium 
    - 3ul concentrated pAc5 plasmid 
    - 3ul 2020 transfection reagent
- Tube 3
    - 100ul Schneider's medium 
    - 1ul concentrated pAc5 plasmid 
    - 3ul 2020 transfection reagent
- Tube 4
    - 200ul Schneider's medium 
    - 2ul concentrated pAc5 plasmid 
    - 1.5ul 2020 transfection reagent
- Tube 5
    - 200ul Schneider's medium 
    - 1ul concentrated pAc5 plasmid 
    - 1ul 2020 transfection reagent
- All reaction tubes were pipette mixed genetly
- Let tubes incubate in the hood for 30 minutes
- After the 30 minute incubation, all experimental reagents were added dropwise to the appropiate wells 
- 100ul tube 1 to wells A1, A2, A3, and A4
- 102ul tube 2 to wells B1, C2, and C2
- 104ul tube 3 to well C1
- 101.75ul tube 4 to wells B3 and C3 
- 101.5ul tube 5 to wells B4 and C4
- Plates were gently rocked back and forth and placed in the 23 degree incubator to be checked every 24 hours for a few days 

The plate was imaged ~every 24 hours with a scope capable of visualizing GFP. Images can be found [here](https://docs.google.com/presentation/d/1Lh6BdXbA3bjOciCqfgqva2WxP_Q-UCU_VQOE_JtLI2g/edit#slide=id.g1b05fcf1f67_0_2)