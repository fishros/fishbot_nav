<!--
 * @作者: 小鱼
 * @公众号: 鱼香ROS
 * @QQ交流群: 2642868461
 * @描述: README
-->
# FishBot机器人导航&建图上位机源码



## 1.介绍

## 支持机器人平台

### FishBot二驱机器人

### FishBot四驱机器人


## 2.安装运行

### 2.1 下载编译


```
git clone --recursive https://github.com/fishros/fishbot_nav.git -b $ROS_DISTRO
cd fishbot_nav
sudo apt install ros-$ROS_DISTRO-nav2-bringup ros-$ROS_DISTRO-joint-state-publisher ros-$ROS_DISTRO-robot-state-publisher
colcon build
```

#### Nav2
```
source install/setup.bash
ros2 launch fishbot_navigation2 navigation2.launch.py use_sim_time:=False
```

## 作者
- [鱼香ROS](https://fishros.com)-小鱼
