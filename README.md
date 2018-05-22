# YOLOWrapper
this project implements a friendly C++ wrapper for darknet

### download weights of YOLO
download with the following commands
```Shell
wget -P models https://pjreddie.com/media/files/yolov3.weights
wget -P models https://pjreddie.com/media/files/yolov3-tiny.weights
```

### build everything
build with the following commands
```Shell
make -C darknet
make
```

### test detector
test YOLOv3 with the following commands
```Shell
make run
```

