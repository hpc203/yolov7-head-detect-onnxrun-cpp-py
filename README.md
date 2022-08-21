# yolov7-head-onnxrun-cpp-py
使用ONNXRuntime部署YOLOV7人头检测，包含C++和Python两个版本的程序.
起初想使用opencv部署的，可是opencv读取onnx文件后在forward函数出错了，
无赖只能使用onnxruntime部署。
这套程序对onnxruntime的版本要求较高，需要使用最新的onnxruntime做推理。
我的机器上的onnxruntime版本是1.11.1，人头检测可以应用到人流密度估计场景里。

onnx文件在百度云盘，链接：https://pan.baidu.com/s/1N22OMJA1UVMpao2QT9Y4lw 
提取码：t02a
