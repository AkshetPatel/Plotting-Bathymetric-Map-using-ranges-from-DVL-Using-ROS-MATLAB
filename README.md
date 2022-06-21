# Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB

## Problem Statement: 
Software development of Bathymetric Map generation using ranges from Doppler Velocity Log for C-Bot

### Developed by
Mr. Akshet Bharat Patel <br>
B. Tech, Mechatronics Engineering, Manipal University Jaipur, Rajasthan. <br>

### Under the guidance of
Mrs. Nagvekar M Surekha, Principal Technical Officer, Marine Instrumentation Division <br>
Mr. Pramod Maurya, Principal Scientist, Marine Instrumentation Division <br>
Dr Raja Rout, Assistant Professor, Manipal University Jaipur <br>

![](https://github.com/AkshetPatel/Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB/blob/main/img/logo.jpeg) <br>
NATIONAL INSTITUTE OF OCEANOGRAPHY <br>
Dona Paula, Goa-403 004, INDIA <br>
Period: 1st December 2021 to 31st January 2022 <br>

### Aims and Objectives
#### The aim and objectives for the project titled “Software development of Bathymetric Map generation using ranges from Doppler Velocity Log for C-Bot” are:
1. To plot the bathymetric map of the seabed using the data captured by the Doppler Velocity Log (DVL)
2. To Develop an algorithm for the correction of roll, pitch, and yaw motion of the beams of the DVL
3. To simulate the algorithm and code on ‘uuvsimulator’ (A Gazebo-based package for underwater intervention and multi-robot simulation)
4. To validate the results using Rviz (A 3D visualization tool for ROS applications)
5. To create a ROS package using Python Programming Language. <br>

### Methodology
Since the research work is unpublished, the detailed methodology cannot be revealed. The steps involved in the metholodgy are:
1. Geometrical Representation
2. Algorithm of the Code
3. Running the uuvsimulator
4. Plotting the Bathymetric Map using MATLAB
5. MATLAB Code

### Results and Discussions
After implementing the python code for calculating the adjusted values of the beams of the DVL, the points were visualised using the Rviz which is a 3d visualization tool for ROS applications. It provides a view of your robot model, capture sensor information from robot sensors, and replay captured data. It can display data from camera, lasers, from 3D and 2D devices including pictures and point clouds. <br>
For visualising the results, the Rexrov was teleoperated over the sand dunes of the seabed and visualised using Rviz. The results are shown below:
![](https://github.com/AkshetPatel/Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB/blob/main/img/Results.jpeg) <br>
Result of the simulation on Rviz <br>

![](https://github.com/AkshetPatel/Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB/blob/main/img/3D%20Coordinates.jpg) <br>
3D Plot of the Bathy Lines <br>

![](https://github.com/AkshetPatel/Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB/blob/main/img/NON%20Interpolated%20Mesh.jpg) <br>
Mesh Plot of Original Coordinates <br>

![](https://github.com/AkshetPatel/Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB/blob/main/img/Interpolated%20Surface.jpg) <br>
Surface Plot of Interpolated Coordinates <br>

![](https://github.com/AkshetPatel/Plotting-Bathymetric-Map-using-ranges-from-DVL-Using-ROS-MATLAB/blob/main/img/Interpolated%20Mesh.jpg) <br>
Mesh Plot of the interpolated coordinates <br>

### Conclusion
Hence by implementing the Linear Velocity Transformation matrix denoted by 𝑱𝟏(𝜼𝟐), the bathymetric map of the seabed can be calculated by adjusting the roll, pitch, and yaw motion of the vehicle and can be visualised using Rviz. The data extracted from the DVL is then saved to a .csv file from the .bag file and imported into MATLAB for plotting the bathymetry maps of the seabed. <br>