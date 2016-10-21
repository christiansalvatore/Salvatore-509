# Salvatore-509
This is a public dataset to be used as a benchmark in the field of automatic classification of Alzheimer's Disease.

This repository does not contain any data from patients itself. Data are taken from the <a href="http://adni.loni.usc.edu/" target="_blank">Alzheimer's Disease Neuroimaging Initiative (ADNI) public database</a>, from where they can be downloaded after registration. 

This repository provides:
  1. IDs of patients (corresponding to the IDs of subjects in the ADNI database)
  2. Fixed splitting indexes to perform a 20-fold nested cross-validation

Using this information, data of patients can be downloaded from the ADNI platform, and used in a 20-fold nested cross-validation, thus obtaining results that can be easily compared to previously published studies.

This dataset consists of 509 patients, including 137 AD, 76 MCIc, 134 MCInc, 162 CN. Fixed splitting indexes are provided for the following binary comparisons: AD vs CN, MCIc vs CN, MCIc vs MCInc. 

### Previous literature

Results are given in terms of accuracy or balanced accuracy of classification. Sensitivity, specificity and AUC are also reported when provided. Results below chance (50%) are not reported. 

### Original dataset
