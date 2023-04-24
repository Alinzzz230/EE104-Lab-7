Name: Andrew Lin
Class: EE 104
Demonstration Link: https://youtu.be/qUihdsu9c88 
https://youtu.be/XswnN_LGtwk 
Reference: https://sjsu.instructure.com/courses/1559910/modules 


Here is the process to begin the object recognition through YOLOv8. 
To create a custom object recognition, you will need to first prepare the dataset through gathering images containing your custom classes and annotating them using any of the online tools available. Ensuring a balanced dataset will avoid any biases towards any specific classes and you can split the data into training file and a validation file for your program Next step is to preprocess and convert these annotations into the YOLO format and organize them into the structure required by YOLOv8. Create a ‘.yaml’ file that specifics the dataset’s directory, classes, and class names. The longest step is to train the model with the custom dataset and you will need to monitor the training to ensure no overfitting or underfitting occurs. To determine accuracy, use the validation set to determine whether the program can accurately identify the object. Lastly, use the trained model to recognize new objects and videos to determine whether it is accurate and ready to be used. 


Here is the process to begin to create the basic Balloon Flight game. 
To create this custom python game, we need to first ensure that we have installed Python and the necessary libraries such as Pygame and Pygame Zero. We will then create the python file for our game, you can name it anything you want but I have it named as balloon.py. We will then download the necessary game files such as the game images which includes the background, balloon, bird, house, and the tree as the default images. These files all need to be saved in an images file that the python code can access. To run the game, we will just click run on python then we will be start the game as an air balloon and either a bird, house, or tree will come towards your balloon. Your job is to dodge these obstacles and survive and get the highest score you can get. To dodge, click the left mouse button and it will make the air balloon rise and it will slowly descend. The game ends when you lose all your lives and the high score will be displayed on the end screen with your last 3 highest scores.