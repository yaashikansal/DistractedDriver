### Distracted Driver Detection
In this competition you are given driver images, each taken in a car with a driver doing something in the car (texting, eating, talking on the phone, makeup, reaching behind, etc). Your goal is to predict the likelihood of what the driver is doing in each picture.

![sampleGif](https://storage.googleapis.com/kaggle-competitions/kaggle/5048/media/output_DEb8oT.gif)

The 10 classes to predict are:

c0: safe driving
c1: texting - right
c2: talking on the phone - right
c3: texting - left
c4: talking on the phone - left
c5: operating the radio
c6: drinking
c7: reaching behind
c8: hair and makeup
c9: talking to passenger

To ensure that this is a computer vision problem, we have removed metadata such as creation dates. The train and test data are split on the drivers, such that one driver can only appear on either train or test set. 

To discourage hand labeling, we have supplemented the test dataset with some images that are resized. These processed images are ignored and don't count towards your score.

Disclaimer: State Farm set up these experiments in a controlled environment - a truck dragging the car around on the streets - so these "drivers" weren't really driving. 
