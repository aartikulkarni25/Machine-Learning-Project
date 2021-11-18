# Machine-Learning-Project

## Requirements
  Anaconda3
  Python3
  Keras
  Tensorflow
  
## Steps
stpe 0- Create env variable

	$ conda create -n game python=3.6 (copy this command and past it in the git bash)
	$ conda activate game (copy this command and past it in the git bash)

step 1- Install the dependencies

	$ pip install -r rerequirements.txt (copy this command and past it in the git bash)

step 2- Collecting test images
	
	Gather Images for each gesture 
 
	"""Script to gather data images with a particular label.

	Usage: python gather_images.py <label_name> <num_samples>

	The script will collect <num_samples> number of images and store them
	in its own directory.

	Only the portion of the image within the box displayed
	will be captured and stored.

	Press 'a' to start/pause the image collecting process.
	Press 'q' to quit."""
 
	1)For rock
	
	$ python gather_images.py rock 200 (copy this command and past it in the git bash)

	2)For paper
	
	$ python gather_images.py paper 200 (copy this command and past it in the git bash)
	
	3)For scissors
	
	$ python gather_images.py scissors 200 (copy this command and past it in the git bash)

	4)For none
	
	$ python gather_images.py none 200 (copy this command and past it in the git bash)

step 4- Train the model

	$ python train.py (copy this command and past it in the git bash)
	
step 5-Test the model on some images

	$ python test.py <path_to_test_image> (copy this command and past it in the git bash)

	(Ex. <path_to_test_image>-->C:\Users\ashte\rock-paper-scissors\image_data\paper\2.jpg)

step 6-Play the game with your machine:)

	$ python play.py
	
## Kaggle link
https://www.kaggle.com/ihelon/rock-paper-scissors-agents-comparison
