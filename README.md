# Finding-Waldo-Puzzle-OpenCV
Solving the classic "Finding Waldo" puzzle using simple template matching feature of OpenCV.

# Usage:
Given the following image of a classic "Finding Waldo" puzzle
![Find Waldo](/find_waldo.jpg)

We have to find Waldo in this
![Waldo template](/Images/waldo.jpg)

After using the python script with template matching the final image would appear like this(look in the top right area of the image where there is a green rectangle)
![Found Waldo](/Images/found_waldo.jpg)


**NOTE**: Use the ```"waldo.png"``` image in the python script for template. Ignore the ```".jpg"``` files inside Images folder, they are just for representation purpose.

# Additional Comments:
Try it out on different "Finding Waldo/Where's Waldo" images available on the internet.

There is one drawback though, simple template matching cannot be operated on rotated images, flipped images or images in any other orientation. Working on a better solution using Deep Learning concepts in order to eliminate this drawback and will share it as soon as possible.
