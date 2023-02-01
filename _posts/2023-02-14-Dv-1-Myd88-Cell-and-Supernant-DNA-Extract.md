---
layout: post
title: Dv-1 and Myd88 Cell and Supernatant DNA Extraction 
---

## Extracting DNA from Dv-1 and Myd88 Cells and Supernatant from the DiNV Infection Experiment  

For flask samples, there is very little liquid in them. I added 1mL of 1X PBS to each flask to make it a usable sample. I also did a Lambda DNA spike for the supernatant samples because they likely contain low amounts of DNA. I also decided to do an extraction replicate for each sample because there was so much sample.  
I also did a modified extraction procedure based off of Kent's viral DNA extraction protocol and the [single fly extraction protocol](https://github.com/meschedl/Unckless_Lab_Resources/blob/main/protocols/single_fly_DNA_extraction.md). Basically I doubled Kent's volumes and added in heated incubation steps. 

The sampling datasheet looks like this:

| Sample_ID | Cell_type | Day | infection_status | type        | flask_replicate | extraction_replicate | lambda_spike | PBS_added |
|-----------|-----------|-----|------------------|-------------|-----------------|----------------------|--------------|-----------|
| 1         | Dv-1      | 0   | yes              | supernatant | 1               |                      | yes          | NA        |
| 1.1       | Dv-1      | 0   | yes              | supernatant |                 | yes                  | yes          | NA        |
| 2         | Dv-1      | 0   | yes              | cells       | 1               |                      | NA           | 1mL       |
| 2.1       | Dv-1      | 0   | yes              | cells       |                 | yes                  | NA           | 1mL       |
| 3         | Myd88     | 0   | yes              | supernatant | 1               |                      | yes          | NA        |
| 3.1       | Myd88     | 0   | yes              | supernatant |                 | yes                  | yes          | NA        |
| 4         | Myd88     | 0   | yes              | cells       | 1               |                      | NA           | 1mL       |
| 4.1       | Myd88     | 0   | yes              | cells       |                 | yes                  | NA           | 1mL       |
| 5         | Dv-1      | 5   | yes              | supernatant | 1               |                      | yes          | NA        |
| 5.1       | Dv-1      | 5   | yes              | supernatant |                 | yes                  | yes          | NA        |
| 6         | Dv-1      | 5   | yes              | cells       | 1               |                      | NA           | 1mL       |
| 6.1       | Dv-1      | 5   | yes              | cells       |                 | yes                  | NA           | 1mL       |
| 7         | Dv-1      | 5   | yes              | supernatant | 2               |                      | yes          | NA        |
| 7.1       | Dv-1      | 5   | yes              | supernatant |                 | yes                  | yes          | NA        |
| 8         | Dv-1      | 5   | yes              | cells       | 2               |                      | NA           | 1mL       |
| 8.1       | Dv-1      | 5   | yes              | cells       |                 | yes                  | NA           | 1mL       |
| 9         | Dv-1      | 5   | no               | supernatant | 1               |                      | yes          | NA        |
| 9.1       | Dv-1      | 5   | no               | supernatant |                 | yes                  | yes          | NA        |
| 10        | Dv-1      | 5   | no               | cells       | 1               |                      | NA           | 1mL       |
| 10.1      | Dv-1      | 5   | no               | cells       |                 | yes                  | NA           | 1mL       |
| 11        | Myd88     | 5   | yes              | supernatant | 1               |                      | yes          | NA        |
| 11.1      | Myd88     | 5   | yes              | supernatant |                 | yes                  | yes          | NA        |
| 12        | Myd88     | 5   | yes              | cells       | 1               |                      | NA           | 1mL       |
| 12.1      | Myd88     | 5   | yes              | cells       |                 | yes                  | NA           | 1mL       |
| 13        | Myd88     | 5   | yes              | supernatant | 2               |                      | yes          | NA        |
| 13.1      | Myd88     | 5   | yes              | supernatant |                 | yes                  | yes          | NA        |
| 14        | Myd88     | 5   | yes              | cells       | 2               |                      | NA           | 1mL       |
| 14.1      | Myd88     | 5   | yes              | cells       |                 | yes                  | NA           | 1mL       |
| 15        | Myd88     | 5   | no               | supernatant | 1               |                      | yes          | NA        |
| 15.1      | Myd88     | 5   | no               | supernatant |                 | yes                  | yes          | NA        |
| 16        | Myd88     | 5   | no               | cells       | 1               |                      | NA           | 1mL       |
| 16.1      | Myd88     | 5   | no               | cells       |                 | yes                  | NA           | 1mL       |

