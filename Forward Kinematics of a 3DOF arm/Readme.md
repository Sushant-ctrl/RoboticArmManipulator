# Forward Kinematics Calculator

Forward kinematics refers to process of obtaining position and velocity of end effector, given the known joint angles and angular velocities.

### Transforming the equations
  We use transformation matrices to transform points with given conditions along position and orientation. These taransformations include translation and rotation matrices.
  The matrices used are called homogeneous transrformation matrices. To get a mathematical insight click [here.](http://planning.cs.uiuc.edu/node111.html)

### DH Parameters

DENAVIT-HARTENBERG parameters are the minimal representation of the link positions and orientations. They consist of 4 parameters. These 4 parameters are sufficient to know the state of any link in the arm. 

To read more on DH parameteres refer the slides of Introduction to Robotics, Stanford 
* [Lectures 1-3](https://see.stanford.edu/materials/aiircs223a/handout2_Kinematics-1.pdf)
* [Lectures 4-5](https://see.stanford.edu/materials/aiircs223a/handout3_Kinematics-2.pdf)

### Simulations

I have tried simulating 3 dof RRR arm using transformation matrices. Velocities were NOT calculated

> DH parameters were NOT used for this simulation

### Results

###### 3 Dof arm in 3D space
![](https://i.imgur.com/T9BGGzE.gif)

###### 3 Dof arm in 3D space
![](https://i.imgur.com/YzANfL2.gif)
