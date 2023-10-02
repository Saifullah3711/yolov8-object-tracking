# yolov8-object-tracking 
#### [ultralytics==8.0.0]



# YOLOv8 Object Tracking

The YOLOv8 Object Tracking repository is a comprehensive solution for real-time object detection and tracking using the YOLO (You Only Look Once) architecture. This project combines the power of YOLOv8 for object detection with efficient object tracking algorithms to enable robust and accurate tracking of objects in videos or real-time camera feeds.

## Key Features

- **YOLOv8 Integration:** The repository integrates the YOLOv8 architecture, a state-of-the-art deep learning model, for real-time object detection. YOLOv8 is known for its speed and accuracy, making it an excellent choice for object localization.

- **Multi-Object Tracking:** The project implements multi-object tracking algorithms that can seamlessly follow multiple objects across frames. Each object detected and tracked is having different and unique color. This is crucial for applications like surveillance, autonomous vehicles, and more.

- **Customization:** The codebase is designed to be easily customizable. Users can fine-tune the model for specific object classes or adapt the tracking algorithms to their use case.

- **Real-Time Processing:** The system is optimized for real-time video processing, ensuring low latency and high-speed tracking performance.

- **Integration with Popular Frameworks:** The repository supports integration with popular deep learning frameworks like PyTorch and TensorFlow, allowing users to leverage their preferred environment.

## Getting Started to run Code

- Clone the repository
```
https://github.com/Saifullah3711/yolov8-object-tracking
```

- Go to cloned folder
```
cd yolov8-object-tracking
```

- Install the ultralytics package
```
pip install ultralytics==8.0.0
```

- Do Tracking with mentioned command below
```
#video file
python yolo\v8\detect\detect_and_trk.py model=yolov8s.pt source="test_video.mp4" show=True

#imagefile
python yolo\v8\detect\detect_and_trk.py model=yolov8m.pt source="path to image"

#Webcam
python yolo\v8\detect\detect_and_trk.py model=yolov8m.pt source=0 show=True

#External Camera
python yolo\v8\detect\detect_and_trk.py model=yolov8m.pt source=1 show=True
```

- Output file will be created in the working-dir/runs/detect/train with original filename

## Contributing

Contributions are welcome! If you have improvements, bug fixes, or new features to add, please fork the repository and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE), which means it is open-source and free to use for both personal and commercial purposes. Be sure to review the license terms before incorporating this code into your own projects.

## Acknowledgments

We acknowledge the contributions of the open-source community and the developers behind YOLOv8, as this project builds upon their work to create a versatile object tracking solution.
