# More projects in the robotics team

This document lists other projects I have worked on as a member of my university robotics team. 

## 1) ROS2 camera PointCloud2 pipeline — package adaptation, transforms & URDF integration

What I did:

- Searched for and adapted the ROS2 package provided by the camera manufacturer to ensure the driver node correctly published a `sensor_msgs/PointCloud2` topic from the depth data.

- Created a custom subscriber node that:

    - Received the PointCloud2 message

    - Applied a spatial transform to align the cloud with the robot’s frame tree

    - Applied a height-based filtering step to separate objects from the field surface

- Added the camera model to the robot’s URDF, specifying its real mounting pose on the robot.

## 2) ROS2 LIDAR package — investigation & documentation

What I did:

- Searched for the ROS2 package supplied by the LiDAR manufacturer.
- Investigated how to use it.
- Wrote a README explaining how to launch the driver and use the published data, enabling teammates to integrate the LiDAR output into their modules.
  
## 3) Team public pages via Jupyter Notebooks + GitHub Pages

A secondary task for the team is to use Jupyter Notebooks together with GitHub Pages to publish documentation and project information. This workflow makes technical content publicly accessible without requiring manual repository setup or repeated explanations.
