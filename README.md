# Your names.
Matt Kaiser, Kevin Flynn, Tanner Quigley

# What your goal is (i.e. what problem you are trying to solve).
The goal of our project was to give feedback on if you are doing a correct pushup or not. Our reasoning behind this was that there are many variations of what a good pushup looks like, but it can be hard to fully know how exactly it works. We decided to measure the proper acceleration and angle that a user does a pushup and use these factors to train our time warping data. 

# How you approached the problem, including
We approached this problem by using a microbit and attaching it to a belt that goes around your chest. The microbit sends input xyz accelerometer input data and is trained with good pushups and bad pushups. Since we only used one microbit, it was difficult on deciding what exactly we wanted to measure and how we wanted to do it. Overall we went with the angle of the pushup, as well as the acceleration that the pushup is done.

# Sensors used
We used one microbit with the xyz accelerometer data. This allowed us to see the angle that the user was doing the push up, as well as how fast they were doing it.

# Feature extractor approach (if you tried several ways to do this, document your work)
In order to record our process, we used processing for both our input and output. The was the microbit example from Kadenze and then we coded our own output to show whether your pushup was good or not.

# ML model structure - what you did and why, including results from experiments you tried along the way
Our model structure that we used was Dynamic Time Warping. We were able to get a percentage of how close our pushup is to a well trained pushup or how close it is to a poorly trained pushup. In order to get the outputs to properly trigger, we had to lower our threshold about halfway in wekinator.

# Ideas about how other might improve upon your work
In order to improve upon our work, we could add more microbits to get more training data. This would allow us to determine a more successful pushup. Any other hardware added would greatly improve this accuracy.

# A link to a demo video
https://youtu.be/Hs0ud9kMwpk
