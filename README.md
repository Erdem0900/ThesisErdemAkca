**Skin Lesion Classification - Thesis Code**

Student name: Erdem Akca

This repository contains the code used in my thesis titled "Seeing Beyond the Surface: Classifying Skin Lesions". The research involves three models: RepVGG (a baseline CNN model), MaxViT, and MviTv2 (Vision transformer models).

**Repository Structure**

data_processing.ipynb: This notebook contains the code used for data splitting, processing and saving the data.

exploratory_data_analysis.ipynb: This notebook containd the code that was used for exploratory data analysis.

**Experiments**

In the thesis, three experiments were conducted for each model. Each notebook is named after the model and experiment applied. The following abbreviations are used:

**no_data_aug:** No data augmentation was applied.							

**randaug:** Data augmentation technique called RandAugment was applied.

**ROSandRUS:** Random oversampling and undersampling were applied.



**Reference to the specific libraries that were used in this code**

• Ming Yang. "Imbalanced-Dataset-Sampler." 2018. [Online]. Available: https://github.com/ufoym/imbalanced-dataset-sampler. Accessed: April 19, 2023.

• Ross Wightman. "PyTorch Image Models." GitHub repository. 2019. [Online]. Available: https://github.com/rwightman/pytorch-image-models.

• Takuya Akiba, Shotaro Sano, Toshihiko Yanase, Takeru Ohta, and Masanori Koyama. 2019. Optuna: A Next-generation Hyperparameter Optimization Framework. In KDD (arXiv).


