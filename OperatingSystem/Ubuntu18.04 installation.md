You probably need to install ubuntu operating system if you are new here or haven’t used that before. An installation under Virtual Box or Dual System are all accepted, but I recommend you choose the Dual System version. I don’t know why, probably because I am used to it. ^_^
The followings are some items that you may need to install in your new Ubuntu. (May be necessary, it depends on your requirements.)
  1. System version: Ubuntu 18.04
  2. Google Chrome
  3. Sougoupinyin for Linux (only necessary if you need to type Chinese)
  4. some ubuntu packages:
  5. ros-melodic-desktop-full (please follow http://wiki.ros.org/melodic/Installation/Ubuntu)
  6. ros-melodic-mavros* (sudo apt-get install ros-melodic-mavros*)
  7. ros-melodic-vrpn* (sudo apt-get install ros-melodic-vrpn*)
  8. python3-catkin-tools (please follow https://catkin-tools.readthedocs.io/en/latest/installing.html)
  9. some other packages (please follow README.md in https://github.com/HKPolyU-UAV/E2ES)
  10. you may need an editor for coding, VSCode and QT-Creator are recommended, either is ok.
  11. VSCode: sorry, I don’t know, just google, please.
  12. QT-Creator (please follow http://www.4k8k.xyz/article/qq_29923461/119419377, which is a document in Chinese).
Tips: You can edit your code in such editors but compile it in ubuntu terminals. (If you use ROS, ‘catkin_make’ and ‘catkin build’ are both acceptable, but you can only choose one since they are not compatible.)
  13. QGC, the ground station of PX4, you’d better install a stable version 3.5.2 which can be downloaded from internet.
  14. SSH, which is used for controlling and monitoring the onboard computer on UAV. (Please follow https://segmentfault.com/a/1190000022103074, which is a document in Chinese.)

There may be some other software you need to install according to your specific technique requirements. If there is, please add your extra items into this document. By the way, if there is anything wrong in this document, please modify it, thank you very much. Have a nice day~~

YANG Yefeng
Oct. 1, 2021
