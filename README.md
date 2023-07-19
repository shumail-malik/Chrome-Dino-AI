This project is done in summers to get a better understanding of Reinforcement Learning.

![DQN-Dino-ai](https://user-images.githubusercontent.com/92183102/214807424-90bbef3f-e76d-49f2-92ba-d9d3ddc4ea96.gif)

## How was this accomplished? 

I used python library called ```mss``` in order to capture the game's frame like that of the camera. The size of the capture must be hardcoded in order to make it work well on your system. So make some trial and errors and figure out the size and position according to your system. Then there was OpenCV in order to process the frame to crop down the area to the dinosaur and cactus so that the training becomes easier by avoiding the unnecessary pixels. 

I used pyautogui to automate the clicks. pytesseract was used as an optical recognition tool to identify the dinosaur. 

Stable Baseline was used as RL framework. OpenAI gym was used to create the development environment for testing.

And the most important of all: The RL network that was used was **Deep-Q Network** (DQN)!

This was just a hobby project done just for fun :)
