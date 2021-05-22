# Face_Recognition

This is a simple project where you can create a simple face recognition given that you have atleast 3-5 images of the person whose face you want to be recognized.
The steps followed are simple:
1. A folder named Dataset is created, inside which each subfolder should be the name of the person you want the model to recognise. Inside the subfolder you must store the photos of this person.(Note: the photos should only contain the person you want to be recognised and not others.)
2. In the Training notebook functions are written to read these files and create a dataset.
3. A pre-trained DNN Face Detector is used to extract the faces
4. A pre-trained facenet keras model is used to convert the detected faces into embeddings
5. A SVM model is trained to differentiate between the different face embeddings.
6. All objects used for training are saved using joblib so they can be used in other notebook for inference.
8. An inference notebook is provided where you can run the code quickly and start recognising people.
