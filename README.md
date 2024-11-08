# Generate Dense Segmentation Mask from Sparse Point Lables
This repository contains script for execution of task carried out for generating dense mask from sparse point labels. Different variants of SAM were compared. Preprocessing and postprocessing were done to check if they help to improve performance of model.

## Folder Structure
1. DifferentVariantsOfSAM <br>
This folder contains all scripts for generating dense mask from sparse point labels using different variants of SAM (SAM, SAM2.1, SAMHQ).

2. preprocess_SAMHQ_base <br>
This folder contains all scripts for generating dense mask from sparse point labels using SAM-HQ base model and applying 16 different preprocessing techniques.

3. postprocessing <br>
This folder ontains scripts for performing morphological operation: opening on generated mask to remove noise from mask.