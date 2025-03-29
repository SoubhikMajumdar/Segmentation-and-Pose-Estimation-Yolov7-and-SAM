* Unzip "CompVision" folder and upload/share to 'My Drive' in google drive. Link: https://drive.google.com/drive/folders/17TKFMhLaWqlZrZvsrkRgnaj7Q8Bx8Rgi?usp=drive_link

* This folder contains video datasets, folders with frames, segmented frames and pose estimated folders for each of 4 dataset videos, the SAM and YOLOV7 models used. 

* Segmentation code: cv_seg_framevideo.ipynb
* Pose estimation code: project_cv_framevideo_poseestimation.ipynb

* The widget used for bounding box during segmentation is designed to work in the google colab environment. cv_imshow is used instead of cv.imshow due to google colab constraints

* Output videos and joint_coordinates.csv for datasets are located in segposeframes, BR_poseframes, BK_poseframes, FL_poseframes (with the output frames after segmentation and pose estimation)

##############################################################################################################################
