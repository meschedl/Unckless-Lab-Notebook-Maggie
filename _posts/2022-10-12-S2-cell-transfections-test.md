---
layout: post
title: Testing Mirus Bio Transfection Reagents on S2 Cells
---

## Testing Cell Transfection Reagents On S2 Cells and 2 GFP Expression Plasmids

I have 2 reagents from Mirus Bio that they sent me to test: The [TransIT®-Insect Transfection Reagent](https://www.mirusbio.com/products/transfection/transit-insect-transfection-reagent) and the [TransIT®-2020 Transfection Reagent](https://www.mirusbio.com/products/transfection/transit-2020-transfection-reagent). The insect reagent is supposed to be specific for insect cells, and the 2020 reagent says it can work on primary cells, which is why I want to test both. Ultimately I want to use this on primary innubila cells to see if I can get a promoter to express GFP and get a working promoter for innubila.

It took a long time to grow up S2 cells from frozen, about a month. And for this experiment I spent a while counting the cells to try to get them to the density needed to plate them. I won't put all of the cell counts in this notebook for simplicity sake, I had to combine 4 flasks of cells and concentrate them to get enough.

Plasmids were extracted [here](https://meschedl.github.io/Unckless-Lab-Notebook-Maggie/2022/09/08/plasmid-extraction-addgene.html) and confirmed via sequencing. pAc5 is a GFP expression plasmid with a melanogaster promoter. pCS2 is a GFP expression plasmid with a promoter that works for xenopus/zebrafish.

**20221011 Plating S2 cells**
- I decided to plan the experiment to use 2 12 well plates. Each plate will use a different plasmid
- The manuals for the transfection reagents say to plate cells at 0.8 - 3 x 10^5 cells/mL density
- 4 S2 flasks, 3 from 10/5 and 1 from 9/29 were cell scrapped, centrifuged at 200rpm for 5 minutes, and resuspended in 5mL 10% FBS Schneider's medium
- Cell counts were made with a hemocytometer that has two quantification sections. Each section has 4 quadrants. Each quadrant is 1mm squared. The number of cells in 1mm^2 * 10^4 is how many cells per mL. See [this link](http://microbiology.ucdavis.edu/privalsky/hemocytometer#:~:text=To%20count%20cells%20using%20a,number%20of%20cells%2Fsquare) for details
  - I counted each quadrant per section and averaged over those
  - Then I averaged over the section
- This was the final count:

|section|quadrant 1|quadrant 2| quadrant 3| quadrant 4|section average|
|---|---|---|---|---|---|
|1|63|77|66|77|70.75|
|2|78|56|43|58|58.75|

- The number of cells per ml:
  - Section 1: 707,500 or 7 * 10^5
  - Section 2: 587,500 or 5.8 * 10^5
- I estimated that I had ~6.5 * 10^5 cells in total, and my total volume was 5mL
  - Total number of cells is 6.5 * 10^5 * 5 = 3,250,000 cells
- If I divide this by 24 (the number of wells I want to make) that is 135,416 or 1.3 * 10^5 cells. This is within the range of cells recommended to seed the plate
- I decided to to 2 12 well plates with 1.5mL of cells in each, which means I require 36mL of diluted cells  
- Added 31mL of 10% FBS Schneider's medium to the 5mL of cells
- Aliquoted 1.5mL of diluted cells to every well in 2 12 well plates

**20221012 Transfection**
- I concentrated the 2 plasmids to 1ug/ul before use with bead cleaning:
  - pCS2 1 was 370ng/ul in 124ul, 45,880 total ng, so I resuspended the DNA in 45ul
  - pAc5 1 was 167ng/ul in 124ul, 20,708 total ng, so I resuspended the DNA in 20ul
- The goal was to add 1ug of plasmid DNA for each transfection
- Plate layout for pAc5:
![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/20221012-pAc5-transfection-S2-plate-layout.png)
- Plate layout for pCS2:
![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/20221012-pCS2-transfection-S2-plate-layout.png)
- Every experimental condition was replicated at least twice
- I then made up separate reagent tubes for each experimental treatment based on the instructions for the reagents. All of this was done at room temperature in the cell culture hood. Transfection reagents were thawed at room temp, vortexed, and spun down before use
- Plate 1 pAc5 reagent tubes:
  - Tube 1:
    - 200ul Schnieder's medium
  - Tube 2:
    - 200ul Schneider's medium
    - 2ul concentrated pAc5
  - Tube 3:
    - 200ul Schneider's medium
    - 4ul insect reagent
  - Tube 4:
    - 200ul Schneider's medium
    - 6ul 2020 reagent
  - Tube 5:
    - 200ul Schneider's medium
    - 2ul concentrated pAc5
    - 4ul insect reagent
  - Tube 6:
    - 200ul Schneider's medium
    - 2ul concentrated pAc5
    - 6ul 2020 reagent
- Each tube was pipette mixed gently
- The tubes incubated 30 minutes to allow the plasmid/lipid complexes to form
  - Liquid with the reagents became opaque, this is normal
- Plate 2 pCS2 reagent tubes:
  - Tube 7:
    - 200ul Schnieder's medium
  - Tube 8:
    - 200ul Schneider's medium
    - 2ul concentrated pACS2
  - Tube 9:
    - 200ul Schneider's medium
    - 4ul insect reagent
  - Tube 10:
    - 200ul Schneider's medium
    - 6ul 2020 reagent
  - Tube 11:
    - 200ul Schneider's medium
    - 2ul concentrated pCS2
    - 4ul insect reagent
  - Tube 12:
    - 200ul Schneider's medium
    - 2ul concentrated pCS2
    - 6ul 2020 reagent
- Each tube was pipette mixed gently
- The tubes incubated 30 minutes to allow the plasmid/lipid complexes to form
  - Liquid with the reagents became opaque, this is normal
- Then the appropriate amount of reagent was added to the appropriate tube in a drop-wise fashion all over the well:
  - Plate 1 pAc5:
    - Well A1: 100ul tube 1
    - Well A2: 101ul tube 2
    - Well A3: 100ul tube 1
    - Well A4: 101ul tube 2
    - Well B1: 102ul tube 3
    - Well B2: 103ul tube 4
    - Well B3: 102ul tube 3
    - Well B4: 103ul tube 4
    - Well C1: 103ul tube 5
    - Well C2: 104ul tube 6
    - Well C3: 103ul tube 5
    - Well C4: 104ul tube 6
  - Plate 2 pACS2
    - Well A1: 100ul tube 7
    - Well A2: 101ul tube 8
    - Well A3: 100ul tube 7
    - Well A4: 101ul tube 8
    - Well B1: 102ul tube 9
    - Well B2: 103ul tube 10
    - Well B3: 102ul tube 9
    - Well B4: 103ul tube 10
    - Well C1: 103ul tube 11
    - Well C2: 104ul tube 12
    - Well C3: 103ul tube 11
    - Well C4: 104ul tube 12
- Plates were gently rocked back and forth and put in the 23 degree incubator for 24 hours then checked. The plate was always kept in the incubator between checks

**20221013 Checking transfections**
- I used the GFP scope in the little fly room, you have to turn off the room lights and use a separate light source to get the focus right
- All reagent + pAc5 wells showed GFP glowing cells
- No wells for pCS2 showed any GFP
- An image was taken on day 1 of well A1 (insect reagent) as well as on day 8. The 2020 reagent well looked the same
- Images can be found [here](https://docs.google.com/presentation/d/1iXbjwSPoyk_UA45TdKA3XzudSulsi9ZcEZV5mjo9KoI/edit#slide=id.p) however I did not do a good job of imaging these plates because I only took 2 pictures
