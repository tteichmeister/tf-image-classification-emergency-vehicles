# classification of emergency vehicles 

Example with Tensorflow to classify images of emergency vehicles into three classes.
Classes: 
  - fire
  - rescue
  - police
  
We've divided the models into 3 project files. Each project files has it's own model. 

## 1. Project 1

Findings & Test: 
* we are not that good in differentiate betwee fire and rescue cars but good in classify the police cars 
* by decreasing the batch size we got worse results (accuracy)

## 2. Project 2

Findings & Tests:
* we decreased the count of filters used
* by decreasing the batch size we got the best results with smaller batch size(16) (accuracy)

## 3. Project 3
Findings & Tests:
* we used a RESNET (many layers)
* by using the loss and accuracy we find out that the model would need a bigger batch size and more training samples
