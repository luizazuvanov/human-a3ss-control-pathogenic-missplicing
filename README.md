# The spliceosome active center reads a cis-regulatory code to control alternative splicing during catalysis

Code and data relating to the article: “The spliceosome active center reads a cis-regulatory code to control alternative splicing during catalysis” (Marciano, G. and Eckert, S., and Zuvanov, L. *et al.*)

### Overexpression of C* factors mutants

This folder contains alternative splicing analysis from RNA sequencing data of overexpressed C* factor mutants. Input data, code, requirements, output files of significant events data, and output plots are shared.

### Machine learning

This folder contains all the material required for data selection, training and prediction steps. Furthermore, disease-related variants and minigenes information can be found there. In detail:

##### Data selection:
Selection of alternative splicing and gene expression data from siFAM32A RNA-sequence to be used for model training. Feature investigation plots and final “ml_input.csv” data can be found in the subfolder “output”.

##### Model:
Stores model training step information and final model pickle file. Three models with different feature sets were trained. Models related output files include precision-recall and SHAP plots. Further model parameters and evaluation metrics results are also made available.

##### Prediction:
Included in the subfolder “input”, there are the processes and data used for variant selection and feature retrieval. In addition, minigenes used for model validation and variant testing are also found. Finally, input data with selected features was predicted for FAM32A regulation using the final model from the previously mentioned “model” folder.


Further information can be found in the “Methods” section of the referred article.
