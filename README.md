# Visage AI
'Visage AI' -Real Time Face Recognition and Classroom Attendance Monitoring using Deep Learning.Group project done in B.Tech Second Year 4th Semester(Mar 2023 - Jun 2023)
## Description
Proposal of an automated student attendance system based on face recognition. In our proposed approach,video framing is performed by activating the camera through a user-friendly interface.The face ROI is detected and segmented from the video frame by using Viola-Jones algorithm.
In the pre-processing stage,scaling of the size of images is performed,to prevent loss of information.The median filtering is applied to remove noise followed by conversion of colour images to grayscale images,contrast-limited adaptive histogram equalization(CLAHE) is implemented on images to enhance the contrast of images.
In face recognition stage,enhanced local binary pattern(LBP) and principal component analysis (PCA) is applied correspondingly in order to extract the features from facial images.
The features extracted from the test images are compared with the features extracted from the training images.Finally,the attendance of the recognized student will be marked and saved in the excel file.
