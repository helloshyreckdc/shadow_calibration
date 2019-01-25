# shadow_calibration
first, remember to set the robot TCP to its original position(if you installed gripper and force sensor)
second, don't change robot ee_link to somewhere else, else calibration would fail
camera calibration (set the resolution to highmode)
operation:   rosrun rqt_reconfigure rqt_reconfigure
camera-driver-color_mode SXGA_30Hz


copy the data(rgb) into ~/demo/camera_info



roslaunch shadow_calibration shadow_boardext.launch


rosrun shadow_calibration manual..   x(the number of pictures)

run the rosrun command showing in the gui 


moveit add pointcloud2  registrated 


run tf static_transform_publisher  -1.030309  -1.142459  0.272453  -0.013156  0.058100  -0.474997  -0.877969    /base_link /camera_link 40

