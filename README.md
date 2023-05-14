Skin Lesion Classification - Thesis Code
Student name: Erdem Akca

This repository contains the code used in my thesis titled "Seeing Beyond the Surface: Classifying Skin Lesions". The research involves three models: RepVGG (a baseline CNN model), MaxViT, and MviTv2 (Vision transformer models).

Repository Structure

data_processing.ipynb: This notebook contains the code used for data splitting, processing and saving the data.

exploratory_data_analysis.ipynb: Here, you can find the code that was used for exploratory data analysis.

Experiments
In the thesis, three experiments were conducted for each model. Each notebook is named after the model and experiment applied. The following abbreviations are used:

no_data_aug: No data augmentation was applied.
randaug: Data augmentation technique called RandAugment was applied.
ROSandRUS: Random oversampling and undersampling were applied.


