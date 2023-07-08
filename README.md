# Solid Waste Segregation

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
Place your own dataset in training_data and testing_data folders,

```sh

   $ cd tutorial-2-image-classifier

   $ python train.py
   ```

### How to run:  

```sh
   $ git clone https://github.com/sai-adarsh/ImageClassifier.git

   $ cd ImageClassifier

   $ pip install -r requirements.txt
   ```
### Open and replace my project path with your respective path inside these files:
 * project\catvsdog\predictor\predict.py
 * tutorial-2-image-classifier\predict.py
 * tutorial-2-image-classifier\train.py


### After installing all requirements, to run in cmd:
   ```sh
   $ cd tutorial-2-image-classifier

   $ python predict.py <imageInputFileName.extension>
   ```

### To run the WebApp:
   ```sh
   $ cd project\catvsdog

   $ python manage.py runserver
   ```   
