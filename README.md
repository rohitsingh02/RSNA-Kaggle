# RSNA-Kaggle
58th Place Solution


Here is a brief Description of all the notebooks in this repo.

## Stage1 Models
* cnn-stage1-train.ipynb (EfficientB0 is used as binary classifier to predict `pe_present_on_image` target)
* cnn-stage1-train-multilabel.ipynb (EfficientB0 is used as multi label classifier to predict the remaining 9 targets)

## Stage2 Models
* cnn-gru-stage2-train-inference.ipynb (CNN-GRU model is used on top of features extracted from stage1 models)
* cnn-gru-stage2-train-self-attention.ipynb (CNN-GRU-Self-Attention model is used on top of features extracted from stage1 models)

## Final Ensemble
* ensemble-stage2-models(self attention+GRU).ipynb (In this notebook, we ensembled our 2 stage2 models)


### Public LeaderBoard Score: 0.225
### Private LeaderBoard Score: 0.218
