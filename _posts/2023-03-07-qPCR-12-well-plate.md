---
layout: post
title: qPCR of Myd88 and Dv-1 Cell 12-Well Infection Experiment
---

## Cell and Supernatant qPCR of Myd88 and Dv-1 Cell Samples from 12-Well Plate Infection Experiment

Using samples from [this extraction](https://meschedl.github.io/Unckless-Lab-Notebook-Maggie/2023/02/14/dna-extracts-02-14-23.html) from the [Feb. 8th infection experiment](https://meschedl.github.io/Unckless-Lab-Notebook-Maggie/2023/02/08/infecting-Myd88-Dv1-cells-20230208.html).

I will not be doing qPCR on every sample from this experiment. To cut down on what should be done, not every day 0 sample will be assayed. The table below shows which samples were used for the experiment, what the treatment conditions were, and what the Qubit concentrations of the DNA extracts are. I also added in the original inoculation fluid so that could be assayed (40ul sample). The spreadsheet with this information can be found [here](https://docs.google.com/spreadsheets/d/1pjKTyKVMAUNSAZKTo0KQ4OoNmmcuTXk7PK1jFw5Yy9w/edit#gid=0).

| extraction_number    | plate_day | infection | cell_type  | sample_type | qubit_concentration |
|----------------------|-----------|-----------|------------|-------------|---------------------|
| 1                    | 0         | yes       | Dv1        | supernatant | too low             |
| 2                    | 0         | yes       | Myd88      | supernatant | too low             |
| 3                    | 0         | no        | Dv1        | supernatant | too low             |
| 4                    | 0         | no        | Myd88      | supernatant | too low             |
| 13                   | 0         | yes       | Dv1        | cells       | too low             |
| 14                   | 0         | yes       | Myd88      | cells       | too low             |
| 15                   | 0         | no        | Dv1        | cells       | too low             |
| 16                   | 0         | no        | Myd88      | cells       | too low             |
| 25                   | 5         | yes       | Dv1        | supernatant | too low             |
| 26                   | 5         | yes       | Myd88      | supernatant | 3.4                 |
| 27                   | 5         | no        | Dv1        | supernatant | 3.55                |
| 28                   | 5         | no        | Myd88      | supernatant | 2                   |
| 29                   | 5         | yes       | Dv1        | supernatant | too low             |
| 30                   | 5         | yes       | Myd88      | supernatant | 3.22                |
| 31                   | 5         | no        | Dv1        | supernatant | 3.43                |
| 32                   | 5         | no        | Myd88      | supernatant | 5.78                |
| 33                   | 5         | yes       | Dv1        | supernatant | 6.7                 |
| 34                   | 5         | yes       | Myd88      | supernatant | 6.67                |
| 40ul original sample | NA        | NA        | innubila   | supernatant | too low             |
| 36                   | 5         | no        | Myd88      | supernatant | 6.57                |
| 37                   | 5         | yes       | Dv1        | cells       | 7.52                |
| 38                   | 5         | yes       | Myd88      | cells       | 11                  |
| 39                   | 5         | no        | Dv1        | cells       | 6                   |
| 40                   | 5         | no        | Myd88      | cells       | 15.7                |
| 41                   | 5         | yes       | Dv1        | cells       | 9.9                 |
| 42                   | 5         | yes       | Myd88      | cells       | 13.1                |
| 43                   | 5         | no        | Dv1        | cells       | 6.83                |
| 44                   | 5         | no        | Myd88      | cells       | 13.2                |
| 45                   | 5         | yes       | Dv1        | cells       | 9.42                |
| 46                   | 5         | yes       | Myd88      | cells       | 10.1                |
| 47                   | 5         | no        | Dv1        | cells       | 9.47                |
| 48                   | 5         | no        | Myd88      | cells       | 8                   |

### Dilution
- For all the samples that had a readable DNA quant, I wanted to normalize them to 1ng/ul to input into the qPCR
- For the too low samples, I acted like they were are 1ng/ul, but there is no way to tell
- All samples were thawed on ice, vortexed, and spun down before dilution 

| extraction_number    | ul for 1ng/ul in 20 ul  | ul Hydration solution |
|----------------------|-------------------------|-----------------------|
| 1                    | NA                      | NA                    |
| 2                    | NA                      | NA                    |
| 3                    | NA                      | NA                    |
| 4                    | NA                      | NA                    |
| 13                   | NA                      | NA                    |
| 14                   | NA                      | NA                    |
| 15                   | NA                      | NA                    |
| 16                   | NA                      | NA                    |
| 25                   | NA                      | NA                    |
| 26                   | 5.9                     | 14.1                  |
| 27                   | 5.6                     | 14.4                  |
| 28                   | 10.0                    | 10.0                  |
| 29                   | NA                      | NA                    |
| 30                   | 6.2                     | 13.8                  |
| 31                   | 5.8                     | 14.2                  |
| 32                   | 3.5                     | 16.5                  |
| 33                   | 3.0                     | 17.0                  |
| 34                   | 3.0                     | 17.0                  |
| 40ul original sample | NA                      | NA                    |
| 36                   | 3.0                     | 17.0                  |
| 37                   | 2.7                     | 17.3                  |
| 38                   | 1.8                     | 18.2                  |
| 39                   | 3.3                     | 16.7                  |
| 40                   | 1.3                     | 18.7                  |
| 41                   | 2.0                     | 18.0                  |
| 42                   | 1.5                     | 18.5                  |
| 43                   | 2.9                     | 17.1                  |
| 44                   | 1.5                     | 18.5                  |
| 45                   | 2.1                     | 17.9                  |
| 46                   | 2.0                     | 18.0                  |
| 47                   | 2.1                     | 17.9                  |
| 48                   | 2.5                     | 17.5                  |

### Supernatant qPCR
- The first plate would just be the supernatant samples
- Rows A, B, C, and D will get the 115 primer (DiNV)
- Rows E, F, G, and H will get the lambda primer (extraction control)
- All DNA, primers, and Supermix (Sso) were thawed on ice, vortexed, and spun down before use 
- A master mix for each primer was made on ice 
- Each primer has 48 samples, plus 4 for error, ends with 52 = n 
- 115 master mix:
    - 5ul Sso * 52 = 260ul 
    - 0.5ul 115 F * 52 = 26ul 
    - 0.5ul 115 R * 52 = 26ul 
    - 3ul nuclease free water * 52 = 156ul 
- The master mix was vortexed, spun down, and kept on ice
- Lambda master mix:
    - 5ul Sso * 52 = 260ul 
    - 0.5ul Lambda F * 52 = 26ul 
    - 0.5ul Lambda R * 52 = 26ul 
    - 3ul nuclease free water * 52 = 156ul 
- The master mix was vortexed, spun down, and kept on ice
- A qPCR plate and seal were used
- 9ul of each master mix was added to each of the planned wells (see plate layout)
- 1ul of DNA was added to each reaction well, with each sample getting triplicate wells per primer
- Each well was pipette mixed with a multichannel pipette set to 5ul 
- The plate was sealed, and spun down for 3 minutes at 3000rcf 
- The plate was put in the qPCR machine:
    - Used program CFX manager
    - Selected user-defined protocol, exisiting protocol, and KMM folder
    - Selected the p47 program
    - Used the machine buttons to open and close the lid
    - Started the program

|   | 1  | 2  | 3  | 4  | 5  | 6  | 7           | 8           | 9           | 10 | 11 | 12 |        |
|---|----|----|----|----|----|----|-------------|-------------|-------------|----|----|----|--------|
| A | 1  | 1  | 1  | 2  | 2  | 2  | 3           | 3           | 3           | 4  | 4  | 4  |        |
| B | 25 | 25 | 25 | 26 | 26 | 26 | 27          | 27          | 27          | 28 | 28 | 28 | 115    |
| C | 29 | 29 | 29 | 30 | 30 | 30 | 31          | 31          | 31          | 32 | 32 | 32 |        |
| D | 33 | 33 | 33 | 34 | 34 | 34 | 40ul sample | 40ul sample | 40ul sample | 36 | 36 | 36 |        |
| E | 1  | 1  | 1  | 2  | 2  | 2  | 3           | 3           | 3           | 4  | 4  | 4  |        |
| F | 25 | 25 | 25 | 26 | 26 | 26 | 27          | 27          | 27          | 28 | 28 | 28 | lambda |
| G | 29 | 29 | 29 | 30 | 30 | 30 | 31          | 31          | 31          | 32 | 32 | 32 |        |
| H | 33 | 33 | 33 | 34 | 34 | 34 | 40ul sample | 40ul sample | 40ul sample | 36 | 36 | 36 |        |

### Cells qPCR
- The first plate is only the cell samples
- Rows A, B, C, and D will get the 115 primer (DiNV)
- Rows E, F, G, and H 1-6 will get the RPL11 primer (Dv-1) and rows E, F, G, and H 7-12 will get the RP49 primer (melanogaster)
- All DNA, primers, and Supermix (Sso) were thawed on ice, vortexed, and spun down before use 
- A master mix for each primer was made on ice 
- The 115 primer has 48 samples, plus 4 for error, ends with 52 = n 
- 115 master mix:
    - 5ul Sso * 52 = 260ul 
    - 0.5ul 115 F * 52 = 26ul 
    - 0.5ul 115 R * 52 = 26ul 
    - 3ul nuclease free water * 52 = 156ul 
- The master mix was vortexed, spun down, and kept on ice
- The two cell control primers has 24 samples, plus 2 for error, ends with 26 = n
- RPL11 master mix:
    - 5ul Sso * 26 = 130ul 
    - 0.5ul RPL11 F * 26 = 13ul 
    - 0.5ul RPL11 R * 26 = 13ul 
    - 3ul nuclease free water * 26 = 78ul 
- The master mix was vortexed, spun down, and kept on ice
- RP49 master mix:
    - 5ul Sso * 26 = 130ul 
    - 0.5ul RP49 F * 26 = 13ul 
    - 0.5ul RP49 R * 26 = 13ul 
    - 3ul nuclease free water * 26 = 78ul 
- The master mix was vortexed, spun down, and kept on ice
- A qPCR plate and seal were used
- 9ul of each master mix was added to each of the planned wells (see plate layout)
- 1ul of DNA was added to each reaction well, with each sample getting triplicate wells per primer
- Each well was pipette mixed with a multichannel pipette set to 5ul 
- The plate was sealed, and spun down for 3 minutes at 3000rcf 
- The plate was put in the qPCR machine:
    - Used program CFX manager
    - Selected user-defined protocol, exisiting protocol, and KMM folder
    - Selected the p47 program
    - Used the machine buttons to open and close the lid
    - Started the program

|   | 1  | 2  | 3     | 4  | 5  | 6  | 7  | 8  | 9    | 10 | 11 | 12 |     |
|---|----|----|-------|----|----|----|----|----|------|----|----|----|-----|
| A | 13 | 13 | 13    | 14 | 14 | 14 | 15 | 15 | 15   | 16 | 16 | 16 |     |
| B | 37 | 37 | 37    | 38 | 38 | 38 | 39 | 39 | 39   | 40 | 40 | 40 | 115 |
| C | 41 | 41 | 41    | 42 | 42 | 42 | 43 | 43 | 43   | 44 | 44 | 44 |     |
| D | 45 | 45 | 45    | 46 | 46 | 46 | 47 | 47 | 47   | 48 | 48 | 48 |     |
| E | 13 | 13 | 13    | 15 | 15 | 15 | 14 | 14 | 14   | 16 | 16 | 16 |     |
| F | 37 | 37 | 37    | 39 | 39 | 39 | 38 | 38 | 38   | 40 | 40 | 40 |     |
| G | 41 | 41 | 41    | 43 | 43 | 43 | 42 | 42 | 42   | 44 | 44 | 44 |     |
| H | 45 | 45 | 45    | 47 | 47 | 47 | 46 | 46 | 46   | 48 | 48 | 48 |     |
|   |    |    | RPL11 |    |    |    |    |    | RP49 |    |    |    |     |

Data from plate 1 (supernatant) can be found [here]  
Data from plate 2 (cells) can be found [here]  
Analysis of these samples can be found [here]  