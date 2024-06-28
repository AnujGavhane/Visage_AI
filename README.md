# PBL4-SY-SEM4
'Visage AI' -Real Time Face Recognition and Classroom Attendance Monitoring using Deep Learning.Group project done in B.Tech Second Year 4th Semester(Mar 2023 - Jun 2023)
## Description
Proposal of an automated student attendance systembased on face recognition. In our proposed approach,video framing is performed by activating the camerathrough a user- friendly interface.The face ROI is detectedand segmented from the video frame by using Viola-Jonesalgorithm.
In the pre-processing stage,scaling of the size of imagesis performed,to prevent loss of information.The medianfi ltering is applied to remove noise followed byconversion of colour images to grayscaleimages,contrast-limited adaptive histogram equalization(CLAHE) is implemented on images to enhance thecontrast of images.
In face recognition stage,enhanced local binary pattern(LBP) and principal component analysis (PCA) is appliedcorrespondingly in order to extract the features fromfacial images.
The features extracted from the test images arecompared with the features extracted from the trainingimages.Finally,the attendance of the recognized studentwill be marked and saved in the excel file.
