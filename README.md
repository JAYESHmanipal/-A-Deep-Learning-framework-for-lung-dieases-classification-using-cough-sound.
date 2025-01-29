# -A-Deep-Learning-framework-for-lung-dieases-classification-using-cough-sound.



The project aims to diagnose pulmonary diseases by analyzing respiratory sounds using
advanced AI technologies, including machine learning and deep learning techniques .
 Responsibilities:
* Audio feature extraction
 * Handle imbalanced data
* Perform multimodel Deep learning approach (ResNet50, EfficientNet, Bi-GRU + AttentionLayer + XGBoost).

Audio Preprocessing: Raw data has been preprocessed using audio splitting, noise reduction, and normalization to reduce the file size which contains relevant data only, and to improve the data quality.
Feature Extraction: The preprocessed data undergoes feature extraction to produce mel-spectrogram images for model training.
Model Training: Binary and 8-class classification has been performed in three models: EfficientNet, VGG16, and ResNet50 where EfficientNet proved to show a higher accuracy for the 8-class classification.




Dataset:

The project uses the ICBHI 2017 Dataset, consisting of 920 audio samples from 126 subjects, all annotated by medical experts. This dataset is notable for being one of the largest publicly available databases in the field of respiratory diseases.

Dataset used: https://www.kaggle.com/datasets/vbookshelf/respiratory-sound-database/data?select=Respiratory_Sound_Database
