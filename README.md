# Nucleus-Semantic-Segmentation
This is a model to perform the semantic segmentation of nuclei in stained tissue images. The model uses a UNet architecture which is commonly employed for biomedical image analysis. The dataset to train this model has been borrowed from the [2018 Data Science Bowl](https://www.kaggle.com/c/data-science-bowl-2018) on kaggle. The training data file is too large to be uploaded here even when compressed, it can be downloaded from the aforementioned link. I have used PyTorch as my framework to build this model. An IoU of about 0.75 was achieved on training for 30 epochs with standard Adam optimizer hyperparameters.
