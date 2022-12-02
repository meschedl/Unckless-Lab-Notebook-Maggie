---
layout: post
title: Testing pAc5 GFP Transfection on DV-1 Cells
---

## Testing Transfection and pAc5 GFP Expression on DV-1 Cells

Because we are getting no GFP expression in the innubila primary cells, it is hard to tell if it is because the transfection is not working or if the promoter in front of GFP does not work for innubila. We decided to test the pAc5 plasmid on DV-1 cells to give us more information. If it doesn't work on these cells, it is likely a promoter issue. If it does work on these cells, we are still left unsure.

**20221115 Plating S2 and DV-1 cells**

- I want to use S2 cells again as a control to show that the transfection works
- I want to plate these at a density of 0.8-3 * 10^5 cells as per the instructions for the transfection reagents. I am testing both the [TransIT®-Insect Transfection Reagent](https://www.mirusbio.com/products/transfection/transit-insect-transfection-reagent) and the [TransIT®-2020 Transfection Reagent](https://www.mirusbio.com/products/transfection/transit-2020-transfection-reagent)
- First I need to count how many cells I actually have to use
- I cell scrapped 2 S2 cell flasks, centrifuged them for 3 minutes at 800rpm, and removed the liquid. Then the cell pellet was resuspended in 1mL of 10% FBS Schneider's medium
- 20ul from the resuspention was added to a hemocytometer and counts from each section of the hemocytometer were taken:

|section|quadrant 1|quadrant 2| quadrant 3| quadrant 4|section average|
|---|---|---|---|---|---|
|1|339|318|351|353|340|
|2|350|326|318|339|333|

- Each section was averaged, and the average of the two sections was taken
  - Total S2 average: 337
- The cells per mL is the average * 10^4
  - 337 * 10^4 = 3,370,000 total cells (there is only 1 mL)
- Now I need to dilute this so that I add ~1.5 * 10^5 cells to each well in 1.5mL aliquoits, meaning that I actually want 2.25 * 10^5 cells in total (this might not have been the correct calculation)
- I calculated this weird, to figure out how much for that many cells in 1mL, then added more volume of dilutant so it would be in 1.5mL
- (3.37 * 10^6 cells/mL)*(1mL) = (2.25 * 10^5 cells)(x mL)
  - x = 14.97 (* 1.5) = 22.5mL (this is a 1:22.5 dilution)
- So I added 21.5 mL of 10% FBS Schneider's medium to the 1mL of liquid, mixed, and aliquoited out 1.5mL to wells A1, A2, and A3 of a 12 well plate. The other liquid I used to seed two new t25 flasks
- I cell scrapped 1 DV-1 cell flasks, centrifuged them for 3 minutes at 800rpm, and removed the liquid. Then the cell pellet was resuspended in 2mL of 10% FBS Schneider's medium
- 20ul from the resuspention was added to a hemocytometer and counts from each section of the hemocytometer were taken:

|section|quadrant 1|quadrant 2| quadrant 3| quadrant 4|section average|
|---|---|---|---|---|---|
|1|343|314|316|323|324|
|2|156|264|327|196|236|

- Each section was averaged, and the average of the two sections was taken
  - Total DV-1 average: 280
- The cells per mL is the average * 10^4
  - 280 * 10^4 = 2,800,000 cells per mL or 5.6 * 10^6 cells total because there are 2 mL
- Now I need to dilute this so that I add ~1.5 * 10^5 cells to each well in 1.5mL aliquoits, meaning that I actually want 2.25 * 10^5 cells in total (this might not have been the correct calculation)
- I calculated this weird, to figure out how much for that many cells in 1mL, then added more volume of dilutant so it would be in 1.5mL
- (5.6 * 10^6 cells/mL)*(1mL) = (2.25 * 10^5 cells)(x mL)
  - x = 24.8 (* 1.5) = 38mL (this is a 1:38 dilution)
  - I did not want to use that much medium, so I scaled it down by 5, so I diluted 0.5mL of cells in 9mL of mediu
  - Note: I now realize that this calculation was wrong, I should have used 2.8*10^6 instead of 5.6 *10^6 but hopefully this will be fine
- I then aliquoited out 1.5mL to wells B1, B2, B3, C1, C2, and C3 of the same 12 well plate
- The plate was left to grow overnight in the 23 degree incubator

**20221116 Transfection**

- Plate layout:
![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/20221116-transfection-layout.png)
- First I concentrated another extraction of the pAc5 plasmid to be ~1ug/ul 
- The total volume is 124ul 
- Tube 2 is 171ng/ul 
  - 171ng/ul in 124ul is 21,204ng total 
- I bead cleaned the sample and resuspended it in 21ul of 10mM tris HCl 
- Insect and 2020 reagents were thawed at room temp and vortexed and spun down 
- All work was done in the cell culture hood 
- There are 3 experimental conditions: medium, insect reagent, or 2020 reagent, so 3 reagent tuebs were created:
- Tube 1
  - 300ul Schneider's medium 
- Tube 2 
  - 300ul Schneider's medium 
  - 3ul concentrated pAc5 plasmid 
  - 6ul insect transfection reagent 
- Tube 3 
  - 300ul Schneider's medium 
  - 3ul concentrated pAc5 plamsid 
  - 6ul 2020 transfection reagent 
- Tubes were pipette mixed and let incubate in the hood for 30 minutes 
- After the 30 minute incubation, all experimental reagents were added dropwise to the appropiate wells 
- 100ul of tube 1 to wells A1, B1, and C1
- 103ul of tube 2 to wells A2, B2, and C2
- 104ul of tube 3 to wells A3, B3, and C3 
- The plate was gently rocked back and forth then placed in the 23 degree incubator overnight 

The plate was imaged ~every 24 hours with a scope capable of visualizing GFP. Images can be found [here](https://docs.google.com/presentation/d/1jrQXVzdZGcpzX34lkhn6NhapYGx49aBSLuyoHH8fxBE/edit#slide=id.p). Only day 3 was not imaged. Imaging stopped after day 6. 