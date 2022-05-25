# ROS2 PCL

This repository is about PCL in ROS2.

## Compile Error

This is about some usual compilation error.

1. Boost Library cannot be found. [link](https://github.com/PointCloudLibrary/pcl/issues/5052)
```bash
--- stderr: point_cloud_filters
CMake Error at /usr/lib/x86_64-linux-gnu/cmake/pcl/PCLConfig.cmake:62 (message):
  common is required but boost was not found
Call Stack (most recent call first):
  /usr/lib/x86_64-linux-gnu/cmake/pcl/PCLConfig.cmake:367 (pcl_report_not_found)
  /usr/lib/x86_64-linux-gnu/cmake/pcl/PCLConfig.cmake:551 (find_external_library)
  CMakeLists.txt:29 (find_package)


---
```

2. Cannot build custom message with PCL

[link](https://github.com/ros2/rosidl/issues/402)
