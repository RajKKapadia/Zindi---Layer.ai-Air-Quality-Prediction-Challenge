# Zindi - Layer.ai Air Quality Prediction Challenge
Hello, this is my attempt to [this](https://zindi.africa/competitions/layerai-air-quality-prediction-challenge) competition hosted by [Zindi](https://zindi.africa/).

I have used the following things here:

* ANN build using Tensorflow
* Keras Tuner to fund the best hyper parameters

This strategy did not work well on the leadrborad but the take away here is that I learned a completely new technology.

## Installation
First create a new python virtual environment, activate that virtual environment and install the required packages

> pip install -r requirements.txt

## Clean the data
Run the Jupyter notebook `clean_dataset.ipynb` to clean the dataset and split them into `train` and `valid` dataset.

## Develop the model
Run the Jupyter notebook `model_w_keras_tuner.ipynb` to train a model, generate submission file, and save the best model. This will do the following things:

1. train a model
2. predict on test dataset and generate submission csv file inside the `submissions` folder
3. save the best model in `best_model` folder

# About me

I am `Raj Kapadia`, I am passionate about `AI/ML/DL` and their use in different domains, I also love to build `chatbots` using `Google Dialogflow ES/CX`, I have backend development experience with Python[Flask], and NodeJS[Express] For any work, you can reach out to me at...

* [LinkedIn](https://www.linkedin.com/in/rajkkapadia/)
* [Fiverr](https://www.fiverr.com/rajkkapadia​)
* [Upwork](https://www.upwork.com/freelancers/~0176aeacfcff7f1fc2)
* [Youtube](https://www.youtube.com/channel/UCOT01XvBSj12xQsANtTeAcQ)
