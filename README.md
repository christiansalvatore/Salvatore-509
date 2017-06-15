update 2017.01.09: dataset uploaded | <a href="mailto:christian.salvatore.ibfm.cnr.it">contact me</a> if you need direct access to the image dataset <br>
update 2016.11.21: the dataset will be uploaded in the next days

# Salvatore-509

[![DOI](https://zenodo.org/badge/71118017.svg)](https://zenodo.org/badge/latestdoi/71118017)

This is a public dataset to be used as a benchmark in the field of automatic classification of Alzheimer's Disease.

This repository does not contain any data from patients itself. Data are taken from the <a href="http://adni.loni.usc.edu/" target="_blank">Alzheimer's Disease Neuroimaging Initiative (ADNI) public database</a>, from where they can be downloaded after registration. 

This repository provides:
  1. IDs of patients (corresponding to the IDs of subjects in the ADNI database)
  2. Fixed splitting indexes to perform a 20-fold nested cross-validation

Using this information, data of patients can be downloaded from the ADNI platform, and used in a 20-fold nested cross-validation, thus obtaining results that can be easily compared to previously published studies.

This dataset consists of 509 patients, including 137 AD, 76 MCIc, 134 MCInc, 162 CN. Fixed splitting indexes are provided for the following binary comparisons: AD vs CN, MCIc vs CN, MCIc vs MCInc. 

### Previous literature
This dataset was first used in its original form in a paper by Cuingnet et al. (Automatic classification of patients with Alzheimer's disease from structural MRI: a comparison of ten methods using the ADNI database. NeuroImage, 2011), where validation was performed with half-splitting into training and testing subsets and leave-one-out in the training subset for validation.

The actual form of the database (20-fold nested cross-validation) was first used in a paper by Salvatore et al. (Magnetic resonance imaging biomarkers for the early diagnosis of Alzheimer's disease: a machine learning approach. Frontiers in neuroscience, 2015).

### State of the art
On this [page](https://christiansalvatore.github.io/2016-10-20/is-this-alzheimer/#Salvatore-509), up-to-date classification performance on this dataset are reported. Results are given in terms of accuracy or balanced accuracy of classification. Sensitivity, specificity and AUC are also reported (when provided).

### Citing
>Salvatore, C. et al. (2015). Magnetic resonance imaging biomarkers for the early diagnosis of Alzheimer's disease: a machine learning approach. Frontiers in neuroscience, 9.

### ADNI policy
ADNI data cannot be publicly shared by private users. It was not possible to directly upload data in this repository. However, feel free to <a href="mailto:christian.salvatore.ibfm.cnr.it">contact me</a> if you need more information about how to access data or about data used in the original paper by Salvatore et al.

Remember to follow the [ADNI data sharing and publication policy](http://adni.loni.usc.edu/wp-content/uploads/how_to_apply/ADNI_DSP_Policy.pdf), if you are going to publish a work in which data from the ADNI database were used.
