## About Dataset

[https://www.kaggle.com/datasets/sriraj66/speech-emotion-detection-dataset](https://www.kaggle.com/datasets/sriraj66/speech-emotion-detection-dataset)

# Speech Emotion Detection Dataset

## Overview

This dataset is designed to aid in the recognition of emotions from speech. It includes labeled speech data with various emotions such as  **happy** ,  **sad** ,  **angry** , and  **neutral** . The dataset also contains audio features like  **MFCCs (Mel Frequency Cepstral Coefficients)** ,  **pitch** , and **speech rate** to help build emotion recognition models.

## Features

* **Emotion Labels** : Happy, Sad, Angry, Neutral
* **Audio Features** : MFCCs, Pitch, Speech Rate
* **Data Size** : 1000 audio samples
* **Format** : CSV containing extracted features and corresponding emotion labels.

## Use Cases

* Speech Emotion Recognition
* Sentiment Analysis
* Human-Computer Interaction
* Voice-based AI Applications
* Psychological and Behavioral Studies

## How to Use

1. Download the dataset from Kaggle: [Speech Emotion Detection Dataset](https://www.kaggle.com/datasets/sriraj66/speech-emotion-detection-dataset)
2. Extract the features (MFCCs, pitch, speech rate) from the audio samples for use in machine learning models.
3. Train emotion recognition models using the provided labels.

## Citation

If you use this dataset in your research or project, please cite it as follows:

```
Sriram R. (2024). *Speech Emotion Detection Dataset*. Kaggle. https://www.kaggle.com/datasets/sriraj66/speech-emotion-detection-dataset
```

## License

This dataset is released under the [Open Dataset License](https://www.kaggle.com/datasets/sriraj66/speech-emotion-detection-dataset).



## Overview

This dataset is designed to aid in the recognition of emotions from speech. It includes labeled speech data with various emotions such as  **happy** ,  **sad** ,  **angry** , and  **neutral** . The dataset also contains audio features like  **MFCCs (Mel Frequency Cepstral Coefficients)** ,  **pitch** , and **speech rate** to help build emotion recognition models.

## Column Descriptors

The dataset consists of the following columns:

1. **Emotion** : The emotion label for the speech sample (Happy, Sad, Angry, Neutral).
2. **MFCC_1** to  **MFCC_13** : Mel-frequency cepstral coefficients (MFCCs) extracted from the audio signal. These are commonly used features in speech recognition and emotion detection tasks.
3. **Pitch** : The fundamental frequency (in Hz) of the speech sample, which is often correlated with emotion.
4. **Speech_Rate** : The rate at which the speaker is talking, measured in words per minute (WPM).
5. **Gender** : The gender of the speaker (optional, if applicable in your dataset).
6. **Audio_File** : The name of the corresponding audio file (for reference, if available).
