## Merck-NLP-on-Protein-Sequences

This repository contains all the files that have been used for the research on NLP on Protein Sequences by the Merck - Purdue Datamine collaboration.

The two folders consist of both of the bioinformatics we have used: BioPhy and MOE.

Outside of that, there is a CSV file that consists of all the data compiled together in an excel file.
There is also a PNAS dataset given by the article we have used as a reference this year:
https://www.pnas.org/doi/10.1073/pnas.1616408114#fig02

# MOE Work Folder:
There are three Jupyter Notebooks in this folder.

MOE-Data-Analysis and MOE-Analysis-2 are both focused on the smaller sample of descriptors with 25 columns.

In the MOE-Data-Analysis notebook, we used several analytics processes such as removing outliers, scaling, preliminary correlations with Accelerated Stability.

In MOE-Analysis-2, we made a new dataset to outline the correlation matrix, and identify multicolinear variables, to remove them. Then we conducted a cross validation test, with 4 models and conducted those tests induvidually and get their respective r squared. 

In Complete_MOE we take the 120 descriptor columns and reduce it down 59 columns and then repeated the proccesses done for the smaller dataset. Then we created k means clustering to isolate groups of antibodies shown in the R squared graphs, and conducted feature importance analysis. We also labeled the points of the antibodies to get a better scientific understanding.

# BioPhy Work Folder

There is a single Notebook in this folder. It consists of some prelimianary pre processing with some target descriptors, however we've come across some challenges handling 1200 descriptor columns and adjusting that number to our needs.

