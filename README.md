# CSCI 5551 - Intro to Intelligent Robotic Systems
This is my final project report for CSCI 5551 taken in Fall 2023.

## Summary
For this project, I combined an uderwater image enhancement algorith with the ORB-SLAM 3 visual SLAM library. I observed a significant increase in the number of feature matches running the enhanced image set compared to the baseline, unenhanced image set. I also noticed a decrease in the number of incorrect feature matches.

## Abstract
In recent years, visual Simultaneous Localization and Mapping (SLAM) methods have shown significant 
performance, accuracy, and efficiency in autonomous robotic navigation. Research has demonstrated that 
visual SLAM is capable of outperforming traditional methods of navigation with lower cost. Recently, 
research has been done on the use of visual SLAM for use by autonomous underwater vehicles (AUVs). 
The highly unstructured and uncertain nature of underwater environments presents several challenges for 
robotic navigation, such as low contrast and color distortion. This work investigates the effects of real-time underwater image enhancement on visual SLAM methods for use in AUVs. This work combines 
DeepSeeColor, a novel underwater image enhancement method, with a popular visual SLAM method, 
ORB-SLAM3. It is hypothesized that the number of features will increase in the enhanced images, 
resulting in a more accurate, robust SLAM method. The results of this work may lead to improved 
navigation for AUVs in unstructured underwater environments.
