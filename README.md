# COVID 19 DETECTION USING AUDIO AND METADATA

Dataset using in this project: https://github.com/iiscleap/Coswara-Data

In order to run the project, dataset should be downloaded and exported into **./Extracted_data**

--------
## TECH STACK
--------
- TPOT
- pandas
- numpy
- sklearn
- imbalance
- matplotlib
- seaborn
- audiomentations
- librosa

------
## FILE RUN STEP
------
1. initial_preprocessing.ipynb
2. data_cleaning.ipynb
3. data_augmentation_under_sampling.ipynb
4. extract_audio_features.ipynb
5. TPOT_generator.ipynb
6. covid_19_detection_pipeline.ipynb

-------
## MODEL PERFORMANCE
-------
![classification report](./img/classification_report.png)

![confusion matrix](./img/confusion_matrix.png)

![ROC](./img/ROC.png)


------
## AUDIO FEATURES IN THIS PROJECT
------
![audio features](./img/audio_features.png)
