# Go_Chase_It
design my mobile robot & write nodes to chasing the ball

In this project, the mobile robot is modeled with URDF.

drive_bot node provides a service to drive the robot by setting its linear x and angular zvelocities.

process_img node subscribe to the robot's camera images and analyze them to determine the position of the white ball.