**Preparing Samples**
- All supernatant tubes and flasks were thawed on ice 
- The stock Lambda DNA (from Kent) was thawed on ice 
- Lambda DNA was vortexed and spun down 
- A dilution of 1:1000 was done for the Lambda: 1ul in 1mL of nuclease fre water. This was vortexed, spun down, and kept on ice 
- Once thawed, each flask had 1mL of 1X PBS added to it, swished back and forth, and sucked up and added to a 1.5mL tube for easy access
- I also made 1mL aliquots of supernatant fluid for each sample in 1.5mL tubes for easy access
- For each sample, I made 2 tubes for extraction. They were labeled 1-16.1 as in the above table
- For each sample, I pipetted 100ul of sample into 2 tubes each (one is the extraction replicate)
    - Note here that potentially I was not consistent with pipetting a similar sample to each replicate tube 
- For all the supernatant samples and their extraction replicates, I needed to add Lambda DNA as an extraction control. Kent says he uses 1ul of 1:1000 diluted DNA, but because I decided to double his volumes I used 2ul 
- Added 2ul of diluted Lambda DNA to tubes 1, 1.1, 3, 3.1, 5, 5.1, 7, 7.1, 9, 9.1, 11, 11.1, 13, 13.1, 15, and 15.1 

**DNA Extraction**
- Using the Qiagen Puregene Blood and Tissue reagents/method
- Turned on the heat blocks to 65C and 37C and chilled the cell lysis solution on ice until cloudy
- Added 500ul of chilled cell lysis solution to each tube and pipette mixed 10X
- Incubated tubes in the heat block at 65C for 10 minutes 
- Diluted RNase A 1:100, 2ul in 198ul of nuclease free water
- Let tubes come to room temp after the heat block 
- Added 6ul of RNase A to each tube 
- Flipped the tubes 25X to mix them 
- Incubated tubes at 37C for 30 minutes in the heat block 
- Let tubes come to room temp after incubation 
- Added 200ul of protein precipitation solution to each tube 
- Vortexed tubes ~10 sec 
- Placed tubes on ice for 5 min 
- Centrifuged tubes 16,300g for 3 minutes (had to be done in 2 batches)
- Made new tubes with 600ul of fresh 100% ethanol with final tube labels 
- Transferred the supernatant from the centrifugation (~800ul) to the new tubes with the isopropanol 
- Inverted the tubes 50X 
- Centrifuged the tubes 16,300g for 5 minutes (2 batches)
- Discarded the supernatant 
    - Note that I didn't see a pellet in any of the samples 
- Added 600ul of fresh 70% ethanol to each tube 
- Inverted 3X 
- Centrifuged tubes 16,300g 5 min 
- Discarded supernatant 
- Let tubes air dry upside down on a kim wipe for ~1 hour 
- Resuspended DNA in 20ul of DNA hydration solution and let tubes sit overnight 

**Qubit of extracted samples 20230125**
- I have 32 samples, plus 2 standards, plus 3 for error
    - N= 37 
- 37 * 199 = 7,363ul buffer 
- 37ul Quant IT reagent 
- Mixed quantification buffer
- Prepared sample and standard Qubit tubes 
- Added 190ul Quant buffer to the standard tubes 
- Added 199ul Quant buffer to the sample tubes 
- Added 10ul standards to the standard tubes 
- Added 1ul sample to the sample tubes 
- Vortexed and spun down tubes 
- Let tubes sit ~2 min 
- Quantified samples:

