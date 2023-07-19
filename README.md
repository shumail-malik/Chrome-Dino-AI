Recently I've been learning about Reinforcement learning and it's 
applications in the field of control, mechatronics and gaming. 

It's super fascinating to see how AI learns to play games. My ultimate 
project is to train a deep reinforcement decision making Chess AI which 
definitely isn't easy. It beholds underneath a hell lot of combinatorial complexities of training the right 
depth search game tree.

This project is just a fun project where I push myslef to learn stuffs. 
Currently I've been working on neural CHESS ENGINES and neural TIC TAC TOE 
engine. 

This project aims to serve just some fun. I've used QDN to train my model 
which plays the game of Chrome Dinosaur. The model has been trained on a 
small dataset cause, Oh Please! I'm broke, I don't have a high-end GPU and 
colab crashes when the data is large and the model is complex. 
 

Here is the short clip how the AI performed in the first 2 minutes of training:

![DQN-Dino-ai](https://user-images.githubusercontent.com/92183102/214807424-90bbef3f-e76d-49f2-92ba-d9d3ddc4ea96.gif)

## How was this accomplished? 

I used python library called ```mss``` in order to capture the game's frame like that of the camera. The size of the capture must be hardcoded in order to make it work well on your system. So make some trial and errors and figure out the size and position according to your system. Then there was OpenCV in order to process the frame to crop down the area to the dinosaur and cactus so that the training becomes easier by avoiding the unnecessary pixels. 

I used pyautogui to automate the clicks. pytesseract was used as an optical recognition tool to identify the dinosaur. 

Stable Baseline was used as RL framework. OpenAI gym was used to create the development environment for testing.

And the most important of all: The RL network that was used was **Deep-Q Network** (DQN)!

This was just a hobby project done just for fun :)
