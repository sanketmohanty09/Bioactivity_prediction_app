# Bioactivity_prediction_app

**1- Collection of Dataset**
The dataset was collected from the chembl database for the acetylcholinesterase inhibitors which can be used as drug for the treatment of alzheimer's disease.There are total 4800 compunds dataset.

**2-EDA**
The Lipinski's rule of 5 was used to calculate the drug-likeness of the given compound and IC50 was converted to pIC50(-log(ic)) as it is more continous in nature.Based on the solubility factor compunds can be divided into 3 class active,inactive,intermediate.

Finally,PaDEL-Descriptor was used to calculate the molecular descriptors and fingerprints which were used as features to train our model.For better understanding please check my EDA_Bio file in the code folder

**3-Model**
I have trained the dataset on the 2 most commonly used bagging and boosting method that are RandomForest and XGBoost,I got the best performance from the RandomForest model.I have also used lazypredict to check the  the performance in various other models.

**4-Webapp**
A web appliction was created using streamlit


