---
layout: post
title: p47 Band Strength from Freezing Experiment 1
---

## Analyzing Band Strength in p47 PCRs from Freezing Experiment 1 and Planning Samples to Use for qPCR

Data for this freezing experiment has issues because many of my sterile poke samples came up as virus positive. There is obviously contamination coming into the system somewhere. The thought is that these flies are just getting viral contact, either from the CO2 pad, probe, forceps, or other fly room materials. 

I wanted to look at the brightness of the bands to see if it seems like the sterile poke flies have "less" virus (at least in the early time points). If contact with the virus leads to an infection, then the later days might show more substantial virus. 

Analysis of the band brightness was analyzed in R with [this code](https://github.com/meschedl/Unckless_Lab_Resources/blob/main/PCR_analysis/20230524-freezing-ecperiment-1/20230524-freezing-exp-1-band-analysis.md)

And from those plots, consensus plots were made for males and females:

Males 
![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/male_band_strength_freezing_expir_1.png)

Females
![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/female_band_strength_freezing_exp_1.png)


Looking at this is also confounded by the fact that I did two different cycle numbers for p47. However, for the males on day 0 and day 3, there were no bands that were "strong" intensity (and obviously less for the 30 cycle). For the females there are some "strong"s in day 0 and day 3. 

Still, it would be really good to look at titer level with qPCR for some of these, max 20 samples. 

Samples to do qPCR on:

| sample_ID | CO1_result | tpi_result | p47_result | p47_30_cycle_result | band_strength_35_cycles | band_strength_30_cycles | day_frozen | treatment    | sex    |
|-----------|------------|------------|------------|---------------------|-------------------------|-------------------------|------------|--------------|--------|
| 1         | yes        | yes        | yes        | no                  | mid-strong              | none                    | day0       | sterile poke | male   |
| 9         | yes        | yes        | no         | no                  | none                    | none                    | day0       | sterile poke | female |
| 10        | yes        | yes        | yes        | yes                 | strong                  | weak                    | day0       | sterile poke | female |
| 23        | yes        | yes        | yes        | no                  | weak                    | none                    | day0       | 16Cq DiNV    | female |
| 30        | yes        | yes        | yes        | yes                 | strong                  | mid-weak                | day0       | 16Cq DiNV    | female |
| 16        | yes        | yes        | no         | no                  | none                    | none                    | day0       | 16Cq DiNV    | male   |
| 37        | yes        | yes        | yes        | no                  | weak                    | none                    | day3       | sterile poke | female |
| 32        | yes        | yes        | yes        | yes                 | mid-strong              | weak                    | day3       | sterile poke | male   |
| 38        | yes        | yes        | yes        | yes                 | strong                  | mid-weak                | day3       | sterile poke | female |
| 42        | yes        | yes        | yes        | yes                 | strong                  | strong                  | day3       | 16Cq DiNV    | male   |
| 48        | yes        | yes        | yes        | yes                 | mid-strong              | mid-weak                | day3       | 16Cq DiNV    | male   |
| 64        | yes        | yes        | yes        | no                  | mid-weak                | none                    | day3       | 16Cq DiNV    | female |
| 84        | yes        | yes        | yes        | yes                 | strong                  | mid-weak                | day5       | sterile poke | male   |
| 87        | yes        | yes        | maybe      | no                  | weak                    | none                    | day5       | sterile poke | male   |
| 89        | yes        | yes        | yes        | yes                 | strong                  | mid-strong              | day5       | sterile poke | female |
| 94        | yes        | yes        | yes        | no                  | mid-strong              | none                    | day5       | 16Cq DiNV    | male   |
| 98        | yes        | yes        | yes        | yes                 | strong                  | mid-strong              | day5       | 16Cq DiNV    | male   |
| 117       | yes        | yes        | maybe      | no                  | weak                    | none                    | day5       | 16Cq DiNV    | female |
| 142       | yes        | yes        | yes        | maybe               | mid-strong              | none                    | day10      | sterile poke | male   |
| 147       | yes        | yes        | yes        | no                  | mid-weak                | none                    | day10      | sterile poke | female |
| 143       | yes        | yes        | yes        | yes                 | strong                  | mid-weak                | day10      | sterile poke | male   |
| 150       | no         | no         | yes        | yes                 | strong                  | strong                  | day10      | 16Cq DiNV    | male   |
| 158       | yes        | yes        | yes        | yes                 | strong                  | mid-strong              | day10      | 16Cq DiNV    | male   |
| 173       | yes        | yes        | yes        | yes                 | mid-strong              | weak                    | day10      | 16Cq DiNV    | female |