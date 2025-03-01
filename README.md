# Marching-Band-Drill-Detection

An andvanced tool to help marching bands evyerwhere perform better. This project allows users to enter videos taken on a smartphone camera and turn it into a top down view for better performance analysis. 

# Key Features

- Person Detection
- Keypoint Detection and top down field view
- Accurate Dots for drill analysis

# Person Detection

This project utlizes a fine tuned version of YOLOv8 trained on band specific uniforms for better accuracy. 

**Sample frame:**

![image](https://github.com/user-attachments/assets/12a738a5-04b4-47a2-ad34-7ad724231a12)

**Confusion Matrix:**

![image](https://github.com/user-attachments/assets/87676c82-f47a-4668-86fd-ffae3e35ff94)

# Keypoint Detection:

In order to create a top down view, this project hilights keypoints on the field to use as a base to transform 3D coordinates onto a 2D screen.

**Sample Frame:**

![image](https://github.com/user-attachments/assets/d68f91c9-d0bd-4ffe-95c3-52da9f1afbce)

Through this, a homography matrix can be used to create the 2D field:

**Sample Frame:**
![image](https://github.com/user-attachments/assets/d36fa19e-b6c2-4ffb-8ed7-1244da2daba8)


# Accurate Dots for drill analysis

Combining the aforementioned features nets the end product: a readable 2D map with every dot representing the performers' positions.

**Sample Frame:**

![image](https://github.com/user-attachments/assets/8ab8b998-9021-4f11-aaef-fb9c231a1b6b)
