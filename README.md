# ROS 2 CI/CD

[![ros2-pipeline-test](https://github.com/JaisalJain/ros2_ci_cd/actions/workflows/main.yml/badge.svg)](https://github.com/JaisalJain/ros2_ci_cd/actions/workflows/main.yml)

ROS 2 package demonstrating GitHub Actions based CI/CD.

## Build

```bash
colcon build --packages-select ros2_ci_cd

```

### Run

terminal 1:

```bash
ros2 run ros2_ci_cd string_publisher
```

terminal 2 :

```bash
ros2 topic echo /topic
```
