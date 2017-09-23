# shadow_calibration
camera calibration (set the resolution to highmode)
operation:   rosrun rqt_reconfigure rqt_reconfigure
camera-driver-color_mode SXGA_30Hz


copy the data(rgb) into ~/demo/camera_info



roslaunch shadow_calibration shadow_boardext.launch


rosrun shadow_calibration manual..   x(the number of pictures)

run the rosrun command showing in the gui 


moveit add pointcloud2  registrated 


rosrun tf static_transform_publisher  -1.082850  -0.914359  0.264033  -0.023216  0.043897  -0.477889  -0.877016    /base_link /camera_link 40

