---
layout: post
title: qPCR of Exonuclease Treated DNA
---

## qPCR on DNA Through the Exonuclease Treatment to See if it Enriches DiNV DNA Compared to Cellular DNA

To test the [exonuclease treatment](https://meschedl.github.io/Unckless-Lab-Notebook-Maggie/2024/01/11/exonuclease-treatment-test.html) the samples need to be run on qPCR to look at the ratio of DiNV DNA to cellular DNA. I will use the DNA before treatment and after treatment for this. Even though two samples from the treatment came out as no DNA from the qubit, I decided to try qPCR on them anyways. 

Information on these samples can be found [here](https://docs.google.com/spreadsheets/d/19HplN9TvH7pDqtDkWpclmwUZHeBB1PwhQunieT6FHSo/edit#gid=0)

- All DNA was kept on ice, flicked to mix, and spun down before use 
- Samples were diluted before use:
    - 16 and 17 - diluted 1:10 2ul DNA in 18ul of 10mM tris HCl 
    - 18 and 19 - diluted 1:100 2ul DNA in 198ul of 10mM tris HCl
    - 16-exo and 19-exo - **not** diluted because of low/no DNA 
    - 17-exo and 18-eco - 1:1 4ul DNA in 4ul of 10mM tris HCl 
- Reagents and primers were thawed on ice, vortexed, and spun down before use 
- TPI master mix: 
    - 125ul Sso supermix 
    - 12.5ul TPI F primer 
    - 12.5ul TPI R primer 
    - 75ul molecular grade water 
- PIF3 master mix: 
    - 125ul Sso supermix 
    - 12.5ul PIF3 F primer 
    - 12.5ul PIF3 R primer 
    - 75ul molecular grade water 
- Master mixes were kept on ice and vortexed and spun down before use 
- 9ul of the appropriate master mix was added to the wells of a qPCR plate 
- 1ul of diluted (or not) DNA was added to the planned wells (see plate layout below)
- Each well was pipette mixed with a multichannel 5ul 10 times 
- The plate was sealed and centrifuged for ~7 minutes at 4000g to remove bubbles 
- The plate was placed in the qPCR machine and ran on the p47 program from the KMM folder 

plate layout (primer is in the last column and corresponds to the whole row): 

|   | 1      | 2      | 3      | 4      | 5      | 6      | 7      | 8      | 9      | 10     | 11     | 12     |primer|
|---|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|--------|------|
| A | 16     | 16     | 16     | 17     | 17     | 17     | 18     | 18     | 18     | 19     | 19     | 19     | TPI  |
| B | 19-exo | 19-exo | 19-exo | 18-exo | 18-exo | 18-exo | 17-exo | 17-exo | 17-exo | 16-exo | 16-exo | 16-exo | TPI  |
| C | 16     | 16     | 16     | 17     | 17     | 17     | 18     | 18     | 18     | 19     | 19     | 19     | PIF3 |
| D | 19-exo | 19-exo | 19-exo | 18-exo | 18-exo | 18-exo | 17-exo | 17-exo | 17-exo | 16-exo | 16-exo | 16-exo | PIF3 |
| E |        |        |        |        |        |        |        |        |        |        |        |        |      |
| F |        |        |        |        |        |        |        |        |        |        |        |        |      |
| G |        |        |        |        |        |        |        |        |        |        |        |        |      |
| H |        |        |        |        |        |        |        |        |        |        |        |        |      |


All data from the qPCR machine can be found [here](https://drive.google.com/drive/folders/1dEbj0K9BZdYc9kKf8ZW93plF7OFPawo9). Analysis of the qPCR results can be found [here](https://github.com/meschedl/Unckless_Lab_Resources/blob/main/qPCR_analysis/20240112-exo-treatment-test/20240112-exo-treatment-test.md). 
