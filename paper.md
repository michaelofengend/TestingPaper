---
title: 'StoichiometryFitter: An Interactive WebApp for Mineral Analysis'
tags:
  - Python
authors:
  - name: Zack Gainsforth
    affiliation: "1" 
  - name: Michael Ofengenden
    equal-contrib: true
    affiliation: "1"
  - name: Roger Yu
    equal-contrib: true
    affiliation: "1"
affiliations:
 - name: Space Sciences Laboratory, Univeristy of California Berkeley, 7 Gauss Way CA, USA
   index: 1
date: 20 November 2022
bibliography: paper.bib

# Optional fields if submitting to a AAS journal too, see this blog post:
# https://blog.joss.theoj.org/2018/12/a-new-collaboration-with-aas-publishing
aas-doi: 10.3847/xxxxx <- update this with the DOI from AAS once you know it.
aas-journal: Astrophysical Journal <- The name of the AAS journal.
---

# Summary
We present an updated software tool[@Gainsforth:2016] for the quantification and analysis of materials. This app is determines sample composition from elements input in the form of atomic %, elemental weight %, oxide weight % (with cation oxidation states), or as raw counts. Raw counts currently support TEM and XRF measurements using k-factors. Planned future work will support SEM geometries. This app is provided as a web app at (link) and can be run locally. Tutorial video avaliable here__. We hope that Stoichiometry Fitter will be more accessible to the public now and will help geologists, mineralogists, and chemists alike, making research more efficient and easy when exploring new minerals. Stoichiometry Fitter also takes in account thickness and absorption correction for more accurate results analysis. (more of use case thinkness correction)

The app supports elaborate analyses of your phases via add-on python scripts.  Scripts for many major minerals and mineral systems are already included, and more will be added in the future.  QMin[@Guilherme:2021] analysis uses machine learning to identify minerals.


# Statement of need
Stoichiometry Fitter is useful in four main ways:

1. It allows for reproducibility, meaning the program can reproduce results on multiple inputs using the same python scripts. Stoichiometry fitter outputs it in standard formats where citations for calculations are automatically generated, and the speed of analysis is much faster and more efficient than other platforms or methods. 

2. Stoichiometry allows the user to remove common artifacts from these quantifications simplifying the understanding process and easing procedure mineral analysis. It also allows for elaborate computations and plotting including Ternary diagrams, superlattice analyses for sulfides, or site occupancies for Pyroxene. Spreadsheets and excel are commonly used to write csv files and analyze elemental compositions from experimental data which can be slow and suffers from the inability to support complex computing tasks. Stoichiometry Fitter resolves this issue by presenting a scalable program that can analyze element quantifications from a direct input or a large text file. The program can then output multi-dimensional analysis. Along with the visuals and other integrated features of Stoichiometry Fitter, it allows for a faster and more thorough than many other computational spreadsheet programs.

3. Stoichiometry Fitter is an easy to use program providing researches with detailed analyses of specific minerals. In cases, where the researcher is unsure of the mineral, our team has integreates QMin[@Guilherme:2021] into the app to allow for identification and classification of new or unknown materials.

4. Stoichiometry Fitter allows a researcher to convert elemental quantification to meaningful conclusions about mineral phases through python scripts.

# Program Layout
![View of WebApp.\label{fig:example}](image.png)
and referenced from text using \autoref{fig:example}.

Chemistry Calculations:

# References

