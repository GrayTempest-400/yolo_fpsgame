# yolo_fpsgame
基于yolo的图像识别辅助
代码很多没经过测试，报error请提issue
看init改参数

代码说明:
detect.py :是edge_detect.py的依赖文件
edge_detect.py :边缘检测  屏幕中心点肯能需要更改 ，更改示例：warthunder_cv2的edge_detect_rang.py
yolov8_bak.fov.py :基于yolov8的检测 
tool.py yolov8的依赖文件 需更改159行的检测目标
![1](https://github.com/GrayTempest-400/yolo_fpsgame/assets/101955396/fe3c170e-ffc0-4cd9-ae28-698f6503d8a7)
边缘检测，原理：通过检测边缘确定中心点
![2](https://github.com/GrayTempest-400/yolo_fpsgame/assets/101955396/f933e68e-a64b-4fb0-bcc8-5f78f9651915)
范围不宜过广
![3](https://github.com/GrayTempest-400/yolo_fpsgame/assets/101955396/71ba4aba-23c1-45b1-a3d7-591aca0bb848)
yolov8检测
其他全为yolov5的依赖文件
