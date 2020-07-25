# Facial  Recognition
This model is created to be used as a Facial recogination model in a software. It helps to distinguish between different faces of human beings so it to used for identification purposes or to lock your phone as a security tool also. Concept of transfer learning is used in this model. For that we have used the mobile.Net as our transfer learning model to have better accuracy rate. For dataset images of two individuals is used so to check if machine is successfull in to  distinguish between them or not. Finally model with best accuracy is saved automatically as a .h5 file so to be used in which ever platform is needed ,so that no need to carry around the code forever. We have used Keras as our library which uses world famous tensorflow at backend.

## Transfer Learning 
Transfer learning is a research problem in machine learning that focuses on storing knowledge gained while solving one problem and applying it to a different but related problem. For example, knowledge gained while learning to recognize cars could apply when trying to recognize trucks.

## Mobile Net
MobileNet is an architecture which is more suitable for mobile and embedded based vision applications where there is lack of compute power. This architecture was proposed by Google. We have added three dense layers on our mobile set layers to train our model on our dataset. Mobile Net is best model to be used as our pre trained model because the reason lies in the traditional downsampling strategy and the computational cost of separable conv. 

For more info on mobile net click here ->https://ai.googleblog.com/2017/06/mobilenets-open-source-models-for.html

![11](https://user-images.githubusercontent.com/47302857/88198277-2a317600-cc61-11ea-9b37-22f11ee3f6c3.jpg)

## Keras 
Keras is an open-source neural-network library written in Python. It is capable of running on top of TensorFlow, Microsoft Cognitive Toolkit, R, Theano, or PlaidML. Designed to enable fast experimentation with deep neural networks, it focuses on being user-friendly, modular, and extensible. 

## Final Result 
Following were the screen shots taken so to check if our model is accurate or not by choosing random images:

1. 
![1](https://user-images.githubusercontent.com/47302857/88198197-171ea600-cc61-11ea-86bb-69b8f6671905.PNG)

2.
![2](https://user-images.githubusercontent.com/47302857/88198205-1ab22d00-cc61-11ea-9ece-ab29400066e8.PNG)

3.
![3](https://user-images.githubusercontent.com/47302857/88198214-1d148700-cc61-11ea-9e06-fec1e8b96a26.PNG)

4.
![4](https://user-images.githubusercontent.com/47302857/88198218-1ede4a80-cc61-11ea-9e30-1c22e6765ae6.PNG)

5.
![5](https://user-images.githubusercontent.com/47302857/88198225-200f7780-cc61-11ea-86b1-a5a1ac51986e.PNG)

6.
![6](https://user-images.githubusercontent.com/47302857/88198233-21d93b00-cc61-11ea-835a-93303b7260cf.PNG)

7.
![7](https://user-images.githubusercontent.com/47302857/88198238-23a2fe80-cc61-11ea-8710-2a3ade57a6fe.PNG)

8.
![8](https://user-images.githubusercontent.com/47302857/88198245-256cc200-cc61-11ea-8087-fb992f128e75.PNG)

9.
![9](https://user-images.githubusercontent.com/47302857/88198260-27368580-cc61-11ea-96f4-0023ace79b10.PNG)

10.
![10](https://user-images.githubusercontent.com/47302857/88198266-29004900-cc61-11ea-8a3d-ada8635937c5.PNG)



