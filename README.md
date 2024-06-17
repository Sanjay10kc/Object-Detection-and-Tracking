# Object Detection and Tracking On Robot
This project introduces a novel robotic navigation system that combines Visual Simultaneous Localization and Mapping (SLAM) for real-time object detection and tracking with Model Predictive Control (MPC) for precise robot control. Leveraging advanced computer vision techniques, the Visual SLAM component constructs a dynamic map of the environment while accurately estimating the robot’s pose. This enables the robot to detect and track objects, essential for navigating through dynamic and challenging surroundings. The integration of MPC as the control framework optimizes the robot’s decision-making process by considering both current sensor data and predictions of future states. The result is a seamless fusion of perception and control, ensuring the robot can navigate dynamically changing environments, avoid obstacles, and plan ahead for more complex scenarios.


## How to work with RGB-D camera?
- Follow the installation of Orbbec SDK from [here](https://dl.orbbec3d.com/dist/orbbecsdk/ROS2/v1.2.5/OrbbecSDK_ROS2_v1.2.5_20230511_4476995_release.zip).
- Launch the camera node using the code `ros2 launch orbbec_camera astra.launch.xml`.
- Then run the **video_publisher** node and choose RGB-D camera using code `2`.
