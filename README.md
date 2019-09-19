
# Object Detection with Bounding Box Regression

The project demonstrates the working of the Bounding Box Regression technique used in 
object detection tasks. It can efficiently predict the four coordinates of a 
bounding box around the image with its class probabilities too.

View the article on Medium ~> 
[Getting Started With Bounding Box Regression In TensorFlow](https://towardsdatascience.com/getting-started-with-bounding-box-regression-in-tensorflow-743e22d0ccb3)

Check out the Google Colab notebook ~> https://colab.research.google.com/drive/1usT_XYE6DLENeUL3__GNCYAWn-0NbVh6#forceEdit=true&offline=true&sandboxMode=true

The following files are included in this repo:

1. `DataProcessor.py` : Extract the images and XML annotations to convert them `.npy` files
 ready for training/testing.
 
2. `Model.py` : Defines the CNN model and other useful methods.

3. `MainFile.py` : Trains the model on the data.

4. `Evaluation.py` : Loads a model from the given `h5py` file and predicts bounding 
boxes for various images, draws them on the image and then finally saves the images 
to a directory.

By default, the `Evaluation.py` file reads the pretrained model weights which are 
included with the repo.

Make sure you download the data first -> https://www.kaggle.com/mbkinaci/image-localization-dataset


