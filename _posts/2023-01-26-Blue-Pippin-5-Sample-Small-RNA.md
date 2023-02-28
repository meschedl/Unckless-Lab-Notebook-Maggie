---
layout: post
title: Blue Pippin Size Selection on 5 Small RNA Libraries
---

## Doing Blue Pippin Size Selection on 2-6 of Small RNA Libraries for Wen-Juan, TapeStation, and Purification

Only doing half the volume of the libraries (15ul) to try to save it just in case this doesn't go well. Only starting with the best libraries (all but #1) 

**Blue Pippin**
- Using BDQ3010 3% cassettes with internal marker Q3
- Brought Marker Q3 to room temp (stored in 4C), flicked to mix, and spun down 
- Thawed samples on ice 
- Make a new set of strip tubes (5 samples only). Added 15ul of libraries 2, 3, 4, 5, and 6 to their respective new strip tubes
- Added 15ul of DNA elution buffer from the Monarch purification kit to those samples to increase the total volume to 30ul
- Mixed 10ul of Marker Q3 with 30ul of sample, pipette mixed and spun down 
- Brought samples, pipette, tips, and cassettes to the Genome Core
    - Note here I need to bring non-filter tips to the core for this because the filter tips don't fit in the elution wells 
- Programed the Blue Pippin:
    - Protocol editor tab and select the 3% DF Marker Q3 cassette 
    - Set the range to 110-170bp    
        - **note here, I had originally wanted to select 105-160. The Blue Pippin machine tells you what the "target" peak is for the range you input. For the 105-160 range it says the target is 132bp. This seemed really low to me. If I increased it to 110-170, the target peak was 140. I decided to make that the range. This may not have been the right idea.**
    - Set to Use Internal Standards 
    - Saved the protocol as “20230126-UNK-SmRNA-110-170” 
- Calibrate optics on the machine:
    - Put the calibration fixture into the machine and closed the lid 
    - Pressed calibrate 
- Inspected cassette:
    - Are there any cracks or breaks in the agarose? - No
        - But there was a scratch in the buffer well chamber of # 4
    - Are there bubbles in the optical chamber of the agarose? - No
- Prepare cassette:
    - Dislodged bubbles from behind elution wells 
    - Placed cassette in nest making sure the bubbles don’t return 
    - Removed adhesive 
    - Removed all buffer from elution wells, sucked up from multiple orientations 
    - Replaced buffer in elution wells with 40ul of fresh electrophoresis buffer 
    - Sealed elution well with tape strip 
    - Checked buffer level in sample wells, make sure it is flush with the gel. Added additional electrophoresis buffer to the first one because it was really low (I realized later that it was leaking, but it hopefully didn't mess anything up) 
    - Closed lid and performed the continuity test - Pass
- Loading samples:	
    - Re-checked buffer level in sample wells 
    - Removed 40ul of buffer from first sample well - followed liquid level down with pipette tip
    - Pipette mixed the first sample, then loaded it into the first sample well - followed liquid level up with pipette tip 
    - Repeated the above 2 steps for each sample well and sample 
    - Closed lid 
    - Double checked that the correct protocol is loaded and then pressed start 
- Program ran for about 70 minutes, and all markers were visible and all wells eluted sample 
- Removed the entire volume in the elution wells and placed in strip tubes per sample. This was about 40ul 

**High Sensitivity D1000 TapeStation**
-  Took out the High Sensitivity D1000 sample buffer and D1000 screen tape from their fridge to equilibrate to room temperature
    - _Note, the GSC does not purchase ladders for the HS D1000 as well, they only use electronic ladders_ 
- Once the reagents were at room temp, vortexed and spun down the sample buffer
- Got the TapeStation tube strip and strip caps 
- Added 2ul of sample buffer to each of 5 tubes in the TapeStation tubes 
- Added 2ul of library to each tube with sample buffer. I went in order of 2-6 
- Vortexed tubes for 1 minute
- Spun down tube 
- Logged into computer and turned on TapeStation, opened software 
- Loaded sample tubes, took of the caps gently, and loaded in the screen tape 
- Selected 5 wells and named them, right clicking the "ladder" position and changing it to electronic ladder so I could put a sample in the first position 
- Closed the lid and pressed start
- Machine ran for ~5 minutes 
- A folder is created for the date, exported the results as a pdf and saved it to that folder. Then renamed the folder by adding initials and Unckless after it 
- Took out tubes, pipette tips, and screentape from the machine, put the screentape back in the fridge as there were spots left, and shut down the machine 
- Saved pdf on flashdrive 
- TapeStation PDF can be seen [here](https://drive.google.com/file/d/1m0yAocffW9VLs_ZE7eqysDZrAkHuzw8P/view?usp=share_link)

**Monarch PCR and DNA Clean Up Kit**
- Total volume out of the Blue Pippin is ~40ul, and the protocol says to use the 7:1 binding buffer to sample ratio
- Transferred the PCR reaction from each sample to new 1.5mL tubes 
- Added 252ul of DNA Cleanup Binding Buffer to each sample tube 
- Pipette mixed to mix the sample 
- Prepared a spin column for each sample 
- Added the ~300ul of sample to the corresponding spin column 
- Centrifuged the spin columns at 16,000 rcf for 1 minute 
- Discarded the supernatant
- Added 200ul DNA Wash Buffer to each column 
- Centrifuged the columns at 16,000 rcf for 1 minute 
- Discarded the supernatant 
- Added another 200ul DNA Wash Buffer to each column
- Centrifuged the columns at 16,000 rcf for 1 minute
- Discarded the supernatant 
- Centrifuged the column “dry” for 1 minute at 16,000 rcf 
- Placed spin column in a new 1.5mL tube for each sample 
- Added 20ul of DNA Elution Buffer (TE buffer) to each column and let sit for 1 minute
- Centrifuged columns for 1 minute at 16,000 rcf 
- Froze the purified libraries at -20