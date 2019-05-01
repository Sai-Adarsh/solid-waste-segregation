# Image Classifier
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/check-it-out.svg)](https://forthebadge.com)

## Install

### Activate virtualenv

[Click here](https://stackoverflow.com/questions/14604699/how-to-activate-virtualenv) to read about activating virtualenv.

* #### For Linux
```sh
   $ source ./venv/bin/activate
```
* #### For windows
```sh
   $ cd venv/Scripts/
```
```sh
   $ activate
```   
### Training & Testing

How to train:
Place your own thermal dataset in training_data and testing_data folders,

```sh

   $ cd tutorial-2-image-classifier

   $ python train.py
   ```

### How to run:  

```sh
   $ git clone https://github.com/sai-adarsh/ThermalAI.git

   $ cd ThermalAI

   $ pip install -r requirements.txt
   ```
### Open and replace my project path with your respective path inside these files:
 * project\thermalai\predictor\predict.py
 * tutorial-2-image-classifier\predict.py
 * tutorial-2-image-classifier\train.py


### After installing all requirements, to run in cmd:
   ```sh
   $ cd tutorial-2-image-classifier

   $ python predict.py <imageInputFileName.extension>
   ```

### To run the WebApp:
   ```sh
   $ cd project\thermalai

   $ python manage.py runserver
   ```   
