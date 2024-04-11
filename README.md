# Look the world straight in the eye!
## Camera calibration and Lens distortion correction using OpenCV.


#### 1. 카메라를 이용해 다양한 시점에서 체스보드를 촬영한다. Using the camera, the chessboard is photographed from various points of view.


#### 2. 촬영한 영상을 읽어서 캘리브레이션 한다. (camera_calibration.py) Read and calibrate the video you filmed.


        Space: Pause and show corners  
        Enter: Select the image  
        ESC: Exit (Complete image selection) 

#### Caution!!)  
   You should change it to your

           - board_pattern = (*, * ) # x by y
   
           - board_cellsize = 0.0**  # (**[mm])
![Screenshot 2024-04-01 at 10 06 18 PM](https://github.com/st-min/Look-the-world-straight-in-the-eye/assets/70586865/57668903-216b-41b1-ac6f-0dbe6e057e2a)
                                                        Camera_calibration.py, Result Example)
![image](https://github.com/st-min/Look-the-world-straight-in-the-eye/assets/70586865/19f6701c-ca8d-4cc5-869e-81bc0eb6d2f8)

<br/>
#### 3. 카메라 캘리브레이션 결과를 이용해 렌즈 왜곡 보정 수행한다. (distortion_correction.py)  The lens distortion correction is performed using the camera calibration result.

    보정 결과와 원본 영상을 "Tab"키로 전환할 수 있다.  The correction result and the original image can be switched to the "Tab" key.
    왜곡이 큰 광각 렌즈를 사용하면 변화가 뚜렷하다.With a wide-angle lens with large distortion, the change is evident.
    
#### Rectified) ![Screenshot 2024-04-01 at 11 17 02 PM](https://github.com/st-min/Look-the-world-straight-in-the-eye/assets/70586865/4fca1157-a19f-4adb-bdd4-e1fb8769bd9c)
                                                                        
#### Original)  ![Screenshot 2024-04-01 at 11 16 53 PM](https://github.com/st-min/Look-the-world-straight-in-the-eye/assets/70586865/6ba1fee9-3868-4173-9c8c-146571a348f1)
