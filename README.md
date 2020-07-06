# Alphonso-Mango-Classification

This notebook is used to classify whether a given input image is an Alphonso Mango. 

The idea is to showcase the below, 

* Building a CNN image classifier from scratch using a `tf.keras.Sequential` model and load data using `tf.keras.preprocessing.image.ImageDataGenerator` class to efficiently work with data on google drive.
* Learning the pitfalls after evaluating the model built in previous step; As we notice _Overfitting_; progressively attempt to prevent it via _Data augmentation_ and _dropout_ — The Key techniques to fight overfitting in computer vision tasks to incorporate into the data pipeline and image classifier model.
* Incorporate Transfer Learning to avoid further pitfalls due to scarcity of data and reduce the trainig time, Ultimately harnessing the power of transfer learning to maximize accuracy.

This notebook follows a basic machine learning workflow:

1. Examine and understand data
2. Build an input pipeline
3. Build the model
4. Train the model
5. Test the model
6. Further Improve the model via Data Augmentation, Dropout, Transfer Learning and repeat the previous workflow steps.
