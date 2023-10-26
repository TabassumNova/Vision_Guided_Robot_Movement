# Vision_Guided_Robot_Movement

<p align="center">
  <img src="Images/rbMotion.png" width="700"/>
 </p>

# View plan tab
 <p align="center">
  <img src="Images/viewPlanTab.png" width="700"/>
 </p>

- Click the ’Directory’ Button: Start by clicking the ’Directory’ button. This
8. Implementation 83
button allows you to select the directory where the images will be saved.
- Find Cameras: Next, click on the ’Find Cameras’ button. This action will reveal
the list of cameras currently available.
- Show Next Image: Press the ’Show Next Image’ button. This will display the
current frames from all connected cameras in the image widget.
- Save Pose: To save the current pose, click the ’Save Pose’ button. This step records
the robot’s current position.
- Home Position: The ’Home Position’ button is used to move the robot’s joints
back to their previously saved angles.
- Choose a Camera: Now, select a camera by clicking the checkbox next to its
name. This selection will generate checkboxes displaying the names of boards that
are detectable in the current frame of the chosen camera.
- Detect Boards: Click on the ’Detect Boards’ button. This action will reveal the
rotation and translation vectors associated with the chosen board.
- Adjust Vectors: You can fine-tune the rotation and translation vectors by clicking
the plus or minus buttons, allowing for precise adjustments.
- Start Motion: After selecting the desired random pose, press the ’Start Motion’
button. If the calculated motion is feasible, the information box will display ”Transformation found,” and the robot will move to the calculated position.
