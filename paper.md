---
title: StoichiometryFitter: An Interactive WebApp for Mineral Analysis
tags:
  - Python
authors:
  - name: Zack Gainsforth
    affiliation: 1
  - name: Michael Ofengenden
    affiliation: 1
  - name: Zhenbang Yu
    affiliation: 1
    
affiliations:
 - name: Space Sciences Laboratory, University of California Berkeley, 7 Gauss Way, USA
   index: 1

date: 15 November 2022
bibliography: paper.bib

## Summary
In 2016, Zack Gainsforth created a GUI for fitting solids and analyzing mineral phases. Gainsforth developed a software tool for the analysis of multi-phase quantification of materials. One would provide the quantification of elements as input in the form of atomic %, elemental weight % oxide weight % (with cation oxidation states), or as raw counts of TEM measurements.(((((((((((((MORE THAN 'ANALYSIS')))))))))))))))) When using raw counts, one can also use Stoichiometry Fitter to apply a set of k-factors, a thickness correction, and a detector correction. More of the use cases of the 2016 version are listed in Gainsforth's Previous paper(((((FOOTNOTE/CITATION)))))). 
In 2022, Gainsforth, Ofengenden, and Yu worked on updating Stoichiometry to the current version, including updating to the latest python version, providing more capabilities, adding more phases, and including Qmin (((((((((INSERT FOOTNOTE))))))))) a mineral recognition webapp. Then by turning it into a WebApp, our hope is that this tool will be more readily available to the public and will help make the research of geologists, minerologists, and chemists alike, more efficient and easy when exploring new minerals. 


## Statement of Need
Allows a researcher to convert elemental quantification to meaningful conclusions about mineral phases through python scripts. Researchers will then be able to reproduce results on multiple inputs using the same python scripts. Stoichiometry Fitter produces standard outputs for various minerals including Ternary diagrams, ... etc(((MORE EXAMPLES)), allowing and improving reproducibility for Geologists and researchers on different elemental compositions. Stoichiometry is and easy to use program that simplifies the understanding process for researchers interested in the analysis of a specified mineral. In the case where the researcher is unsure of the mineral that is composed by inputs of element quantifications, Ofengenden and Yu have integrated QMin ((((INSERT FOOTNOTE)))))) into Stoichiometry Fitter. This allows for 

3) Produces standard outputs for various minerals including ternary diagrams, etc. improving reproducibility between researchers.

4) Eases understanding mineral systems that are new to the researcher and how that leads into Qmin.

5) Allows removing common artifacts from elemental quantifications.

## State of Field
How will this software compare to others or other packages in the field

## Mathematics
Chemistry Calculations:



## Citations, Mentions, & References

Citations to entries in paper.bib should be in
[rMarkdown](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)
format.
