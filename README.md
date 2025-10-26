# TensorFlow-Keras-Regressor
The pretrained model 'ResNet50' is retrained to predict people age from their image faces, this is, the regression problem is solved for face images.

## Details
* The model is stored in Hugging Face, use the following link to download it:

https://huggingface.co/AntonioArteaga7/Face-Regressor/resolve/main/model_face.h5

* In folder "notebooks" are the Jupyter Notebooks used to train the model and the Jupyter Notebook "make_regression_predictions.ipynb" used to make predictions with the model. This model should be downloaded and saved in folder 'models' as 'model_face.h5'.
* In folder "test" are some images used to test the model, other images can be also used.

## 🚀 How to use the model locally to make predictions
1. Clone this repository:
```
git clone https://github.com/arteaga7/TensorFlow-Keras-Regressor.git
```
2. Set virtual environment and install dependencies:
```
python3 -m venv env && source env/bin/activate && pip3 install -r requirements.txt
```
3. Create folder "models" and copy the downloaded model into it with the filename 'model_face.h5'.
4. Run "notebooks/make_regression_predictions.ipynb".

## 🎯 Results
After running "make_regression_predictions.ipynb", the following results were obtained.

<img width="1202" height="726" alt="image" src="https://github.com/user-attachments/assets/f86f23b8-9d71-4004-9c3d-74f66e246642" />

Mean Absolute Error (MAE): 10.5, Mean Squared Error (MSE): 243.83 and R^2 Score: 0.15.

## ♟️ Conclusion
The MAE (Mean Absolute Error) is acceptable. The performance of the model is related to the dataset quality, pretrained model used (Resnet50), convolutional neuronal network design and batch size of training. Due to limitations in computing power, this model could not be trained better. This model was trained in a core i7 second generation processor with 4GB of RAM memory. In order to improve the model performance, not only the batch size should be increase, but also the dataset quality.
