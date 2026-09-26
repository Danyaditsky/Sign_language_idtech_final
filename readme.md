# Sign Language Interpreter


This project utilizes the Jetson Orin Nano to determine and distiguish between the ASL symbols representing all 26 letters of the Alphabet, as well as a few special keys such as periods, commas, and hyphens.


## Setup
1. Set up [Jetson Inference Project](https://github.com/dusty-nv/jetson-inference/tree/master) on local nano.
2. Clone this repository on github
3. Run Python script `python3 asl_net.py [input] [output]` 

## To-do
1. Finish organizing the datasets to train the model
2. [Training the model](https://github.com/dusty-nv/jetson-inference/blob/master/docs/pytorch-cat-dog.md) using said datasets
3. Add retrained onnx model to repository.
4. Testing that asl_net.py works with the retrained model.
5. Collecting example images/videos to showcase the model's output (that it works)