# 20182_cstopics_ConnectFourAI
AI entity who plays connect four in real life using a camera.

project consist of an AI entity who play connect four in real life using a camera (in this case and xbox 360 kinect) to see the game board,  minimax algorithm with alpha beta to pruning and improve the time that the AI entity takes to make their decisions and stepper motor that shows were to put the puzzle when the AI plays.

The theoretical foundation used to develop this project was:
- image filtering 
- morphological transformation
- search trees
- decision treesos
- adversarial search
- minimax algorithm

## how to run:
to run:
python Splay.py 
this program run with an xbox 360 camera with boot drivers  freenect and openNi (see the comments to choose with one you want to use), if you wanna use a normal camera just change the frame for corresponding camera and you're free to go, also you need an arduino with an H bridge to move the stepper motor, look in to  the arduino folder for pins conections of it.
to change the turn between AI and human, you also need an photoelectric sensor (look into arduino folder for more information about the pins connections.)


## the flowchart of the algorithm is :
![image](https://user-images.githubusercontent.com/30030792/49172687-b9ad4700-f30f-11e8-8da1-25f624d3a9fc.png)

## MINIMAX flowchart:

![image](https://user-images.githubusercontent.com/30030792/49173047-9a62e980-f310-11e8-9530-3a1c6aafbf6b.png)

## screenshot of the result program :
![jj](https://user-images.githubusercontent.com/30030792/49173940-0d6d5f80-f313-11e8-82fb-ad2e61b51c9c.JPG)

## screenshot of the AI wining :

![captura](https://user-images.githubusercontent.com/30030792/49174016-3e4d9480-f313-11e8-8eb6-211d4aba013f.JPG)

## photos of the prototype:


![whatsapp image 2018-11-28 at 1 42 23 pm](https://user-images.githubusercontent.com/30030792/49174333-085ce000-f314-11e8-9015-a63dc335d227.jpeg)

![whatsapp image 2018-11-28 at 1 42 15 pm](https://user-images.githubusercontent.com/30030792/49174382-2fb3ad00-f314-11e8-9eea-d46ea70863ad.jpeg)
## youtube video :
https://www.youtube.com/watch?v=abIrOX-Xmjc





