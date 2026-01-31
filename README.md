# Fashion-MNIST-Image-Classification
Laboratory 1

Aurjohn Cris C. Monte BSIT IV

Questions:
1. What is the Fashion MNIST dataset?
   - is a collection of 70,000 \(28\times 28\) grayscale images of 10 fashion categories, designed as a modern, more complex replacement for the original MNIST handwritten digit dataset. Created by Zalando Research, it is   widely used for benchmarking machine learning          algorithms, particularly for image classification, with 60,000 training and 10,000 test images
    
2. Why do we normalize image pixel values before training?
   - It is importan for preprocessing step to enhance model performance, speed up training, and ensure stability.

3. List the layers used in the neural network and their functions.

   - Flatten layer: Converts the 28×28 image into a one-dimensional array.
      Dense (128 neurons, ReLU): Learns important features and patterns from the image.
      Dense (10 neurons): Outputs a score for each of the 10 clothing classes.

4. What does an epoch mean in model training?

   - An epoch represents one complete pass of the entire training dataset through the neural network.
     During each epoch, the model updates its weights to reduce error.
     Training for multiple epochs allows the model to learn patterns more effectively.

5. Compare the predicted label and actual label for the first test image.

   - The predicted label for the first test image matches the actual label, indicating a correct prediction.
     This shows that the trained model is able to correctly classify at least some unseen images.

6. What could be done to improve the model’s accuracy?

   - Add more hidden layers or increase the number of neurons.
     Use a Convolutional Neural Network (CNN) instead of a basic dense network.
     Train for more epochs or tune the learning rate.
     Apply data augmentation to increase training data variety.
