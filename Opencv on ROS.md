//2019/03/08 Opencv on ROS
//---在ROS下建立工作空間---

//=====================================================================
//---建立空間---
//建立一個資料夾
mkdir -p cv_ws/src

//進入資料夾內部
cd cv_workspace/src

//建立catkin的workspace
catkin_init_workspace

//建立一個Package
catkin_create_pkg test stdmsgs rospy roscpp
//@路徑需要在 ~/catkinws/src 下
//格式: [指令] [Package名稱] [depend1] [depend2] [depend3]
//支援的函式庫: stdmsgs rospy roscpp



