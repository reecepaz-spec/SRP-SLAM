# SRP-SLAM
This summer, my research project focuses on programming a TELLO drone by AI. The SLAM program allows the drone camera to detect its surroundings and create a virtual map (assuming that GPS cannot be used). This code is based on this program by MATLAB: https://www.mathworks.com/help/vision/ug/performant-and-deployable-monocular-visual-slam.html.
Out of all of the work I did during the research program, this is the most challenging part primarily because in order for SLAM to function properly, the camera must face a detailed environment (like a cluttered desk or a pile of cardboard boxes), otherwise the graph will not detect anything.
The work presented are scripts I created through MATLAB and Python. To run the MATLAB program provided, download the ".m" and the calibration (.mat) files. The Webcam programs were run through a Logitech C310 Camera; a new calibration file would be required for other webcams.
In MATLAB, the main issue is that the if the camera does not detect a detailed area first, then the graph will not run, even if the camera stopped detecting that. In rare cases, the camera would "jump" at a long distance as shown in the image below


