Creating a Simple Game with Basic Understanding of Open-CV
How Simple tasks combined to create a visual riddle game with opencv
![image](https://user-images.githubusercontent.com/85643641/204102673-3f0711be-9d1d-4c60-83ea-9a3916ba1f24.png)
in this article we will see how simple tasks provided to me after learning some basic concepts about computer vision, turned out to be a logic based game created in python .for this we would first have to know about the basic concept of computer vision .libraries of python such as numpy ,open cv and other can help us to create a pixel based image and then you can use simple logic to make some animations and by combining these basics we can reach the final results but first lets understand the basics and the challenge.
PYTHON
The Python Package Index (PyPI) hosts thousands of third-party modules for Python. Both Python’s standard library and the community-contributed modules allow for endless possibilities.

Web and Internet Development
Database Access
Desktop GUIs
Scientific & Numeric
Education
Network Programming
Software & Game Development
NUMPY
NumPy arrays have a fixed size at creation, unlike Python lists (which can grow dynamically). Changing the size of an ndarray will create a new array and delete the original.

The elements in a NumPy array are all required to be of the same data type, and thus will be the same size in memory. The exception: one can have arrays of (Python, including NumPy) objects, thereby allowing for arrays of different sized elements.
NumPy arrays facilitate advanced mathematical and other types of operations on large numbers of data. Typically, such operations are executed more efficiently and with less code than is possible using Python’s built-in sequences.
A growing plethora of scientific and mathematical Python-based packages are using NumPy arrays; though these typically support Python-sequence input, they convert such input to NumPy arrays prior to processing, and they often output NumPy arrays. In other words, in order to efficiently use much (perhaps even most) of today’s scientific/mathematical Python-based software, just knowing how to use Python’s built-in sequence types is insufficient — one also needs to know how to use NumPy arrays.
OPEN -CV
OpenCV is the huge open-source library for the computer vision, machine learning, and image processing and now it plays a major role in real-time operation which is very important in today’s systems. By using it, one can process images and videos to identify objects, faces, or even handwriting of a human. When it integrated with various libraries, such as Numpuy, python is capable of processing the OpenCV array structure for analysis. To Identify image pattern and its various features we use vector space and perform mathematical operations on these features.

The first OpenCV version was 1.0. OpenCV is released under a BSD license and hence it’s free for both academic and commercial use. It has C++, C, Python and Java interfaces and supports Windows, Linux, Mac OS, iOS and Android. When OpenCV was designed the main focus was real-time applications for computational efficiency. All things are written in optimized C/C++ to take advantage of multi-core processing.

TASK:
Task Description 📄

📌 Create image by yourself Using Python Code

📌 Take 2 image crop some part of both image and swap it.

📌 Take 2 image and combine it to form single image. For example collage

MY APROACH:
So as the first task states i tried to create my own dinosaur as i wanted to create a google dino game inn future if i can but then i by mistake created a character from a famous tv show “Perry”
![image](https://user-images.githubusercontent.com/85643641/204102716-3ae64614-8008-44c8-9c02-69edc0ab238f.png)![image](https://user-images.githubusercontent.com/85643641/204102728-676cef25-768b-46ce-8a0c-f11c354335f3.png)

Now for the second task i just made some changes in the same image and game a backgroung to the image

also after understanding the concept i gave a little bouncing effect to the original image.

![image](https://user-images.githubusercontent.com/85643641/204102748-ebeb881e-10db-456d-a67d-5893fae7b44e.png)![image](https://user-images.githubusercontent.com/85643641/204102754-7b81c6d2-65ad-46dc-b707-1a2c721dbfe3.png)

Now after understanding some concepts of looping with the cv2 module and after spending a lot of time to create some movement logic i came up with a game based on a game “that level again ”and i created this logic:
LEVEL1



LEVEL1
now this game is based on a moving platipus which can move with keys wasd and to actually solve this game you have to see the hint given on the top of window to win you must press escape five times i wanted it to happen in one press but due to a bug this have to be done 5 times

LEVEL 2


level2
In this level you face a self moving platipus with the hint

“STOP her forcefully but slowly and ask her a question REMEMBER: once gone shall never return”

to win you must press spacebar two times and the moving creature will stop and you will reach in a new room ie the final level

LEVEL 3


level 3
this one is the most easiest yet most diffcuilt level of them all as the solution of this level is not easily understandable or i cam say diffcuilt to remember as the hint was present in the level 2 also in this level you cannot chose a wrong option else you will lose the whole game

the solution to this is toask her a question by pressing the question key on keyboard


final you will know if you won or not
remember keep exploring and small things can turn out to be mesmerising ideas

![image](https://user-images.githubusercontent.com/85643641/204102799-ed6e500c-cbd2-400a-bb4a-eda4af0a5067.png)


