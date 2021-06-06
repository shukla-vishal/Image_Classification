# Image_Classification
Image classification refers to the task of extracting information classes from a multiband raster image. The resulting raster from image classification can be used to create thematic maps. Depending on the interaction between the analyst and the computer during classification, there are two types of classification: supervised and unsupervised.

Hyperspectral data is widely used for the analysis of remotely sensed images and it includes hundreds of number of bands. Machine learning techniques are widely used in classification of remotely sensed data.Data was acquired by the ROSIS (Reflective Optics System Imaging Spectrometer) sensor during a flight campaign over Pavia, northern Italy. 
The number of spectral bands is 103 for Pavia University. Pavia University dataset contains 610*340 pixels.The geometric resolution is 1.3 meters and ground-truth consist 9 classes.

Ground truth classes for the Pavia University scene and their respective samples number
![image](https://user-images.githubusercontent.com/64328738/120937034-b2f5bb00-c728-11eb-8b79-e70dbfb110f0.png)



 ![image](https://user-images.githubusercontent.com/64328738/120937038-bbe68c80-c728-11eb-91e0-045c44a41f7b.png)
                                                  ![image](https://user-images.githubusercontent.com/64328738/120937041-c1dc6d80-c728-11eb-9319-bc584122e84b.png)
                    

K-Nearest Neighbour(K-NN) is one of the simplest Machine Learning algorithms based on Supervised Learning technique.It assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories.K-NN algorithm stores all the available data and classifies a new data point based on the similarity.This means when new data appears then it can be easily classified into a well suite category by using K- NN algorithm.


Support Vector Machine(SVM) is a supervised machine learning algorithm which can be used for both classification or regression challenges.In the SVM algorithm, we plot each data item as a point in n-dimensional space (where n is number of features you have) with the value of each feature being the value of a particular coordinate. Then, perform classification by finding the hyper-plane that differentiates the two classes very well.