| Sample_ID | Cell_type | Day | infection_status | type        | flask_replicate | extraction_replicate | lambda_spike | PBS_added | extraction_date | qubit_quantity |
|-----------|-----------|-----|------------------|-------------|-----------------|----------------------|--------------|-----------|-----------------|----------------|
| 1         | Dv-1      | 0   | yes              | supernatant | 1               |                      | yes          | NA        | 20230124        | too low        |
| 1.1       | Dv-1      | 0   | yes              | supernatant |                 | yes                  | yes          | NA        | 20230124        | 2.67           |
| 2         | Dv-1      | 0   | yes              | cells       | 1               |                      | NA           | 1mL       | 20230124        | too low        |
| 2.1       | Dv-1      | 0   | yes              | cells       |                 | yes                  | NA           | 1mL       | 20230124        | too low        |
| 3         | Myd88     | 0   | yes              | supernatant | 1               |                      | yes          | NA        | 20230124        | too low        |
| 3.1       | Myd88     | 0   | yes              | supernatant |                 | yes                  | yes          | NA        | 20230124        | too low        |
| 4         | Myd88     | 0   | yes              | cells       | 1               |                      | NA           | 1mL       | 20230124        | 5.16           |
| 4.1       | Myd88     | 0   | yes              | cells       |                 | yes                  | NA           | 1mL       | 20230124        | 4.18           |
| 5         | Dv-1      | 5   | yes              | supernatant | 1               |                      | yes          | NA        | 20230124        | too low        |
| 5.1       | Dv-1      | 5   | yes              | supernatant |                 | yes                  | yes          | NA        | 20230124        | 5.05           |
| 6         | Dv-1      | 5   | yes              | cells       | 1               |                      | NA           | 1mL       | 20230124        | 48.1           |
| 6.1       | Dv-1      | 5   | yes              | cells       |                 | yes                  | NA           | 1mL       | 20230124        | 7.3            |
| 7         | Dv-1      | 5   | yes              | supernatant | 2               |                      | yes          | NA        | 20230124        | 13.2           |
| 7.1       | Dv-1      | 5   | yes              | supernatant |                 | yes                  | yes          | NA        | 20230124        | 13.7           |
| 8         | Dv-1      | 5   | yes              | cells       | 2               |                      | NA           | 1mL       | 20230124        | 44.3           |
| 8.1       | Dv-1      | 5   | yes              | cells       |                 | yes                  | NA           | 1mL       | 20230124        | 12.9           |
| 9         | Dv-1      | 5   | no               | supernatant | 1               |                      | yes          | NA        | 20230124        | 10.6           |
| 9.1       | Dv-1      | 5   | no               | supernatant |                 | yes                  | yes          | NA        | 20230124        | 12.1           |
| 10        | Dv-1      | 5   | no               | cells       | 1               |                      | NA           | 1mL       | 20230124        | 45.6           |
| 10.1      | Dv-1      | 5   | no               | cells       |                 | yes                  | NA           | 1mL       | 20230124        | 16.9           |
| 11        | Myd88     | 5   | yes              | supernatant | 1               |                      | yes          | NA        | 20230124        | 11.2           |
| 11.1      | Myd88     | 5   | yes              | supernatant |                 | yes                  | yes          | NA        | 20230124        | 11.5           |
| 12        | Myd88     | 5   | yes              | cells       | 1               |                      | NA           | 1mL       | 20230124        | 20.1           |
| 12.1      | Myd88     | 5   | yes              | cells       |                 | yes                  | NA           | 1mL       | 20230124        | 20.1           |
| 13        | Myd88     | 5   | yes              | supernatant | 2               |                      | yes          | NA        | 20230124        | 14.5           |
| 13.1      | Myd88     | 5   | yes              | supernatant |                 | yes                  | yes          | NA        | 20230124        | 14.2           |
| 14        | Myd88     | 5   | yes              | cells       | 2               |                      | NA           | 1mL       | 20230124        | 18.3           |
| 14.1      | Myd88     | 5   | yes              | cells       |                 | yes                  | NA           | 1mL       | 20230124        | 16.4           |
| 15        | Myd88     | 5   | no               | supernatant | 1               |                      | yes          | NA        | 20230124        | 14.2           |
| 15.1      | Myd88     | 5   | no               | supernatant |                 | yes                  | yes          | NA        | 20230124        | 12.8           |
| 16        | Myd88     | 5   | no               | cells       | 1               |                      | NA           | 1mL       | 20230124        | 14             |
| 16.1      | Myd88     | 5   | no               | cells       |                 | yes                  | NA           | 1mL       | 20230124        | 13.9           |


Some samples are too low, but could be just below the detection threshold of 2ng/ul. There is also considerable variability in extraction output for some replicates, while others are very consistent. It could be that the samples I gave the replicate had settled and had less cells or sample when I thought I was giving them the same. Or I lost pellets places. 

Samples were frozen at -20 after this. 






