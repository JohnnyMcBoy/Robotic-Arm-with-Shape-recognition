# Robotic-Arm-with-Shape-recognition
This was a project done for the class CEG 4158 (Computer Control in Robotics) in which we were required to determine both the kinematic equation and inverse kinematic equation for a 5 jointed robotic arm.\
\
![1](https://user-images.githubusercontent.com/66148502/122081028-be9e4d00-cdcc-11eb-8c8d-49e1254a231e.PNG)\
\
This robotic arm was controlled using MATLAB and featured two camaras for remote use. Using these cameras, a shape recognition algorithm was developeed to identify four shapes, a: circle, square, rectangle, triangle.\
\
![2](https://user-images.githubusercontent.com/66148502/122081813-6f0c5100-cdcd-11eb-93f0-a5ef0b75ad1c.PNG)
![3](https://user-images.githubusercontent.com/66148502/122081821-716eab00-cdcd-11eb-8e12-fec0bdbc2c83.PNG)\
\
This image processing also determines the position and orientation of the objects.\
\
![4](https://user-images.githubusercontent.com/66148502/122082034-a3800d00-cdcd-11eb-8d2c-60855a6db538.PNG)
![5](https://user-images.githubusercontent.com/66148502/122082040-a4b13a00-cdcd-11eb-9110-803009638fa5.PNG)\
\
These calculations can then be used in the previously developed inverse kinematitc to calculate proper joint movements for the arm to move and pick up the object.
