<img src="https://www.pallikkutam.com/uploads/news_images/1526369477.jpg" height=400>

> "You can't Handle the Truth!"

# TransferLearning_On_WebBrowser
I made a custom 4-class object classifier using the webcam on the fly. We're going to make a classification through MobileNet model for a particular webcam image and use that for classification. 

## Built With
* [TensorflowJs](https://www.tensorflow.org/js) - TensorFlow.js is a library for developing and training ML models in JavaScript, and deploying in the browser 
* [Flask](https://flask.palletsprojects.com/) - Flask is a micro web framework written in Python.
* [MobileNet](https://github.com/tensorflow/tfjs-models/tree/master/mobilenet) - MobileNet is an architecture which is more suitable for mobile and embedded based vision applications where there is lack of compute power. This architecture was proposed by Google.

## Requirements:
- A recent version of chrome browser.
- A text editor
- Understanding of HTML, CSS, JavaScript and Chrome Dev Tool

## Getting Started
- Load index.html page in your Chrome browser.
- you can use common objects or face/body gestures to capture images for each of the three classes(eg: Add A, Add B, Add C). 
- Each time you click one of the "Add" buttons, one image is added to that class as a training example. While you do this, the model continues to make predictions on webcam images coming in and shows the results in real-time.
- I have also added a "No Class" button to make sure that No class is predicted other than A, B, C. 
- **Make Sure that you send single training example by clicking button sequentially from Left to Right.**
