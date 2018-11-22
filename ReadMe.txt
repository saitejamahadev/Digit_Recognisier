This project is used to detect the handwritten digits using Convolutional newural networks and Open CV .

cnn_model.ipynb contains following steps :

1.Import all the necessary dependencies.
2.load data set from the Keras library & check data shapes.
3.Pre-process the data i.e Nomalize, Onehotencode the data labels and reshape the data .
4.Define and design the CNN network.
5.Compile the model.
6.Fit the model.
7.Save the model weights to be used in the CV2_app.ipynb

CV2_app Contains following steps :

1.Import all the dependencies.
2.Load the model weights saved from cnn_model.ipynb into cv2_app.
3.Read the Image from webcam and process the image.
4.input the processed image to the newural net and check the output.


Sample Outputs are attached with code.
