# ENPM661_AStar_Phase_1
A Star Algorithm

Group Members:

117054859 Aditya Varadaraj

118133959 Saurabh Palande

Requirements:

1) Python 3.8 (Since we are using math.dist() for eucledian distance which is available in Python >=3.8)

2) OpenCV (cv2)

3) math

4) numpy

5) matplotlib

Instructions:

1) Download the files into a folder.

2) Run the python file by "python3 Aditya_Varadaraj.py"

3) Enter the user inputs when prompted. (If prompted to re-enter after entering all inputs, then please re-enter some valid coordinates which are not in any obstacles)

4) In the user inputs, steps of 30 in each direction means: For example, if you enter 2, the actionset will be [-60, -30, 0, 30, 60]. If you enter 3, the actionset would be [-90, -60, -30, 0, 30, 60, 90] and so on.

5) Once done, you should see "Goal reached" in the terminal with total cost printed. 
   Then it should print "Path generated using backtracking" after backtracking. 
   Then it should print "Visualization video created".

6) Now, you should see a video file by the name "Astar_visualisation.mp4" in the same directory as the python file. This would be the output showing explored states in yellow and the path in black once done coloring all explored nodes. Obstacles are in red/brown color.

7) You should also have "Final_output.png" that shows only the path in the space and "Obstacle_space.png" that shows the obstacle space with the padding (clearance+radius).

8) Program might finish running in 1-3 mins for a step size of 5. For smaller step sizes like 1, it might take a long time.

