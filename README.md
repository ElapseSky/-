# 手势控制音量



硬件：

* windows 11

（需要电脑具备摄像头）

软件：

* python 3.11
* mediapipe

运行方法：

先下载所有依赖项
`$ pip3 install -r requirements.txt`

然后运行主代码
`$ python hand_control_volume.py`

功能：

通过摄像头图像捕获手势，计算食指与拇指之间的距离，电脑音量随距离增大而变大
