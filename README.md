# realTimeRecognition
using:
- Python 3.9.19
- Tensorflow 2.10.1
# collecting data set
- run collect.ipynb to collect photos(dataset) for each class

# labelling
- run git clone https://github.com/HumanSignal/labelImg inside Tensorflow directory
- run setup.py  
- label for every image and divide into train and test dataset

# get tensorflow

- run git clone https://github.com/tensorflow/models inside Tensorflow
- go to Tensorflow\models\research\object_detection\packages choose your tf version and run the setup in the main directory.(/realTimeRecagnition in this case)

# run train.ipynb
- after 6. Train the model, copy output and paste in terminal(main directory) this will train your model
