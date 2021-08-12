# Machine-Learning-Project

## Requirements
- Python 3
- Keras
- Tensorflow
- OpenCV

## Set up instructions
1. Install the dependencies
```sh
$ pip install -r requirements.txt
```

2. Gather Images for each gesture (rock, paper and scissors and None):
In this example, we gather 200 images for the "rock" gesture
```sh
$ python3 gather_images.py rock 200
```

3. Train the model
```sh
$ python3 train.py
```

4. Test the model on some images
```sh
$ python3 test.py <path_to_test_image>
```

5. Play the game with your computer!
```sh
$ python3 play.py
```
