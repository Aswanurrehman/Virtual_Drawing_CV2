# Virtual_Drawing_CV2
This project is about using openCV and mediapipe libraries   to utilize the webcamera for drawing in real time.   
The main idea is:   
* detect hands using mediapipe
* detect wheither the index and middle fingers are up
* detect fingers' tip location
* draw a line when only the index finger is up and make a sellection when both index and middle fingers are up
* draw on a black canvas then mask it with actual frame


# Installation
There are some prerequisites that are needed to be done to be able to run this project.
It's needed to install the required libraries by running the following commend in the project's directory:
```bash
pip install -r requirements
```
now you can run the project directly from your terminal:
```bash
python main.py
```
If everything has gone right, a window will  pop up as in the below figure:
<br><br>
<img src="images\Screenshot (24).png">
<br><br>

**some more pics**

demo of drawing
<br><br>
<img src="images\Screenshot (25).png">
<br><br>

demo of drawing with hand gesture
<br><br>
<img src="images\Screenshot (26).png">
<br><br>