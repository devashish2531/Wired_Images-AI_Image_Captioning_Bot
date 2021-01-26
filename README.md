# Wired_Images   AI Image Captioning Bot
# [Flask - Wired_Images Repository](https://github.com/devashish2531/Wired-Images_Flask/)

With the help of this project, machine can generate its own captions related to the image. 
The model uses Flickr8k dataset for training data and uses LSTM for training and CNN for extracting the image features.
Also created a flask web application for the same - [Wired-Images_Flask](https://github.com/devashish2531/Wired-Images_Flask/).
## Dataset
Flickr30k Image dataset has been used for training the model.
This dataset contains 8000 images and there are 5 captions for each image.

## The Model made contains:

1) Image model: for reducing image of high dimensions into selected features.  
2) Language model: for creating output as embeddings to reduce complexity of model. 
3) Final model: which will concatenate results of both this model and will use LSTM layer and Time Distributed layer for doing final_predicttions.

## Screenshots
![FaceableCapture2](https://i.imgur.com/Z6bzOlg.jpg)
![FaceableCapture3](https://i.imgur.com/eEaXMpQ.jpg)
![FaceableCapture3](https://i.imgur.com/lybydHX.jpg)
