# shadow_calibration
camera calibration (set the resolution to highmode)
operation:   rosrun rqt_reconfigure rqt_reconfigure
camera-driver-color_mode SXGA_30Hz


copy the data(rgb) into ~/demo/camera_info



roslaunch shadow_calibration shadow_boardext.launch


rosrun shadow_calibration manual..   x(the number of pictures)

run the rosrun command showing in the gui 


moveit add pointcloud2  registrated 

rosrun tf static_transform_publisher  -1.072694  -0.956061  0.220491  -0.014582  0.059231  -0.485862  -0.871905    /base_link /camera_link 40

