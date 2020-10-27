# RSNA-Kaggle


![](https://www.transparentpng.com/download/bronze-medal-png/bronze-medal-blank-png-images-17.png = 20x20) 58th Place Solution


Here is a brief Description of all the notebooks in this repo.

## Stage1 Models
* cnn-stage1-train.ipynb (EfficientNet-B0 is used as binary classifier to predict `pe_present_on_image` target)
* cnn-stage1-train-multilabel.ipynb (EfficientNet-B0 is used as multi label classifier to predict the remaining 9 targets)

## Stage2 Models
* cnn-gru-stage2-train-inference.ipynb (CNN-GRU model is used on top of features extracted from stage1 models)
* cnn-gru-stage2-train-self-attention.ipynb (CNN-GRU-Self-Attention model is used on top of features extracted from stage1 models)

## Final Ensemble
* ensemble-stage2-models(self attention+GRU).ipynb (In this notebook, we ensembled our 2 stage2 models)


https://www.kaggle.com/c/rsna-str-pulmonary-embolism-detection/leaderboard

### Public LeaderBoard Score: 0.225
### Private LeaderBoard Score: 0.218
