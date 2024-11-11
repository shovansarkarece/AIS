# Camera-LIDAR Object Detection and Distance Estimation with Application in Collision Avoidance System

- **Abstract**
This paper presents a Collision Avoidance System (CAS) that integrates data from both camera and LIDAR sensors to detect obstacles directly in front of vehicles and estimate their distances.
The camera is utilized for object detection and classification, while the LIDAR sensor provides essential 3D data for accurate distance measurements.
A spatial calibration technique is applied to align the 3D data from LIDAR with the 2D images captured by the camera.
The proposed solution was developed as a prototype using the ROS-based Autoware platform and tested in the CARLA simulator, yielding satisfactory real-time processing results across various weather conditions.


- **Introduction**
The introduction underscores the significance of CAS in enhancing the safety of autonomous driving systems, which are crucial for preventing frontal collisions.
It points out that modern vehicles increasingly incorporate CAS, which is vital for achieving high safety ratings, such as the Euro NCAP five-star rating.
The introduction discusses the various types of sensors employed in CAS, including cameras, LIDAR, and radar, while addressing the challenges associated with sensor fusion and the necessity for precise object detection and rapid processing.
It highlights that although deep learning and CNNs have advanced 2D object detection, accurately determining the 3D positions of detected objects remains a challenge, thus necessitating the use of LIDAR for reliable spatial data.


- **Conclusion**
The conclusion emphasizes the success of the proposed algorithm, which effectively combines camera and LIDAR data to accurately assess the distance to obstacles.
It acknowledges certain limitations, such as the algorithm's reliance on camera detection and the requirement for precise time synchronization between the sensor outputs.
The paper notes that the algorithm can process data from different sensors in real-time and has demonstrated a high success rate in distance estimation.
Additionally, it mentions that while LIDAR is a costly sensor, it offers precise positional information and performs well under most weather conditions, although its effectiveness may diminish in severe weather scenarios like snow and fog.
