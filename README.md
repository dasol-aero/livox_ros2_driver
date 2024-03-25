# Livox ROS2 Driver

Click to see the original [README.md](./README_ORIGINAL.md)

---

- **[Prerequisite: Livox-SDK2](https://github.com/dasol-aero/Livox-SDK2)**

- **[Prerequisite: Livox ROS Driver2](https://github.com/dasol-aero/livox_ros_driver2)**

- **Build**

  ```bash
  # clone
  mkdir -p ~/ws_livox_ros2_driver/src/
  cd ~/ws_livox_ros2_driver/src/
  git clone https://github.com/dasol-aero/livox_ros2_driver.git

  # source
  source /opt/ros/humble/setup.bash                       # ROS2 humble
  source ~/ws_livox_ros_driver2/install/local_setup.bash  # livox_ros_driver2 (for CustomMsg.msg)

  # build
  cd ~/ws_livox_ros2_driver/
  colcon build
  ```

- **bashrc**

  ```bash
  source ~/ws_livox_ros2_driver/install/local_setup.bash  # MID-70 / AVIA
  ```

---
