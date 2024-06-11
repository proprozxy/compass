# ROS Usage

**initialize**

```bash
source /opt/ros/noetic/setup.bash
```

```bash
roscore
```

open another terminal to run following tasks

**load config**

```bash
rviz -d rviz_config.rviz 
```

**play rosbag in loop**

```bash
rosbag play --loop /path/to/bag/file.bag
```

**check info**

```bash
rosbag info /path/to/bag/file.bag 
```

**print topic info**

```bash
rostopic echo /topic_name
```

**record**

```bash
rosbag record -a -b 9086 --duration 30
```

`-a` means record all, `-b 9086` is to set buffer size, `--duration 30` means last 30 seconds



