---
layout: post
title: qPCR Comparison of Hirt Extraction and Puregene Extraction
---

## Doing qPCR to Compare DiNV Levels in Hirt Extracted DNA and Puregene Extracted DNA

Using DNA samples from [Hirt Extraction](https://meschedl.github.io/Unckless-Lab-Notebook-Maggie/2022/09/01/hirt-extraction-test-3.html) and [Puregene Extraction](https://meschedl.github.io/Unckless-Lab-Notebook-Maggie/2022/09/10/puregene-on-hirt-samples.html). These DNA are from the exact same samples, just with different extraction methods. The goal is to see if the Hirt method does give a better ratio of DiNV DNA to Dv-1 cell DNA. Samples were normalized to 1ng/ul before use in qPCR. DiNV primers are called 115, and Dv-1 cell primers are RPL11.

**DNA dilution to 1ng/ul**
- All samples were kept on ice and/or thawed on ice

|Tube number|Sample|Sample DNA concentration|ul DNA|ul Molec grade water for 1ng/ul concentration|
|---|---|---|---|---|
|1|Hirt 1.5-2|63.7ng/ul|2ul|127.4ul|
|2|Hirt 0.75|35.5ng/ul|2ul|71ul|
|3|Hirt 0.5-C|130ng/ul|2ul|260ul|
|4|Puregene 1.5-2|3.72ng/ul|3ul|11.16ul|
|5|Puregene 0.75| 3.57ng/ul|3ul|10.71ul|
|6|Puregene 0.5-C|26.1ng/ul|2ul|52.2ul|

**qPCR setup**
- I have 6 samples, which need to be run in triplicate for 2 primers, so that will be 6 * 3 * 2 = 36 separate reactions
- However I will need to make 2 separate mastermixes for the two primers
- Kent suggested starting the machine and the computer before starting the process to make sure no one takes the computer before you need it
  - Turn on qPCR machine so it can warm up
  - Log into computer
  - Click on the Biorad CFX manager
  - Click user defined, then select existing, then KMM, then p47 program
- Using [SsoAdvanced Universal SYBR Green Supermix](https://www.bio-rad.com/en-us/product/ssoadvanced-universal-sybr-green-supermix?ID=MH5H1EE8Z) as the reagent for the qPCR
- Make master mixes on ice
- RPL11 master mix:
  - 5ul Sso * 21 = 105ul
  - 0.5ul RPL11 F * 21 = 10.5ul
  - 0.5ul RPL11 R * 21 = 10.5ul
  - 3ul molec grade water * 21 = 63ul
- 115 master mix
  - 5ul Sso * 21 = 105ul
  - 0.5ul 115 F * 21 = 10.5ul
  - 0.5ul 115 R * 21 = 10.5ul
  - 3ul molec grade water * 21 = 63ul
- Vortexed and spin down mixes
- Added 9ul of RPL11 mix to 18 wells A1-9 and B1-9
- Added 9ul of 115 mix to 18 wells C1-9 and D1-9
- Added 1ul DNA to those wells (see table), where the number corresponds to the tube number in the above table

||1 |2 |3 |4 |5 |6 |7 |8 |9|10|11|12|
|---|---|---|---|---|---|---|---|---|---|---|---|---|
|A|1|1|1|2|2|2|3|3|3||||
|B|4|4|4|5|5|5|6|6|6|
|C|1|1|1|2|2|2|3|3|3|
|D|4|4|4|5|5|5|6|6|6|
|E|
|F|
|G|
|H|

- Put the plate seal on the plate and made sure to take off the perforated edges
- Spun down the plate in 4055 (I should have vortexed it before this)
- Pressed the open lid button on the machine
- Put the plate in
- Pressed the lid button again
- Pressed start on the computer
- Program runs for about an hour
- Saved the results to a new folder on the computer with my name
- After the run was done, exported all the files onto a flash drive to use on my computer

**Analysis**
