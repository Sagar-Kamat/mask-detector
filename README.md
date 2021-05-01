### This is a YOLOv3 based model that draws bounding boxes around faces and detects whether the person is wearing a mask or not. Apart from that, the model also displays the confidence score of its prediction. 

#### The dataset used is a custom dataset wherein I downloaded 120 images from google and annotated each of them using labelImg. I used 2 classes, Mask and No Mask which can be extended to 3 classes by including Partially Wearing as the 3rd class. 

#### I started with Darknet for the pretrained model and used transfer learning to make the model work on my dataset.

#### You can run this model on your own dataset, just make sure you fine tune the hyperparameters according to your needs.
