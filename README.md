# R sample - Cancer Cell-of-Origin Determination
This project serves as an R code sample and it contains cancer cell-of-origin determination based on mutational landscape that has a potential to be used in cancer diagnostics.  
It contains majority of my master thesis code. Thesis is available in english at https://repozitorij.pmf.unizg.hr/en/islandora/object/pmf%3A10544.  
In this work I explored correlation between melanoma single nucleotide polymorphism and multiple chromatin marks of various healthy cell types in order to find melanoma cell-of-origin using the Random Forest regression analysis.  

#### This project is seperated in five parts:
In **Part One** I dowloaded reference genome and divided it into 1 megabase windows.  
**Part Two**  contains chromatin mark data download for seven histone modifications and overlap count with the divided reference genome. 
In **Part Three**  I demonstrated melanoma SNP mutation data filtration and overlap count with the reference genome.  
In **Part Four** I performed Random Forest regression analysis, visualised the results, performed statistics and determined the correct cell-of-origin.  
**Part Five** contains additional plots in order to observe correlation between SNP mutation and chromatin marks.

