* The file *RID.mat* contains the RIDs of the patients (rows) according to the notation used in the ADNI data repository.

* The file *cross-validation indexes.mat* contains the splitting indexes for each comparison.
RIDs of the patients are additionally reported together with the corresponding label as obtained from the ADNI data repository. <br>
For each comparison, the table has the following structure (each patient corresponding to a different row): <br>
|--  *RID*  --|--  *Label*  --|--  *Cross-validation index*  --|

For the following comparisons, we have:

1. CN vs AD > Label for CN = 0, label for AD = 1
2. CN vs MCIc > Label for CN = 0, label for MCIc = 1
3. MCInc vs MCIc > Label for MCInc = 0, label for MCIc = 1
