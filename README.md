# Face-Mask-Recognition
The Face Mask app has been designed to check if the User is wearning mask or not.
We will be training the model with face mask images as well as non-mask images . The webcam will be opened to see if the person is wearing mask or not and draw a square around the face which will show the percentage of wearning a mask or not

# Dataset and Modelling
We will be designing a model that will be able to distinguish the masked images and non-masked images. The dataset contains of masked and non-masked images. The data was obtained from Kaggle and other oper source datasets.
Once the data is imported we will preprocess the input images and convert the labels into encoding. Once the dataset is splitted into Training and Test along with augmentation we will use MobileNetV2 model to train the base layers. Then we will be using the normal convolution operation to train the further layers. The operation was done for 20 epochs.

We are coding two files where one file will be used to check if the user is wearing a mask or not and the other file will be used to invoke the webcam and apply the mask detection techniques.

Another file will be coded where the facial features will be detected and a blob will be created to detect the face.
The app identifies the facial features and then checks if the user is wearing mask or not. We will use files containing the facial features detection and weights that will detect face and use the previously developed mak detector file to check if the face detected has mask or not.

We will use the model that was obtained from mask detector and add them with MobileNet model which will enable to detect the mask worn faces as well as run the video by invoking webcam.
Streamlit was used to develop the model and it can be run on the localhost.

![image](https://user-images.githubusercontent.com/76935226/140601593-8bdd83b0-ccb8-4406-9224-1235ab31e8b3.png)
![image](https://user-images.githubusercontent.com/76935226/140601598-a42f2ce3-5d55-4923-8812-d9565dd2f273.png)
![8](https://user-images.githubusercontent.com/76935226/140601616-5b4b1221-f7c0-4db6-a98b-f7a4acb066c4.jpg)

![Screenshot (176)](https://user-images.githubusercontent.com/76935226/149612815-da930d99-3aa9-45bb-b2d3-f42d70ce2b39.png)



