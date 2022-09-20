# Image Captioning

An implementation of Vanilla RNN, LSTM, and Attention LTSM from scratch using PyTorch. This part of the implementation was done following the tutorial from assignment 4 of the course EECS 498-007/598-005 (Deep Learning for Computer Vision) from the University of Michigan.

In this repository, instead of using the preprocessed data file `coco.pt`, the Microsoft COCO dataset is downloaded to preprocess the data manually. The notebook `rnn_lstm_attention_captioning.ipynb` shows all the steps to run the project (The results were trained for 5 epochs).

## Libraries
* PyTorch and Torchvision
* Pillow
* Matplotlib
* nltk
* Pycocotools (Installation instructions are in the notebook)