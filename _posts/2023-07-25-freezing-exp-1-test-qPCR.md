---
layout: post
title: Test qPCR for Freezing Experiment 1
---

## Doing qPCR for Viral Titre on a Test Subset of Samples From Freezing Experiment 1

The freezing experiments consist of infecting flies with DiNV, and freezing them on day 0, 3, 5, and 10. From the [PCR data](https://meschedl.github.io/Unckless-Lab-Notebook-Maggie/2023/06/20/freezing-exp-1-PCRs.html), a lot of samples ended up having what looks like contamination in some way, where the sterile poke flies have virus PCR products. Even when looking at the [band strength](https://meschedl.github.io/Unckless-Lab-Notebook-Maggie/2023/06/20/freezing-exp-1-PCRs.html) of those PCRs, some seem pretty strong. However, it is hard to tell exactly what is going on with conventional PCR, so I chose 3 samples from each treatment from each day (24 total) to do qPCR on. Those samples are chosen in the [band strength](https://meschedl.github.io/Unckless-Lab-Notebook-Maggie/2023/06/20/freezing-exp-1-PCRs.html) notebook. 

Before qPCR, all samples were Qubited and diluted to a 1ng/ul concentration using DNA hydration solution. The [Qubit protocol](https://docs.google.com/document/d/1ZCz0SBof6LHE3P_LbftawFyexl8iCECUlvjIcauPYwY/edit) was used, and all samples were thawed and kept on ice during. 

| sample_ID | qubit | vol DNA needed | vol hydration solution needed for 1ng/ul |
|-----------|-------|-----------------|------------------------------------------|
| 1         | 31.3  | 3               | 90.9                                     |
| 9         | 109   | 3               | 324                                      |
| 10        | 45.8  | 3               | 134.4                                    |
| 23        | 30.6  | 3               | 88.8                                     |
| 30        | 44.7  | 3               | 131.1                                    |
| 16        | 29.5  | 3               | 85.5                                     |
| 37        | 123   | 3               | 366                                      |
| 32        | 40.3  | 3               | 117.9                                    |
| 38        | 55.5  | 3               | 163.5                                    |
| 42        | 18.3  | 3               | 51.9                                     |
| 48        | 70.1  | 3               | 207.3                                    |
| 64        | 67.6  | 3               | 199.8                                    |
| 84        | 38.4  | 3               | 112.2                                    |
| 87        | 102   | 3               | 303                                      |
| 89        | 103   | 3               | 306                                      |
| 94        | 33.9  | 3               | 98.7                                     |
| 98        | 43.8  | 3               | 128.4                                    |
| 117       | 51.3  | 3               | 150.9                                    |
| 142       | 30.9  | 3               | 89.7                                     |
| 147       | 65.4  | 3               | 193.2                                    |
| 143       | 37.6  | 3               | 109.8                                    |
| 150       | 50    | 3               | 147                                      |
| 158       | 37    | 3               | 108                                      |
| 173       | 44.3  | 3               | 129.9                                    |


Here is the qPCR layout:

![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/20230725-qPCR.png)

- Samples and reagents were thawed on ice, vortexed, and spun down before use 
- There were 72 individual wells for each primer, 3 were added on for pipetting error
- 115 master mix:
    - 5ul Sso supermix * 75 = 375ul 
    - 0.5ul 115 F primer * 75 = 37.5ul 
    - 0.5ul 115 R primer * 75 = 37.5ul 
    - 3ul nuclease free water * 75 = 225ul 
- The master mix was made on ice, vortexed, and spun down 
- TPI master mix: 
    - 5ul Sso supermix * 75 = 375ul 
    - 0.5ul TPI F primer * 75 = 37.5ul 
    - 0.5ul TPI R primer * 75 = 37.5ul 
    - 3ul nuclease free water * 75 = 225ul  
- The master mix was made on ice, vortexed, and spun down 
- I used the qPCR specific plates and seals
- 9ul of the appropriate master mix was added to the planned well (see layout above)
- 1ul of DNA was added to the planned well (see table above)
- Each well was pipette mixed with 5ul using a multichannel
- The plate was sealed and centrifuged for 2 minutes at 3,000g 
- The plate was put in the qPCR machine:
    - Used program CFX manager 
    - Selected user-defined protocol, existing protocol, and KMM folder 
    - Selected the p47 program 
    - Used the machine buttons to open and close the lid 
    - Started the program 
- Data from the qPCR machine can be found [here](https://drive.google.com/drive/folders/1emjDkMMl5RCYLjHYIl_YyGZFyMDEdB5g)
- And analysis of the Cq results can be found [here](https://github.com/meschedl/Unckless_Lab_Resources/blob/main/qPCR_analysis/20230725-freezing-exp-1/20230725-freezing-exp-1-qPCR-analysis.md)

