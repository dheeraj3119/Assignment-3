# Assignment-3
Video link:
 https://drive.google.com/file/d/1K5JWpKwS4JIfUjHilQ2-hRUePk8QFADJ/view?usp=sharing
In the previous code provided the code has wrong values (3,32,32), so I have changed to (32,32,3) then the code has executed successfully. 
![image](https://github.com/dheeraj3119/Assignment-3/assets/83443076/692c79ee-3fbf-4da9-863e-390975b74d6a)
![image](https://github.com/dheeraj3119/Assignment-3/assets/83443076/b925a3e6-e29d-4079-8030-0e9ba2b8d315)
![image](https://github.com/dheeraj3119/Assignment-3/assets/83443076/0a36acfc-09d2-4814-9a1a-d680741764a7)
1.	Follow the instruction below and then report how the performance changed.(apply all at once) 
• Convolutional input layer, 32 feature maps with a size of 3×3 and a rectifier activation function.• Dropout layer at 20%. • Convolutional layer, 32 feature maps with a size of 3×3 and a rectifier activation function. • Max Pool layer with size 2×2. • Convolutional layer, 64 feature maps with a size of 3×3 and a rectifier activation function. • Dropout layer at 20%. • Convolutional layer, 64 feature maps with a size of 3×3 and a rectifier activation function. • Max Pool layer with size 2×2. • Convolutional layer, 128 feature maps with a size of 3×3 and a rectifier activation function. • Dropout layer at 20%. • Convolutional layer,128 feature maps with a size of 3×3 and a rectifier activation function. • Max Pool layer with size 2×2. • Flatten layer. • Dropout layer at 20%. • Fully connected layer with 1024 units and a rectifier activation function. • Dropout layer at 20%. • Fully connected layer with 512 units and a rectifieractivation function. • Dropout layer at 20%. • Fully connected output layer with 10 units and a Softmax activation function.

Here we have compiled the model after changing the code with the above changes and fit the model and executed it.
![image](https://github.com/dheeraj3119/Assignment-3/assets/83443076/0f181f3b-f22b-4c17-9b98-7fa82838156d)
Did the performance change?
Here we can see the accuracy has changed from 65.22% to 56.46%. performance has changed.

2.	Predict the first 4 images of the test data using the above model. Then, compare with the actual label for those 4 images to check whether or not the model has predicted correctly
First we have predicted the first 4 images of the test data and then converted the predictions to class labels and then converted the actual labels to class labels and then printed the predicted and actual labels for the first four images.
![image](https://github.com/dheeraj3119/Assignment-3/assets/83443076/182b7bc9-958a-4ee8-a083-4a0e23469ddd)
4.	Visualize Loss and Accuracy using the history object
Here we have plotted the model loss and model accuracy using the above code.
![image](https://github.com/dheeraj3119/Assignment-3/assets/83443076/8684dffa-df0b-46de-9c09-fd2881f2a89e)
![image](https://github.com/dheeraj3119/Assignment-3/assets/83443076/02f41fd7-23fb-46af-a096-1b840dbe1c71)

 
 


