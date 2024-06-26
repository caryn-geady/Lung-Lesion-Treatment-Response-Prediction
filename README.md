# Lung-Lesion-Treatment-Response-Prediction
 Code + Data for the Manuscript titled "Radiomic-Based Prediction of Lesion-Specific Systemic Treatment Response in Metastatic Disease"

 # Abstract
Despite sharing the same histologic classification, individual tumors in multi metastatic patients may present with different characteristics and varying sensitivities to anticancer therapies. In this study, we investigate the utility of radiomic biomarkers for prediction of lesion-specific treatment resistance in multi metastatic leiomyosarcoma patients. Using a dataset of n=202 lung metastases (LM) from n=80 patients with 1648 pre-treatment computed tomography (CT) radiomics features and LM progression determined from follow-up CT, we developed a radiomic model to predict the progression of each lesion. Repeat experiments assessed the relative predictive performance across LM volume groups. Lesion-specific radiomic models indicate up to a 4.5-fold increase in predictive capacity compared with a no-skill classifier, with an area under the precision-recall curve of 0.70 for the most precise model (FDR = 0.05). Precision varied by administered drug and LM volume. The effect of LM volume was controlled by removing radiomic features at a volume-correlation coefficient threshold of 0.20. Predicting lesion-specific responses using radiomic features represents a novel strategy by which to assess treatment response that acknowledges biological diversity within metastatic subclones, which could facilitate management strategies involving selective ablation of resistant clones in the setting of systemic therapy. 

# Instructions
- (recommended) create a new environment and install necessary dependancies (scripts/lung-prediction.yml);
- run analysis script for output (main.py)
