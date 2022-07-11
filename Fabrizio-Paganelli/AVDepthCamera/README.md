# AVDepthCamera

This is an iOS app merging two features:
 - a colour camera that uses a Core ML model for predicting number gestures (0 to 5);
 - a grayscale camera with a Core ML Model for predicting three hand gestures: *fist, palm, ok.*

The app starts in grayscale mode, just tap on the screen to change model and prediction. *Models can be downloaded using the link below.*

## Authors

### [Filippo Paganelli](https://github.com/FilippoPaganelli)

### [Ginevra Fabrizio](https://github.com/lamebanana)

## Models

We used MobileNetV2 (224x224 rgb) for both of the two versions. It's been retrained on each of the two datasets to recognise the appropriate label classes.

About the net: [MobileNetV2](https://arxiv.org/abs/1801.04381)

Our trained models: [here](https://drive.google.com/drive/folders/1GT8UrlIU3_3XRNL_Poii4Mz_-IT3YuA8?usp=sharing)
(drag the models and drop them in Xcode workspace)

## Datasets

 Grayscale: [Multi-Modal Dataset for Hand Gesture Recognition](https://www.kaggle.com/adeshdalvi41/hand-signs)
  
 Colours: [Hand Gestures Dataset](https://www.kaggle.com/gti-upm/multimodhandgestrec)

## The Colab we used

[Our colab](https://colab.research.google.com/drive/1NpvKpCy_snJcUu5afDZeTyWdHsZEFMVa?usp=sharing) (for any question about the code, don't mind contacting us)

## Dataset images

Grayscale dataset preview:

![Grayscale](/Fabrizio-Paganelli/AVDepthCamera/images/grayscale_dataset_preview.png)

Colours dataset preview:

![Colours](/Fabrizio-Paganelli/AVDepthCamera/images/colours_dataset_preview.png)

## Working app snapshot

![Snapshot_app](/Fabrizio-Paganelli/AVDepthCamera/images/app_preview.png)
