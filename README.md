## Eye-Gaze-Tracking <br>

### Purpose
The project allows you to track your eye gaze based on pupils on the available screen. Along with it a head tracking is also available. It can also detect your closed eyes.
This code runs for real time web cam but can be changed to work on saved pictures and videos also.
<br>

Note: Flip the frames for accurate right and left results. <br> <br>

### Approach Used
1. <ins> Head Tracking </ins>
* A landmark located on the nose from face mesh is drawn into the screen.
* Accurate head pose estimation for directions: up, down, left, right and forward wrt the screen.

2. <ins> Eye Tracking </ins>
* Landmarks for the left and right eye located separately.
* A horizontal and vertical line drawn on bith eyes to get ratio for further calculation such as blink possibility.

3. <ins> Gaze Tracking </ins>
* When the eyes are open, the landmarks for pupil are located.
* A line from the pupil is drawn into the screen.
<br> <br>

### Screenshot reference
<img src= 'https://github.com/kirtiitt/Eye-Gaze-Tracking/assets/137528591/2e58c12a-9bfb-4f04-97ae-0d0ad5105d8f' width= '500' height= '400'>
<br> <br>
<img src= 'https://github.com/kirtiitt/Eye-Gaze-Tracking/assets/137528591/10d9ebf2-3060-4528-9ec1-bc3e9b073f20' width= '500' height= '400'>
