## CryMLClassifier - Baby Cry Classification Model

This repository contains the source code and dataset for the CryMLClassifier, a machine learning model designed to classify baby cries into five types: burping, belly pain, discomfort, hungry, and tired. The model is trained on the "Donate a Cry Corpus Dataset," which is a publicly available dataset widely used for baby cry analysis.

### Dataset
The dataset used for training and evaluation is the "Donate a Cry Corpus Dataset." Unfortunately, the direct link to the dataset is currently unavailable. However, you can find more information about the dataset and how to access it by visiting the official website or contacting the dataset creators directly.

### Features Extraction
The folder "features_extraction" provides a demonstration of the various features used in the classification process. It includes sample code and information on feature extraction techniques. However, please note that the actual CryMLClassifier model utilizes 193 features, as described below.

### Features Used
The CryMLClassifier model utilizes 193 features extracted from the audio data of baby cries. These features include the following:

- 40 MFCCs (Mel-frequency cepstral coefficients)
- 12 chroma features
- 128 mel-spectrogram features
- 7 spectral contrast features
- 6 tonnetz features

These features are extracted from the audio samples and used as inputs to the machine learning algorithms for classification.

### Model Training
The CryMLClassifier model has been trained and evaluated using various machine learning algorithms, including K-Nearest Neighbors (KNN), Support Vector Machines (SVM), Decision Trees, Random Forest, and XGBoost. After experimentation, the Random Forest and XGBoost models have shown promising results in terms of accuracy.

The accuracy achieved by the CryMLClassifier model using these algorithms is as follows:
- K-Nearest Neighbors 90.58%
- Support Vector Machine 92.18%
- Decision Tree 96%
- Random Forest: Approximately 99.59%
- XGBoost: Approximately 99.79%

Please note that the performance of the model may vary based on different factors, and these accuracy values are specific to the dataset and evaluation methods used in this project.

### Requirements
Make sure you have the required Python libraries installed before running the code. You can install them using the pip package manager by executing the following command:

```bash
pip install jupyter sklearn librosa numpy pandas matplotlib seaborn
```

### Execution
To execute the code, follow these steps:

1. Download the entire folder, including the dataset and source code.
2. Install the required Python libraries as mentioned in the "Requirements" section.
3. Open the Jupyter notebook or Python script containing the source code.
4. Run the code to train and evaluate the CryMLClassifier model.
5. You can modify the code as needed for further experimentation or analysis.

For any inquiries or issues related to the CryMLClassifier model or the code, please feel free to contact me.

-------------------------------
