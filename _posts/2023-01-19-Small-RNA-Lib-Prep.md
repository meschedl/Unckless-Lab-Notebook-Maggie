---
layout: post
title: Small RNA Library Prep of 6 Samples for Wen-Juan
---


### NEBNext Multiplex Small RNA Library Prep On Six Small RNA Samples For Wen-Juan

Using the [NEBNext Multiplex Small RNA Library Prep](https://www.neb.com/products/e7300-nebnext-multiplex-small-rna-library-prep-set-for-illumina-set-1#Product%20Information) on six testes samples of sex ratio and standard _D. affinis_ for Wen-Juan. Sample information can be found [here](https://docs.google.com/spreadsheets/d/1g7VCNogjnWyEvJDrV9c9ze8MJJcm_1nR6c5tgExZxSY/edit#gid=0). 

**20231019 Set Up and Overnight 3' Adapter Ligation**

- Cleaned benchtop, pipettes, tube racks, ice buckets, both mini-centrifuges, and pipette tip boxes with 70% ethanol and then RNase Away
- Made sure to wear gloves at all times and wiped gloves with RNase Away whenever touching something that had not been wiped previously 
- Wore a lab coat 
- Got new containers of filter tips so they were fresh, a new bag of 1.5mL tubes, and a new bag of strip tubes 
- Programed the PCR machine for each incubation an process needed:
- SMRNALG3 - 3' SR Adapter Ligation program - 20ul volume
    - Hold 70C
    - 2 min 70C
    - Hold 16C
    - 18 hours 16C
- SMRNARTP - Hybridize Reverse Transcription Primer - 26ul volume
    - 5 min 75C
    - 15 min 37C
    - 15 min 25C
    - Hold 4C
- SMRNALG5 - Ligate the 5' SR Adapter - 30ul volume
    - Hold 70C
    - 2 min 70C
    - Hold 4 C
    - Hold 25C
    - 1 hour 25C
- SMRNART - Reverse Transcription - 40ul volume
    - Hold 50C
    - 1 hour 50C
- SMRNAPCR - PCR Amplification - 100ul volume 
    - 30 sec 94C 
    - **15 sec 94C**
    - **30 sec 62C**
    - **15 sec 70C**
    - 5 min 70C
    - Hold 4C
    - _Bold sections are cycled 18 times_
- Thawed 3' SR Adapter, 3' Ligation Reaction Buffer, and 3' Ligation Enzyme mix on ice, flick mixed, and spun down
    - _Note: the ligation buffer had a white precipitate in it, maybe DTT. Note that it did not smell bad. I am not sure if this is an issue or not, I know that DNA ligase buffer is supposed to smell bad_
- Thawed RNA samples on ice
    - These were in the -80 on the 2nd from the top shelf, 2nd rack on the left, on the 2nd row in the rack, a box with 6 samples 
- Samples:

|Tube #|Sample ID|
|---|---|
|1|SR1|
|2|SR2|
|3|SR3|
|4|D1|
|5|D2|
|6|D3|

- Started the SMRNALG3 program to get it to the 70C hold 
- Diluted the 3’ adapter 1:2 by taking 3.3ul of adapter and adding 3.3ul of molecular grade water. Pipette mixed and kept on ice
- Added 1ul of the diluted 3 ́ SR Adaptor for Illumina to each sample strip tube and pipette mixed and spun down
- Placed tubes in the thermocycler and pressed skip to the 2 min 70C, watched for 2 min then took them out after the 2 min at 70 is finished
- Placed tubes on ice immediately
- Prepared the ligation mix on ice, pipette mixed, and spun down:
    - 10ul 3 ́ Ligation Reaction Buffer * 6.6 = 66ul
    - 3ul 3 ́ Ligation Enzyme Mix * 6.6 = 19.8ul
- Added 13ul of ligation mix to each sample tube on ice, pipette mixed, and spun down 
- Placed tubes in thermocycler and started the 1080 min 16 C section 
    - This was at 4:06pm, being ready at ~10am tomorrow

**20230120 Finish Library Prep To PCR Cleanup Step**

- Cleaned benchtop, pipettes, tube racks, ice buckets, both mini-centrifuges, and pipette tip boxes with 70% ethanol and then RNase Away
- Made sure to wear gloves at all times and wiped gloves with RNase Away whenever touching something that had not been wiped previously 
- Wore a lab coat 

**Hybridize the Reverse Transcription Primer**
- Thawed SR RT Primer for Illumina on ice, flick mixed, and spun down 
- Diluted the SR RT 1:2 by taking 3.3ul of primer and adding 3.3ul of molecular grade water. Pipette mixed and kept on ice
- Made primer master mix on ice, pipette mixed, and spun down:
    - 4.5ul nuclease free water * 6.6 = 29.7ul
    - 1ul diluted SR RT Primer for Illumina * 6.6 = 6.6ul 
- Added 5.5ul primer mix to the samples from the ligation step, pipette mixed, and spun down 
    - Pipette mixed with 20ul 5X 
- Added samples to the thermocycler and started the RT primer hybridization program SMRNARTP
- Placed tubes on ice afterwards

**Ligate 5' SR Adapter**
- Thawed 5’ ST adapter, 5’ Ligation Reaction Buffer (10X), and 5’ Ligation Reaction Mix, flicked to mix and spun down 
    - _The 5' Adapter seemed like lopholized oligos, so it was spun down for 1 minute_
    - _Note that the 5' Ligation Reaction Buffer did not have a precipitate_
- Resuspended 5 ́ SR adaptor in 120 μl of nuclease free water
    - _Let sit for 1 minute after adding water, then vortexed for 30 seconds then spun down_
- Diluted the 5 ́ SR adaptor 1:2 by taking 4.5ul of adapter and adding 4.5ul of molecular grade water. Pipette mixed and kept on ice
- Aliquoted 1.2ul of diluted 5 ́ SR adaptor into 6 strip tubes 
- Aliquoted the rest of the adapter into 11ul strip tube aliquots (for 10 samples at a time), this made 10 full size aliquots and 1 half size aliquot 
- Started the SMRNALG5 program to get to the 70C hold
- Put the 1.2ul aliquots of diluted 5 ́ SR adaptor in the thermocycler and skipped so it would go to 2 min at 70C 
- Took denatured adapters out and placed on ice at the 4C hold, continued the program to 25C and kept on hold until later
- Added 1ul 5 ́ Ligation Reaction Buffer (10X) to each of the sample tubes from the ligation step
- Added 2.5ul 5 ́ Ligation Enzyme Mix to each of the sample tubes from the ligation step
- Added 1ul of the diluted denatured adapters to each of the sample tubes from the ligation step
    - _There was just enough liquid in each tube for this_
- Pipette mixed and spun down samples 
    - Pipetted with 20ul 10X
- Placed sample tubes in the thermocycler and continued the program so that it went for 1 hour at 25C
- Placed tubes on ice afterwards 

**Reverse Transcription**
- With ~30 minutes left in the program, thawed First Strand Synthesis Reaction, Murine RNase Inhibitor, and ProtoScript II Reverse Transcriptase on ice, flicked to mix, and spun down 
    - _Note, the reaction buffer was opaque when thawing. Then when it was spun down, a white precipitate pelleted. I flicked the tube to mix it again and did a very quick spin down to keep the particles suspended_
- Started the SMRNART program so it got to the 50C hold
- Made reverse transcription master mix on ice, flicked to mix and spun down: 
    - 8ul First Strand Synthesis Reaction * 6.6 = 52.8ul
    - 1ul Murine RNase Inhibitor * 6.6 = 6.6ul
    - 1ul ProtoScript II Reverse Transcriptase * 6.6 = 6.6ul 
- Added 10ul of reverse transcription mix to each sample tube and pipette mixed and spun down
    - _Pipette mixed with 30ul 10X_
- Added sample tubes to the thermocycler and skipeed the step so it would go to 50C for 1 hour 
- Placed tubes on ice afterwards 

**PCR Amplification**
- With ~15 minutes left in the program, thawed LongAmp Taq 2X Master Mix, SR Primer for Illumina, and Index primers 2, 4, 5, 6, 7, and 12 on ice, flicked to mix, and spun down 
- Made PCR master mix on ice, flick mixed and spun down:
    - 50ul LongAmp Taq 2X Master Mix *6.6 = 330ul 
    - 2.5ul SR Primer for Illumina * 6.6 = 16.5ul 
    - 5ul nuclease free water * 6.6 = 33ul
- Added 57.5ul master mix to each sample tube out of the thermocycler on ice 
- Added 2.5ul of the appropriate index to the appropriate sample tube:

|Sample|index|volume (ul)|
|---|---|---|
|1|2|2.5|
|2|4|2.5|
|3|5|2.5|
|4|6|2.5|
|5|7|2.5|
|6|12|2.5|

- Pipette mixed tubes and spun down
- Placed  tubes in thermocycler SMRNAPCR program 
    - _Program takes ~40 minutes_
- Placed tubes on ice afterwards 
    - _Note, tubes stat 1.5 hrs on ice before starting the cleanup so I could have access to the faster centrifuge_

**Monarch PCR and DNA Clean Up Kit**
- Prepared buffers as this is a new kit:
    - Added 14 ml of 100% isopropanol to the DNA Cleanup Binding Buffer
    - Added 20 ml of ethanol to the Monarch DNA Wash Buffer
- Total volume out of the PCR is 100ul, and the protocol says to use the 700:1 binding buffer to sample ratio
- Transferred the PCR reaction from each sample to new 1.5mL tubes 
- Added 700ul of DNA Cleanup Binding Buffer to each sample tube 
- Pipette mixed to mix the sample 
    - _Note that the "low retention" tips we have are not really that low retention and some sample was lost in the tips_
- Prepared a spin column for each sample 
- Added the 800ul of sample to the corresponding spin column 
- Centrifuged the spin columns at 16,000 rcf for 1 minute 
- Kept supernatant from this just in case in backup tubes
- Added 200ul DNA Wash Buffer to each column 
- Centrifuged the columns at 16,000 rcf for 1 minute 
- Discarded the supernatant 
- Added another 200ul DNA Wash Buffer to each column
- Centrifuged the columns at 16,000 rcf for 1 minute
- Discarded the supernatant 
- Centrifuged the column “dry” for 1 minute at 16,000 rcf 
- Placed spin column in a new 1.5mL tube for each sample 
- Added 32ul of DNA Elution Buffer (TE buffer) to each column and let sit for 1 minute
- Centrifuged columns for 1 minute at 16,000 rcf 
- Transferred 2ul of library to new strip tubes for TapeStation Analysis
- Froze the 2ul aliquots, the purified libraries, and the saved supernatant at -20C 

**20230120 D1000 TapeStation**
- Brought the 2ul aliquots down to the Genome Sequencing Core 
- Took out the D1000 sample buffer and D1000 screen tape from their fridge to equilibrate to room temperature
    - _Note, the GSC does not purchase ladders for the D1000, they only use electronic ladders_ 
- Once the reagents were at room temp, vortexed and spun down the sample buffer
- Got the TapeStation tube strip and strip caps 
- Added 3ul of sample buffer to each of 6 tubes in the TapeStation tubes 
- Added 1ul of library to each tube with sample buffer. I went in order of 1-6 
- Vortexed tubes for 1 minute
- Spun down tube 
- Logged into computer and turned on TapeStation, opened software 
- Loaded sample tubes, took of the caps gently, and loaded in the screen tape 
- Selected 6 wells and named them, right clicking the "ladder" position and changing it to electronic ladder so I could put a sample in the first position 
- Closed the lid and pressed start
- Machine ran for ~5 minutes 
- A folder is created for the date, exported the results as a pdf and saved it to that folder. Then renamed the folder by adding initials and Unckless after it 
- Took out tubes, pipette tips, and screentape from the machine, put the screentape back in the fridge as there were spots left, and shut down the machine 
- Saved pdf on flashdrive 
- Signed out on the clipboard how many samples I did for billing purposes 
- Re-froze the samples, there is ~1ul left in each tube 

Libraries seemed to have worked for all samples, except sample 1 is very low in concentration. See results [here](https://drive.google.com/file/d/1SVNWxZVnsq9F_xevtSYTbD5kbs3Okbk-/view?usp=share_link)

Concentrations of the ~155bp peak 
- Sample 1 - 0.712 ng/ul
- Sample 2 - 3.37ng/ul
- Sample 3 - 6.67ng/ul
- Sample 4 - 4.01ng/ul
- Sample 5 - 5.02ng/ul
- Sample 6 - 4.07ng/ul 

For all samples but 1 the total yield is ~100-200ng cDNA library. Molarities for these peaks are pretty high because the bp is small. It would be good to know what the requirements are for sequencing. Hard to know how much I will get out of these from the Blue Pippin. 






