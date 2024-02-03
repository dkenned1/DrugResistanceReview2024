# DrugResistanceReview2024

This is the README file accompanying the publication "Exceptions to the rule: When does resistance evolution not undermine antibiotic therapy in human bacterial infections?" by Bhattacharya et al. 

Files include the R code and raw data needed to reproduce the figures and analyses contained in the manuscript.  

The ERM data (expert review method) are contained in: Datav11_Apr19.2021.data.csv

The ARM data (algorithmic review method) are contained in: Masterfile_v8.csv

In the EMR dataset (i.e. "Datav11_Apr19.2021.data.csv"), for all columns showing resistance scores, 0="None/very rare", 1="Rare", and 2="Not rare" as defined in the manuscript.  For the column labeled "TransmissionType", 0="Direct transmission" and 1= "Indirect transmission" as defined in the manuscript.  For all other columns that take values of 0 or 1 only, 0="Not documented" or "No", and 1="Documented" or "Yes".

In the ARM dataset (i.e. "Masterfile_v8.csv"), each row is data for a unique study x pathogen x drug combination.  The relevant data for the manuscript were the number of resistant and not resistant isolates tested -- columns M ("Resistant") and N ("NotResistant") respectively.  These data sometimes had to be back caculated using the data in columns G through L.  For column T ("TransmissionType"), 0="Direct transmission" and 1="Indirect transmission" as defined in the manuscript.  For all other columns that exclusively take values of 0 or 1, 0="Not documented" or "No", and 1="Documented" or "Yes".  Units for all columns are as described in the manuscript.  
