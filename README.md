#SAVE DA FISH 

Project Problem Statement from Kaggle Competition called [The Nature Conservancy Fisheries Monitoring](https://www.kaggle.com/competitions/the-nature-conservancy-fisheries-monitoring/discussion/27100).

The dataset provided by can be downloaded [here](https://www.kaggle.com/competitions/the-nature-conservancy-fisheries-monitoring/data).

Gdrive folder of our code running in Colab [here](https://drive.google.com/drive/folders/1KwbHwZRHPAKHasZbCa-3WJiZ15t2SQ6j?usp=sharing).


## Notebooks folder
> This folder contains all the .ipynb files used to train and evaluate models.

| Name                | Description                                                                        |
| ------------------- | ---------------------------------------------------------------------------------- |
| EDA                 | Used to analyse the dataset provided.                                              |
| VGG16               | Our first model that we tried, forms the baseline.                                 |
| AlexNet             | Our second model that we tried, forms the baseline.                                |
| ResNet152           | Our third model that we tried, deeper but lower in accuracy.                       |
| EfficientNetB4-V1   | Our fourth model that we tried, smaller and better in accuracy.                    |
| EfficientNetB4-V2   | Implemented regularization techniques, however achieved lower accuracy.            |
| EfficientNetB4-V3   | Implemented lesser regularization techniques, achieved comparable accuracy to V1.  |
| LIME Interpretation | Implemented LIME on V1 and V3 model to analyse what influences the model decision. |
| Model Evaluation    | Evaluation pipeline to get confusion matrix and classification report.             |

## Models folder
> This folder contains selected weights used by our GUI (uploading all weights would exceed the size limitation of repositories).

| Name                               | Description                                        |
| ---------------------------------- | -------------------------------------------------- |
| efficientnet_10_25_full.pt         | Model weights of the `EfficientNetB4-V1` model.    |
| efficientnet_03_full_state_dict.pt | Model weights of the `EfficientNetB4-V3` model. |