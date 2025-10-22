# TensorFlow-Keras-Regressor
The pretrained model 'ResNet50' is retrained to predict people age from their image faces, this is, the regression problem is solved for face images.

## Details
* The model is stored in Hugging Face, use the following link to download it:

www

* In folder "notebooks" are the Jupyter Notebooks used to train the model.
* In folder "test" are some images to test the model.
* The Jupyter Notebook "make_regression_predictions.ipynb" shows how to make predictions with the trained model. This model should be downloaded and saved in folder 'models' as 'model_face.h5'.

## 🚀 How to run locally
1. Clone the corresponding Hugging Face repository:
```
git clone https://huggingface.co/spaces/AntonioArteaga7/TensorFlow-Keras-Regressor.git
```
2. Set virtual environment and install dependencies:
```
python3 -m venv env && source env/bin/activate && pip3 install -r requirements.txt
```
3. Run "notebooks/make_regression_predictions.ipynb".

## Results
