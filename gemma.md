# TriNitt-ML
Our project offers a robust platform for comprehensive analysis and captioning of remotely sensed images. By harnessing tailored machine learning models designed for the distinctive characteristics of satellite images, this platform facilitates efficient captioning, categorization, and utilization of satellite imagery. Additional features include the ability to locate the satellite image on Google Maps for region-specific details and maintaining a history of recent uploads on the platform.

## User Interface
![first_page](https://github.com/gemma-square/TriNitt-ML/assets/119145656/8ddbe917-64c4-4783-be61-56d6f4438cc1")
![second_page](https://github.com/gemma-square/TriNitt-ML/assets/119145656/18ae240b-2dec-4515-80cd-df8d12139f22)

KEY FEATURES:
+ **Image Captioning:**
  + Employs specialized ML for accurate image captions.
  + Enhances understanding of satellite images.
+ **History:**
  + Tracks recent uploads for quick reference.
  + Improves user experience.
+ **Google Map Integration:**
   + Integrates with Google Maps for precise image location.
   + Adds spatial context for insights.

## Deep Learning Model
We employ an encoder-decoder transformer with a self-curated architecture tailored to meet the distinct needs of satellite images. Trained on the standardized Remote Sensing Image Captioning Dataset (RSICD), our model utilizes an RNN-based GRU in the encoder (preferring GRU over LSTM to mitigate overfitting on a smaller database). For detailed model specifics, refer to the TRINITT.ipynb file. The model demonstrates an average validation and test accuracy of approximately 70%, promising better results on larger datasets and extensive scaling.

### Decoder architecture
<img src="https://github.com/gemma-square/TriNitt-ML/assets/119145656/e488b432-0e93-4e21-bac9-91f55081bbbd" width="300" height="500" />

### Encoder architecture
<img src="https://github.com/gemma-square/TriNitt-ML/assets/119145656/05ac39c0-11c4-4aab-92b2-73ec8a606f46" width="500" height="300" />

# Download the trained model from here
https://drive.google.com/file/d/1R7Go_0uNH4PwfL-LgbJ5GydT-BxhrX5C/view?usp=drive_link 

# Download the training dataset from here
https://drive.google.com/file/d/1RD37ydu0vnmHRJBRF2A1bUGCTDS3EgcE/view?usp=sharing

# Project Video Drive link
https://drive.google.com/file/d/19Tm02lK0kTY9hKh1BfC_rTnX8-xXi-CX/view?usp=sharing
