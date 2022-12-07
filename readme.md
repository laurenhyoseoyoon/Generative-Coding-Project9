# A9: Hand Tracking
(NOTE: Under the approval of professor, I aimed to develop a face/emotion-tracking system.)

## Your name
Lauren Hyoseo Yoon


## Your link
[LINK](https://laurenhyoseoyoon.github.io/Generative-Coding-Project9/)


## Describe the experience you designed
The experience that I designed is the face-emotion tracking system. By training the face that you would classify as Positive, Negative, Surprised, the system will predict what emotion you are currently expressing. 


## For each facial expression it responds to, what does it do?
For each facial expression that you provide, the dynamic slide bar in the ride bar under Positive, Negative, Surprised will show the percentage of classification certainty. 


## How are you visualizing or changing graphics with the gesture?
Contingent to the above question, the changing graphics/visualization with the gesture is the dynamic slide bar in the right that yields the classification certaintly level. 


## What gestures mentioned in the Lingthusiasm podcast are related to your gestures?
Since this project is modified for facial expression trackign system, the gestures that I am aiming to deal with are not directly related to the hand gestures/sign languages mentioned in the Linghusiasm podcast. However, facial expressions are still one of the integral components for communication and story-telling; and in this regard, the system incorporates the key components of the meaning/effectiveness behind gestures mentioned in the Linghusiasm podcast. 


## How long did it take to train your network?
For 60 counts of training data (20 for each Positive, Negative, Surprised), the network took approximately 50 seconds for training. 


## Which gestures did it guess wrong and when? What could have improved that training data?
The expressions that the system confused the most were between surprised and positive. In order to improve this, (1) I would incorporate more training data, and (2) modify the machine learning algorithm that can also specifically add more weights on mouth area which are one of the essential face parts that can 


## How long did it take to train the network with the Teachable Machine pixel-based approach?
For 60 counts of training data (20 for each Positive, Negative, Surprised), below 30 seconds for training. 


## How did the quality of predictions compare between them?
The quality of predictions were nearly identical. Yet, the Teachable Machine could not correctly detect the Negative emotion accurately compared to the system I developed. 


## How did the quality of predictions on Teachable Machine change when you changed the background or lighting?
The predictions on Teachable Machine did not change significantly when background/lighting changed. 


## RESOURCES
- https://www.npmjs.com/package/clmtrackr
