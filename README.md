The PPM algorithm is an algorithm for multi-camera pedestrian detection. The code and demonstration videos of the PPM algorithm, as well as the PETS2009 ground truth data created by us and used in the following article, are provided here. The PPM algorithm is presented in the article: Rui Qiu, Ming Xu, Yuyao Yan, Jeremy S. Smith, Yuchen Ling,  PPM: A Boolean Optimizer for Data Association in Multi-View Pedestrian Detection, Pattern Recognition, Article NUmber 110807.

This program is a x64 program and developed by using Microsoft Visual Studio 2017 (v141) and opencv 2.4.13.

In the PPM code folder, main.cpp is the program's main file, starting from this file in Microsoft Visual Studio.

gt_terrace.txt is the ground truth file of EPFL Terrace dataset. Please refer to the official website for specific instructions on this document. https://www.epfl.ch/labs/cvlab/data/data-pom-index-php/

Terrace_ms_5000.txt contains the results of Mask Scoring RCNN detection of pedestrians for the Terrace dataset. Each detection of pedestrian is recorded as a row in this file.
The columns in Terrace_ms_5000.txt are defined as follows:

1st column:  frame number
2nd column:  camera number.
3rd column:  x coordinate of the top left corner of the bounding box.
4th column:  y coordinate of the top left corner of the bounding box.
5th column:  the width of the bounding box.
6th column:  the height of the bounding box.
7th column:  the slope of the fitting line of a pedestrian mask.
8th column:  the intercept of the fitting line of the pedestrian mask.
9th column:  x coordinate of the highest point of the pedestrian mask
10th column: y coordinate of the highest point of the pedestrian mask

If you need to run the program on a new dataset, please refer to this format to generate the file. For further enquiry, please contact: ming.xu@xjtlu.edu.cn.
