---
layout: post
title: 15.5 Hour Gel of HMW Samples and Gel Extraction for PCR
---

## Second Attempt at Running a ~16 Hour Gel on HMW DNA Samples, Cutting out a "150kb" Region, and Gel Extracting to Get DNA for PCR

**Notes**
- Using a 0.8% gel and running at 40V because this keeps all the DNA on the gel, and a lower gel percentage is good for the extraction
- Using the [QIAquick Gel Extraction Kit](https://www.qiagen.com/us/products/discovery-and-translational-research/dna-rna-purification/dna-purification/dna-clean-up/qiaquick-gel-extraction-kit/)
- Decided to run my best sample on the gel (90ng/ul) only, and twice just to have replication. This is the 130hr sample
- Decided to put in two PFG ladders just in case one ran strange
- When slicing the gel, because we don't have any separation of the bands in the PFG marker between 48.5-245kb, I was really guessing on where the "150kb" size would be. I decided to cut out a slice where I guessed it would be, and then also a slice above and below that region to see if I could amplify DiNV in those sizes too. I also noticed that there was glowing in the well, so I cut out a slice there too
- I warmed up the buffer EB and increased the incubation time on the column with the EB to 30 minutes to try to get larger fragments to elute (if that was the issue)

**20211116 Loading and Running Gel**
- .8% gel mix:
  - 180mL 1X TAE
  - 1.4g agarose
- Microwaved for ~4min
- Pipetted 1mL into a 1.5mL tube and saved on the heat block at 65 degrees C **make sure the heat block is on and running**
- Made sure the large tray had well sealed tape barriers
- Let the gel liquid cool for ~10 min until pouring into the tray and placing in the combs
- Gel cooled in ~20 min or less
- Added 1 round of PFG ladder to the left-most well, then another round to the well next to that (first two wells)
- Let the 1mL saved gel cool for ~3 min outside of the heat block
- Filled the PFG wells with cooled gel liquid to the top of the well to seal the rounds in
- Waited ~3 minutes for the wells to cool
- Made up 48kb ladder:
  - 1.2ul ladder
  - 6ul loading dye
  - 28.8ul molecular grade water
- Placed the gel tray into the box after removing the tape
- Added 16ul 48kb ladder to the well right next to the PGF well
- Mixed 15ul 120hr sample with 2ul loading dye and added into the 4th well
- Mixed another 10ul 120hr sample with 2ul loading dye and added into the 6th well - leaving a space open. Also I was afraid to use all the sample so that's why I did only 10ul
- Set the timer for 16 hours at 40 volts and started it at ~5:15pm

**20211117 Imaging, Cutting, and Gel Extraction**
- Stopped the gel at ~8:50am, it had ran 15.5hrs
- Sliced the gel in half and put the half with samples in the EtBr bath for 1 hr
- Prepped for imaging and cutting the gel: made tubes for the gel pieces and weighed them, got glasses, lab coat, gloves, and face shield ready, cleaned a razor blade with ethanol
- First, imaged the gel and saw that this gel was pretty faint compared to yesterday's, also that the markers looked a little scrunched still
- It was hard to slice out the right section of the gel, the bottom (where the DNA was) didn't super want to come out of the gel. I tried cutting out the excess gel on the slices that I could, some of them seemed to have DNA at the bottom and the top of the gel and not in the middle, which I couldn't slice around. Also the dye kept getting fainter the longer I had the UV on, even though I turned it off every time I wasn't actively using it to slice the gel. I don't know what that means, or if the DNA was getting messed up during that process
![](https://raw.githubusercontent.com/meschedl/Unckless-Lab-Notebook-Maggie/master/images/20211117-gel.jpeg)
- Then I weighed each tube to get the weight of the gel piece. I had not prepared for the well slices, so I had not pre-weighed their tubes. I used 993mg as their starting weight

|Sample name|Tube weight (mg)|Tube with gel weight (mg)| Gel weight (mg)|3 volumes of gel (ul)|
|---|---|---|---|---|
|120A|993.4|1045.8|52.4|157.2|
|120B|993.6|1015.2|21.6|64.8|
|120A UP|994.2|1044.1|49.9|149.7|
|120A LOW|989.8|1033.5|43.7|131.1|
|120B UP|993.7|1049.5|55.8|167.4|
|120B LOW|985.5|1025.5|40|120|
|120A WELL|NA|1030|37|111|
|120B WELL|NA|1013.7|20.7|62.1|

- Added "3 volumes" of the gel to each tube with Buffer QG (5th column in table above)
- Tubes were spun down and placed in a heat block for 10 minutes at 50 degrees C
- An aliquot of buffer EB was also added to the heat bloack at this time to warm up
- Tubes were vortexed and spun down once during the incubation
- Tube color was yellow, but 10ul of 3M NaOAc pH 5.2 was added to each tube, they were vortexed and spun down
- Added 1 gel volume (column 4 in table above, but in ul) of 100% isopropanol to each tube and inverted to mix
- Set up spin columns for each sample
- Added total volume to the spin columns with clipped pipette tips (~200ul)
- Centrifuged columns 1 min, 17,900g
- Discarded flow through
- Added 750ul buffer PE to each column
- Centrifuged columns 1 min, 17,900g
- Discarded flow through
- Centrifuged columns 1 min, 17,900g "dry"
- Transferred columns to final 1.5mL tubes
- Added 50ul warmed buffer EB to the columns
- Let tubes sit for 30 minutes
- Centrifuged columns 1 min, 17,900g
- Removed columns and stored tubes
- Qubitted tubes immediately, yields were still quite low but at least all readable this time
  - 120A: 1.71ng/ul
  - 120B: 0.496ng/ul
  - 120A UP: 0.18ng/ul
  - 120A LOW: 1.15ng/ul
  - 120B UP: 0.629ng/ul
  - 120B LOW: 0.492ng/ul
  - 120A WELL: 0.321ng/ul
  - 120B WELL: 0.275ng/ul

Even though these quants are low, I will try a PCR on them anyways, for p47 (DiNV) and CO1 (fly/control)
