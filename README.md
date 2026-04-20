# alzheimer-classification-model
Classifies patients into diagnostic categories (Cognitive Normal, Alzheimer's Disease, Late Mild Cognitive Impairment) using clinical, cognitive, and neuroimaging data. Merges multiple data sheets (diagnosis, cognitive scores, demographics/brain measures), performs feature engineering, and trains a Random Forest classifier.
Dataset


CSI_7_MAL_2324_CW_resit_data.xlsx -- an Excel workbook with three sheets:

Diagnosis target: diagnosis labels and FDG-PET values
Cognitive score: CDRSB, ADAS, MMSE, RAVLT scores
Data: demographics, genetics (ApoE4), and 361 brain structure measurements (volumes, surface areas, cortical thickness)


## Key steps:
- Data preprocessing and merging
- Handling missing values
- Feature encoding and scaling
- Model training and evaluation

## Results:
- Training accuracy: 1.0
- Test accuracy: ~0.72
- Cross-validation mean: ~0.71

## Note:
An earlier issue in label preprocessing caused incorrect evaluation results, which has now been fixed.
