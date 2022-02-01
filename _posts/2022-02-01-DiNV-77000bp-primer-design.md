---
layout: post
title: Primer Design for DiNV 77,000-78,000bp
---

## Designing Primers for the 77,00-78,00bp Region of the DiNV Genome with Geneious

**Using the [Geneious Primer Design Tutorial](https://www.geneious.com/tutorials/primer-design-prime/) as a reference, and using the [guidelines for primer design from Addgene](https://www.addgene.org/protocols/primer-design/) and [Zymo Research](https://www.zymoresearch.com/blogs/blog/how-to-design-primers-for-pcr-experiments)**

What I want out of these primers
  - Amplify a region roughly between 77,000 and 78,400bp in the DiNV genome
    - Why? Because of CRISPR sites:
    - Site 92: 77,223bp
    - Site 27: 77,384bp
    - Site 86: 77,454bp
    - Site 73: 77,892bp
  - Primer length between 18 and 24 nucleotides
  - GC content of the primers between 35-60%
  - Melting Temperature (Tm) between 50-60 degrees C
  - Melting Temperatures between the F and R primers be within ~2-3 degrees C
  - No secondary structure/hairpins

Forward Primer

  - It's hard to design primers for this genome because it's so AT rich!
  - Candidate 1 for forward primer: 76,921 - 76,940bp
    - Length: 20nt
    - Tm: 60.2 degrees C
    - GC content: 55%
    - No hairpin
    - Sequence: CATCGCGCACCCATCTCTAA
  - Because it's so hard to find a Tm for the reverse that matches the one above, I looked for a second forward primer
  - Candidate 2 for forward primer: 76,760 - 76,781bp
    - Length: 22nt
    - Tm: 57.4 degrees C
    - GC content: 40.9%
    - No hairpin
    - Sequence: GTGCAAAGTCAAGTTGTCAGAT

Reverse Primer

  - Candidate 1 for reverse primer: 78,312 - 78,335bp
    - Length: 24nt
    - Tm: 58.2 degrees C
    - GC content: 37.5%
    - No hairpin
    - Sequence: TTCTTGATGTAGTTCTGCTTACGT
  - But the GC content is close to the low end in this one, so I tried finding another
  - Canidate 2 for reverse primer: 78,659 - 78,651bp
    - Length: 23nt
    - Tm: 57.5 degrees C
    - GC content: 43.5%
    - No hairpin
    - Sequence: CCTCAGTAGCCGTATCAAGTATT

Comparing the Primers

|Pair #s| start and stop|length of PCR product|Tm difference|
|---|---|---|---|
|F-1 and R-1|76,921 - 78,335bp|1,414bp|2 degrees|
|F-1 and R-2|76,921 - 78,651bp|1,730bp|2.7 degrees|
|F-2 and R-1|76,760 - 78,335bp|1,575bp|0.8 degrees|
|F-2 and R-2|76,760 - 78,651bp|1,891bp|0.1 degrees|
