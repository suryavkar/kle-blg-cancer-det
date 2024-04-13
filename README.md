# Computer-aided Cancer Detection

A deep learning model, based on Convolutional Neural Networks (CNN), is used for identifying prostate cancer tissue, using patches derived from whole slide images stained with hematoxylin and eosin, provided by [KLE Hospital, Belgavi](https://www.klehospital.org).

Due to confidentiality reasons, raw data cannot be shared. [`model.ipynb`](model.ipynb) contains snippets of some of the data.
Final model cannot be made public. [`model.ipynb`](model.ipynb) is one of the models trained during development of the project. The overall training process is outlined in the notebook.

Other files contain some of the pre-processing techniques used to refine the model.

# Some training patches
<p align="left"> <a> <img src="https://github.com/suryavkar/kle-blg-cancer-det/blob/main/images/training_patches.png" alt="train_patch" width="1200" height="500"/> </a> </p>

# Some validation patches
<p align="left"> <a> <img src="https://github.com/suryavkar/kle-blg-cancer-det/blob/main/images/validation_patches.png" alt="val_patch" width="1200" height="500"/> </a> </p>

# Confusion matrix
<p align="left"> <a> <img src="https://github.com/suryavkar/kle-blg-cancer-det/blob/main/images/confusion matrix.png" alt="conf_mat" width="1200" height="400"/> </a> </p>

## Dependencies:
- Tensorflow
- NumPy
- Matplotlib
- Scikit-Learn

Install dependencies using `pip install -r requirements.txt`
