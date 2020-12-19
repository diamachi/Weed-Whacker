# THEME: AGRICULTURE-- FALL_FEST Hackathon 2020
**Weed identification and classification**

## Problem Overview:
Robotic weed control has seen increased research of late with its potential for boosting
productivity in agriculture. Majority of works focus on developing robotics for croplands,
ignoring the weed management problems facing rangeland stock farmers.<br>
Due to lack of knowledge, farmers face many problems regarding weed control like stock
injury, poisoning, unwanted growth etc. These problems can be dealt with if farmers can be
provided with relevant information on the query plant.

## Our Solution:
Solution to the problem, our project is aimed to create a Convolutional Neural Network
based deep-learning model to identify weed plants instantly by just using one or two
pictures of the plant. Ready to use, the whole system will be integrated into a simple-to-use
app.<br>
By simply pointing your phone at the plant and a few snaps, the app will tell you whether the
pointed plant is a weed or not along with full description of the plant to help farmers deal
with it.<br><br>
Apk Link : https://drive.google.com/file/d/1nD9PSW64tflKK9aYXoBrU04tq6PDPM-t/view?usp=sharing
<br>
Here's a demo video: https://drive.google.com/file/d/1fGhh9ljr5I642INx4QdCnx3YlZxwnQlO/view?usp=drivesdk

## Performance:
Our top model reached **0.978 Accuracy score** with efficientnetB2 as backbone and Ranger optimiser trained on 448x448 image size.<br><br>
*But because we wanted to reduce the application size to minimum and model to be more mobile-efficient, we changed the architecture to **Mobilenet_V2**.*<br><br>
With Mobilenet_V2 as backbone we reached **0.967 Accuracy Score** trained on 512x512 image size with Ranger optimiser.

## Dataset:
We used **DeepWeeds** dataset which can also be found in TensorFlow official datasets.<br>
Below are the drive links for direct access:
- [images.zip](https://drive.google.com/file/d/1xnK3B6K6KekDI55vwJ0vnc2IGoDga9cj/view?usp=sharing)(468 mb)
- [labels.csv](https://drive.google.com/file/d/1z4GmMJQrBwV_xKqsm0OihhSyil0hBvck/view?usp=sharing)

## Repo description:
- **pytorchAndroid** contains source code for the app.
- **Notebooks** contains some of the kernel files we used to train different models. 
- **Trained_weights** contains weight files for the respective models.


