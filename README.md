# Image_Captioning
Image Captioning project using CNN and RNN(LSTM) as a part udacity computer vision nanodegree program.
![](.//Image/sample_output.JPG?raw=true)

CNN as Encoder(convert image to embedded image feture vectors) and LSTM as Decoder(generates caption from embedded word vector).
Here's a sumary of the steps involved.


- Dataset used is the COCO data set by Microsoft.
- Feature vectors for images are generated using a CNN based on the ResNet architecture by Google.
- Word embeddings are generated from captions for training images. NLTK was used for working with processing of captions.
- Implemented an RNN decoder using LSTM cells.
- Trained the network for nearly 5 hrs using GPU to achieve average loss of about 2%.
- Obtained outputs for some test images to understand efficiency of the trained network.<br/>


![](.//Image/encoder-decoder.png?raw=true)
Used COCO dataset for training(https://cocodataset.org).
