a) Perceiver ml model for classification in keras. 
   Image classification with Perceiver on cifar-10 dataset
   Instead of the cifar-100, the cifar-10 dataset is used
   To cut traning time from ~2hours
   - Image classification problem has been reduced to 2 classses
   - 5 epoch training is performed to cut runtime
  
   Observations: After 5 epochs, the Perceiver achieves a 
   - Test accuracy of 
   - Top 5 test accuracy of 

b) Perceiver IO model for masked last word prediction task.
   The task is performed on sample input text
   - Example 1: missing word is masked and predicted 
     Input - This is an incomplete sentence where some words are missing.
     Predict - missing

   - Example 2  
     Input - This is an assignment for deep learning class.  
     Predict - class
   
   Observations: The perceiver IO correctly predicts "missing" 
   for example 1 but incorrectly predicts "class" in example 2.
   