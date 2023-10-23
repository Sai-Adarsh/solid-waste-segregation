## Solid Waste Segregation

This competition was known to be possibly "The Biggest AI Hackathon in India in terms of the number of Participants" (as of August 2018). We made a Solid Waste Segregating Image Processing Model powered by Convolutional Neural Networks embedded with Raspberry Pi and its Add-ons. TensorFlow, OpenCV, Amazon Web Services, Django Framework, Google Firebase, and Raspberry Pi were the technologies we used for this model.

## Getting Started
### Run:  
   ```bash
   $ git clone https://github.com/Sai-Adarsh/solid-waste-segregation.git
   
   $ cd solid-waste-segregation
   
   $ pip install -r requirements.txt
   ```
### Open and replace the project path with the respective path inside the below mentioned files:
   ```bash
   project\catvsdog\predictor\predict.py

   tutorial-2-image-classifier\predict.py

   tutorial-2-image-classifier\train.py
   ```

### Activate virtualenv
   ```bash
      # Linux
      $ source ./venv/bin/activate
   
      # Windows
      $ cd venv/Scripts/
   
      $ activate
   ```
### Train/Test
Place your thermal dataset in the training_data and testing_data folders.
   ```bash
   $ cd solid-waste-segregation
   
   $ python train.py
   ```

### Predict
   ```bash
   $ cd solid-waste-segregation

   $ python predict.py sample.jpg (any extension works)
   ```
### Run web app:
   ```sh
   $ cd project\catvsdog

   $ python manage.py runserver
   ```   
