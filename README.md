# Air Painting Canvas

This program lets you *draw* on a blank canvas using your fingers. You can use any color and also erase your drawings in real time. It's called Air Canvas and it  can draw anything on it by just capturing the motion of a colored marker with a camera. Here a colored object at the tip of the finger is used as the marker.<br>

Novelty: <br>
1. The most difficult task during Covid times was education. Not everyone had access to touch laptops or drawing pads/pens. This program will let users/teachers draw using their finger and with different inks too. 
2. It helps students understand better than on BlackBoard using camera. 

<br>
Methodology: <br>
1. The incoming image from the webcam is to be converted to the HSV colour space for detecting the colored object at the tip of finger.<br>
2. Center position for drawing the line is located. <br>
3. The Line is drawn using the position of Contour.<br>
4. Points are drawn.<br>
