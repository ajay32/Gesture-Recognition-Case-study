# Gesture Recognition

**Developed by:**

- **Ajay Mehta & Ayush Saxena**

Recognising 5 different hand gestures to control a smart TV

We need to develop a smart feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote. 

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:
 - Thumbs up:  Increase the volume
 - Thumbs down: Decrease the volume
 - Left swipe: 'Jump' backwards 10 seconds
 - Right swipe: 'Jump' forward 10 seconds  
 - Stop: Pause the movie

Each video is a sequence of 30 frames (or images).

**Objectives:**

**Generator:** The generator should be able to take a batch of videos as input without any error. Steps like cropping, resizing and normalization should be performed successfully.

**Model:** Develop a model that is able to train without any errors which will be judged on the total number of parameters (as the inference(prediction) time should be less) and the accuracy achieved. As suggested by Snehansu, start training on a small amount of data and then proceed further.

**Write up:** This should contain the detailed procedure followed in choosing the final model. The write up should start with the reason for choosing the base model, then highlight the reasons and metrics taken into consideration to modify and experiment to arrive at the final model.

 
The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use. 

Dataset : https://drive.google.com/file/d/1GPqxmUcp5sQ5NUWAZ9z-_VZFuowYieUJ/view?usp=share_link
          if this is not work can check anotehr link.
          https://drive.google.com/drive/u/0/folders/0By3zAnKFndqVVGpVd01lZnhGUTQ?resourcekey=0-7aorZloI-Ujnp6et64KeXw


### Contributers:
 - [Ajay Mehta & Ayush Saxena](https://github.com/ajay32/Gesture-Recognition-Case-study)

