# ROS 2 example packages for the ROS 2 seminar

| Travis CI (master)  | Travis CI (develop) | Ament Lint |
| ------------- | ------------- | ------------- |
| [![Build Status](https://travis-ci.com/oroca/oroca-rqt-command.svg?branch=main)](https://travis-ci.com/github/oroca/oroca-rqt-command)  | [![Build Status](https://travis-ci.com/oroca/oroca-rqt-command.svg?branch=develop)](https://travis-ci.com/github/oroca/oroca-rqt-command)  |  [![Lint](https://github.com/oroca/oroca-rqt-command/workflows/Lint/badge.svg?branch=develop)](https://github.com/oroca/oroca-rqt-command/actions) |

## ROS 2 online seminar
- https://cafe.naver.com/openrt/24070

## GitHub Action for ROS Lint
- `.github/workflows/lint.yml`

## Travis option for CI
- `.travis.yml`

## Build
```
$ cd ~/robot_ws/src
$ git clone https://github.com/oroca/oroca-rqt-command.git
$ cd ~/robot_ws && colcon build --symlink-install
```

## Run oroca_rqt_command package
```
$ ros2 run oroca_rqt_command rqt_command
```

## Run oroca_rqt_command package with turtlesim_node
```
$ ros2 launch oroca_rqt_command turtlesim.launch.py
```
