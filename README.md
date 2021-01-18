# Face detection with OpenCV and deep learning
The best reference for Computer Vision is **pyimagesearch**
I used numpy, argparse. opencv. 

The **argparse** module makes it easy to write user-friendly command-line interfaces. The program defines what arguments it requires, and argparse will figure out how to parse those out of sys.argv. The argparse module also automatically generates help and usage messages and issues errors when users give the program invalid arguments.

Where this “hidden” deep learning face detector lives in the OpenCV library
How you can perform face detection in images using OpenCV and deep learning
How you can perform face detection in video using OpenCV and deep learning

When using OpenCV’s deep neural network module with Caffe models, you’ll need two sets of files:

The .prototxt file(s) which define the model architecture (i.e., the layers themselves)
The .caffemodel file which contains the weights for the actual layers
How does the OpenCV deep learning face detector work?
OpenCV’s deep learning face detector is based on the Single Shot Detector (SSD) framework with a ResNet base network (unlike other OpenCV SSDs that you may have seen which typically use MobileNet as the base network).

We have three required arguments for image:

--image : The path to the input image.
--prototxt : The path to the Caffe prototxt file.
--model : The path to the pretrained Caffe model.

We have Two required arguments for video:

--prototxt : The path to the Caffe prototxt file.
--model : The path to the pretrained Caffe model.

![Video_2021-01-17_150348](https://user-images.githubusercontent.com/46414243/104920344-4dcf4200-59a0-11eb-967f-99695e30091c.gif)
