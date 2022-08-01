What is object tracking?

Object tracking is one such application of computer vision where an object is detected in a video, otherwise interpreted as a set of frames, and the object’s trajectory is estimated. For instance, you have a video of a baseball match, and you want to track the ball’s location constantly throughout the video. Object tracking is the method of tracking the ball’s location across the screen in real-time by estimating its trajectory.
 


https://user-images.githubusercontent.com/98385786/182181844-42bd55fb-0a04-419d-8e19-ea3ecca9ffbd.mp4



Environment
I have tested on Ubuntu 16.04/18.04.

Ubuntu 16.04 / 18.04

python 2.7 / 3.6

opencv 3.4/4.6


Goal

We will learn about the Meanshift and Camshift algorithms to track objects in videos.

Meanshift

Mean shift is a non-parametric feature-space analysis technique, a so-called mode seeking algorithm. It is a procedure for locating the maxima of a density function given discrete data sampled from that function. In a sense, it is using a non-parametric density gradient estimation. It is useful for detecting the modes of this density.

![meanshift](https://user-images.githubusercontent.com/98385786/182184125-cb6e8a4b-d853-4f86-aa3f-b2ea3787a091.png)


 Camshift
 
The CAMShift algorithm derived from the mean shift algorithm, which is responsible for finding the centre of the probability distribution of the object to track. The main difference is that CAMShift adjusts itself to the search window size, for example when object sizes are changing as they move closer to or farther from the camera.








 










 
