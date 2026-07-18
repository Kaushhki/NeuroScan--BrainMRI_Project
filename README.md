# NeuroScan — Brain Disease Classification & Age Estimation from MRI

Multi-task CNN (TensorFlow/Keras) that classifies dementia stage and estimates age from OASIS-1 brain MRI slices.

## Results
- Overall classification accuracy: 77%
- Age estimation MAE: 10.5 years

## Files
- `NeuroScan_notebook.ipynb` — full training pipeline
- `best_model_final.keras` — trained model
- `meta.json` — class mapping + age normalization stats needed for inference

## Dataset
- Images: [OASIS Brain MRI (Kaggle)](https://www.kaggle.com/datasets/ninadaithal/imagesoasis)
- Demographics: [MRI and Alzheimer's (Kaggle)](https://www.kaggle.com/datasets/jboysen/mri-and-alzheimers)
