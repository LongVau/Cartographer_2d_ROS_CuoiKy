## Tải package cần thiết và chạy

Mở terminal và chạy các lệnh sau để cập nhật hệ thống và cài đặt các gói Cartographer:

```bash
sudo apt update
sudo apt install ros-humble-cartographer ros-humble-cartographer-ros
```
Tải về và đổi tên thành cartographer_2d, sau đó mới chạy
```bash
ros2 launch cartographer_2d cartographer.launch.py
```
