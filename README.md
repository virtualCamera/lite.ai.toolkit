

##  <p align="center"> Lite.AI.ToolKit 🚀🚀🌟: A lite C++ toolkit of awesome AI models. </p>  

<div id="lite.ai.toolkit-Introduction"></div>  

<div align='center'>
  <img src='logs/test_lite_yolov5_1.jpg' height="80px" width="80px">
  <img src='docs/resources/efficientdet_d0.jpg' height="80px" width="80px">
  <img src='docs/resources/street.jpg' height="80px" width="80px">
  <img src='logs/test_lite_ultraface.jpg' height="80px" width="80px">
  <img src='logs/test_lite_face_landmarks_1000.jpg' height="80px" width="80px">
  <img src='logs/test_lite_fsanet.jpg' height="80px" width="80px">
  <img src='logs/test_lite_deeplabv3_resnet101.jpg' height="80px" width="80px">
  <img src='logs/test_lite_fast_style_transfer_mosaic.jpg' height="80px" width="80px"> 
  <br>
  <img src='docs/resources/teslai.gif' height="80px" width="80px">
  <img src='docs/resources/tesla.gif' height="80px" width="80px">
  <img src='docs/resources/dance3i.gif' height="80px" width="80px">
  <img src='docs/resources/dance3.gif' height="80px" width="80px">  
  <img src='docs/resources/yolop1.png' height="80px" width="80px">
  <img src='docs/resources/yolop1.gif' height="80px" width="80px">
  <img src='docs/resources/yolop2.png' height="80px" width="80px">
  <img src='docs/resources/yolop2.gif' height="80px" width="80px">

</div>    

<p align="center">English | <a href="README.zh.md">中文文档</a> | <a href=#lite.ai.toolkit-Build-MacOS>MacOS</a> | <a href=#lite.ai.toolkit-Build-Linux>Linux</a> | <a href=#lite.ai.toolkit-Build-Windows>Windows</a> </p>

<div align='center'>
  <img src=https://img.shields.io/badge/MacOS-pass-brightgreen.svg >
  <img src=https://img.shields.io/badge/Linux-unofficial-blue.svg >
  <img src=https://img.shields.io/badge/Windows-unofficial-blue.svg >
  <img src=https://img.shields.io/badge/Version-0.1.0-green.svg >
  <img src=https://img.shields.io/badge/Language-C%2B%2B-orange.svg >
  <img src=https://img.shields.io/badge/Device-GPU/CPU-yellow.svg >
  <img src=https://img.shields.io/badge/License-GPLv3-blue.svg >
</div>   

<div align='center'> 
  <img src=https://img.shields.io/badge/ONNXRuntime-support-brightgreen.svg >
  <img src=https://img.shields.io/badge/MNN-unofficial-blue.svg >
  <img src=https://img.shields.io/badge/NCNN-unofficial-blue.svg >
  <img src=https://img.shields.io/badge/TNN-unofficial-blue.svg >
<br>
  <img src=https://img.shields.io/github/stars/DefTruth/lite.ai.toolkit.svg?style=social >
  <img src=https://img.shields.io/github/forks/DefTruth/lite.ai.toolkit.svg?style=social >
  <img src=https://img.shields.io/github/watchers/DefTruth/lite.ai.toolkit.svg?style=social > 

</div>    

<!-----
<div align='center'>
  <img src=https://img.shields.io/badge/lite.ai.toolkit-"Try%20to%20make%20interesting%20things%20more%20complete~"-blue.svg >
</div>   
----->

*Lite.AI.ToolKit* 🚀🚀🌟: A lite `C++` toolkit of awesome AI models which contains *[70+](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md)* models now. It's a collection of personal interests. Such as RVM, YOLOX, YOLOP, YOLOR, YoloV5, DeepLabV3, ArcFace, etc. emmm😞 ... it's not perfect yet. For now, let's regard it as a large collection of application cases for inference engines. *Lite.AI.ToolKit* based on *[ONNXRuntime C++](https://github.com/microsoft/onnxruntime)* by default. I do have plans to reimplement it with *[NCNN](https://github.com/Tencent/ncnn)*, *[MNN](https://github.com/alibaba/MNN)* and *[TNN](https://github.com/Tencent/TNN)*, some models are already supported. Currently, I mainly consider its ease of use. Developers who need higher performance can make new optimizations based on the `C++` implementation and `ONNX` files provided by this repo~ 👏👋  

<p align="center">Core Features 🚀🚀🌟</p>

* ❤️ *Simply and User friendly.* Simply and Consistent syntax like *lite::cv::Type::Class*, see [examples](#lite.ai.toolkit-Examples-for-Lite.AI.ToolKit).
* ⚡ *Minimum Dependencies.* Only *OpenCV* and *ONNXRuntime* are required by default, see [build](#lite.ai.toolkit-Build-Lite.AI.ToolKit).
* ❤️ *Lots of Algorithm Modules.* Contains 10+ modules and *[70+](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md)* famous models with *[500+](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md)* frozen pretrained *.onnx/.mnn/.param&bin(ncnn)/.tnnmodel&tnnproto* files now, such as [object detection](#lite.ai.toolkit-object-detection), [face detection](#lite.ai.toolkit-face-detection), [face recognition](#lite.ai.toolkit-face-recognition), [segmentation](#lite.ai.toolkit-segmentation), [matting](#lite.ai.toolkit-matting), etc. See [Model Zoo](#lite.ai.toolkit-Model-Zoo) and [lite.ai.toolkit.hub.onnx.md](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md).

<p align="center"> ❤️ Star 🌟👆🏻 this repo if it does any helps to you ~ 🙃🤪🍀 </p>
 
<!----
* ✅ *Cross-Platform support.* 👋 Support [MacOS/Linux/Windows](#lite.ai.toolkit-Introduction) and CPU/GPU now.

|Latest Release|Quick Start|Usage| 
|:---:|:---:|:---:| 
|  👉 [lite.ai.toolkit.macos.v0.1.0](https://github.com/DefTruth/lite.ai.toolkit.demo/tree/main/releases/macos/v0.1.0) |  👉 [lite.ai.toolkit.demo](https://github.com/DefTruth/lite.ai.toolkit.demo) & [Quick Start Examples](#lite.ai.toolkit-Examples-for-Lite.AI.ToolKit) |  👉 [lite.ai.toolkit.examples](https://github.com/DefTruth/lite.ai.toolkit/tree/main/examples/lite/cv) |

  <img src=https://visitor-badge.laobi.icu/badge?page_id=DefTruth.lite.ai.toolkit >

<p align="center"> ❤️ Star 🌟👆🏻 this repo if it does any helps to you ~ 🙃🤪🍀 </p>
---->

## Important Notes !!!  
* 🔥 (20211111) Added NCNN/TNN/MNN/ONNXRuntime C++ [YoloV5_V_6_0](https://github.com/RangiLyu/nanodet) for [YOLOv5 v6.0](https://github.com/ultralytics/yolov5/releases/tag/v6.0) . See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolov5_v6.0.cpp).
* 🔥 (20211026) Added NCNN/TNN/MNN/ONNXRuntime C++ [YoloX_V_0_1_1](https://github.com/RangiLyu/nanodet) for [YOLOX v0.1.1](https://github.com/Megvii-BaseDetection/YOLOX/releases/tag/0.1.1rc0) . See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolox_v0.1.1.cpp).
* 🔥 (20211002) Added [NanoDet](https://github.com/RangiLyu/nanodet) for object detection. ⚡ Super fast and tiny! 1.1Mb only! See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_nanodet.cpp).  
* 🔥 (20210920) Added [RobustVideoMatting](https://github.com/PeterL1n/RobustVideoMatting) as [*lite::cv::matting::RobustVideoMatting*](#lite.ai.toolkit-matting) ! See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_rvm.cpp).  

<div align='center'>
  <img src='docs/resources/interviewi.gif' height="80px" width="80px">
  <img src='docs/resources/interview.gif' height="80px" width="80px">  
  <img src='docs/resources/dance3i.gif' height="80px" width="80px">
  <img src='docs/resources/dance3.gif' height="80px" width="80px">
  <img src='docs/resources/teslai.gif' height="80px" width="80px">
  <img src='docs/resources/tesla.gif' height="80px" width="80px">  
  <img src='docs/resources/b5i.gif' height="80px" width="80px">
  <img src='docs/resources/b5.gif' height="80px" width="80px">
</div>


* 🔥 (20210915) Added [YOLOP](https://github.com/hustvl/YOLOP) Panoptic 🚗 Perception as [*lite::cv::detection::YOLOP*](#lite.ai.toolkit-object-detection) ! See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolop.cpp).

<div align='center'>
  <img src='docs/resources/yolop1.png' height="80px" width="160px">
  <img src='docs/resources/yolop1.gif' height="80px" width="160px">
  <img src='docs/resources/yolop2.png' height="80px" width="160px">
  <img src='docs/resources/yolop2.gif' height="80px" width="160px">

</div>   


* ✅ (20210807) Added [YoloR](https://github.com/WongKinYiu/yolor) ! Use it through [*lite::cv::detection::YoloR*](#lite.ai.toolkit-object-detection) syntax ! See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolor.cpp).
* ✅ (20210731) Added [RetinaFace-CVPR2020](https://github.com/biubug6/Pytorch_Retinaface) for face detection, 1.6Mb only! See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_retinaface.cpp).
* 🔥 (20210721) Added [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX)! Use it through [*lite::cv::detection::YoloX*](#lite.ai.toolkit-object-detection) syntax ! See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolox.cpp).  


<details>
<summary> Expand for More Notes.</summary>  

## More Notes !!!    

* ✅ (20210815) Added [EfficientDet](https://github.com/zylo117/Yet-Another-EfficientDet-Pytorch) for object detection! See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_efficientdet.cpp).  
* ✅ (20210808) Added [ScaledYoloV4](https://github.com/WongKinYiu/ScaledYOLOv4) for object detection! See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_scaled_yolov4.cpp).  
* ✅ (20210807) Added [TinyYoloV4VOC](https://github.com/bubbliiiing/yolov4-tiny-pytorch) for object detection! See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_tiny_yolov4_voc.cpp).  
* ✅ (20210807) Added [TinyYoloV4COCO](https://github.com/bubbliiiing/yolov4-tiny-pytorch) for object detection! See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_tiny_yolov4_coco.cpp).  
* ✅ (20210722) Update [lite.ai.toolkit.hub.onnx.md](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md) ! *Lite.AI.Toolkit* contains *[70+](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md)* AI models with *[150+](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md)* .onnx files now.  
* ⚠️ (20210802) Added GPU Compatibility for CUDAExecutionProvider. See [issue#10](https://github.com/DefTruth/lite.ai.toolkit/issues/10).
* ⚠️ (20210801) fixed [issue#9](https://github.com/DefTruth/lite.ai.toolkit/issues/9) YOLOX inference error for non-square shape. See [yolox.cpp](https://github.com/DefTruth/lite.ai.toolkit/blob/main/ort/cv/yolox.cpp).  
* ✅ (20210801) Added [FaceBoxes](https://github.com/zisianw/FaceBoxes.PyTorch) for face detection! See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_faceboxes.cpp).  
* ✅ (20210727) Added [MobileNetV2SE68、PFLD68](https://github.com/cunjian/pytorch_face_landmark) for 68 facial landmarks detection! See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_pfld68.cpp).  
* ✅ (20210726) Added [PFLD98](https://github.com/polarisZhao/PFLD-pytorch) for 98 facial landmarks detection! See [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_pfld98.cpp).

</details>


## Contents.
* [Build](#lite.ai.toolkit-Build-Lite.AI.ToolKit)
* [Model Zoo](#lite.ai.toolkit-Model-Zoo)
* [Examples](#lite.ai.toolkit-Examples-for-Lite.AI.ToolKit)
* [API Docs](#lite.ai.toolkit-Lite.AI.ToolKit-API-Docs)
* [Other Docs](#lite.ai.toolkit-Other-Docs)
* [License](#lite.ai.toolkit-License)
* [References](#lite.ai.toolkit-References)


## 1. Build Lite.AI.ToolKit 🚀🚀🌟
<div id="lite.ai.toolkit-Build-MacOS"></div>
<div id="lite.ai.toolkit-Build-Lite.AI.ToolKit"></div>

Build the shared lib of *Lite.AI.ToolKit* for *MacOS* from sources. Note that Lite.AI.ToolKit uses `onnxruntime` as default backend, for the reason that onnxruntime supports the most of onnx's operators.  Click ▶️ will show you the docs how to build *Lite.AI.ToolKit* 🚀🚀🌟 for Linux and Windows.

<div id="lite.ai.toolkit-Build-Linux"></div>
<div id="lite.ai.toolkit-Build-Windows"></div>

<details>
<summary> ⚠️ Linux and Windows. </summary>  

### Linux and Windows.  

⚠️ *Lite.AI.ToolKit* is not directly support Linux and Windows now. For Linux and Windows, you need to build or download(if have official builts) the shared libs of *OpenCV*、*ONNXRuntime* and any other Engines(like MNN, NCNN, TNN) firstly, then put the headers into the specific directories or just let these directories unchange(use the headers offer by this repo, the header file of the dependent library of this project is directly copied from the corresponding official library). However, the dynamic libraries under different operating systems need to be recompiled or downloaded. MacOS users can directly use the dynamic libraries of each dependent library provided by this project:   
* *lite.ai.toolkit/opencv2*  
  ```shell
    cp -r you-path-to-downloaded-or-built-opencv/include/opencv4/opencv2 lite.ai.toolkit/opencv2
  ```
* *lite.ai.toolkit/onnxruntime*  
  ```shell
    cp -r you-path-to-downloaded-or-built-onnxruntime/include/onnxruntime lite.ai.toolkit/onnxruntime
  ```
* *lite.ai.toolkit/MNN*  
  ```shell
    cp -r you-path-to-downloaded-or-built-MNN/include/MNN lite.ai.toolkit/MNN
  ```
* *lite.ai.toolkit/ncnn*   
  ```shell
    cp -r you-path-to-downloaded-or-built-ncnn/include/ncnn lite.ai.toolkit/ncnn
  ```
* *lite.ai.toolkit/tnn*   
  ```shell
    cp -r you-path-to-downloaded-or-built-TNN/include/tnn lite.ai.toolkit/tnn
  ```

and put the libs into *lite.ai.toolkit/lib* directory. Please reference the build-docs[<sup>1</sup>](#lite.ai.toolkit-1) for *third_party*.   
* *lite.ai.toolkit/lib*  
  ```shell
    cp you-path-to-downloaded-or-built-opencv/lib/*opencv* lite.ai.toolkit/lib
    cp you-path-to-downloaded-or-built-onnxruntime/lib/*onnxruntime* lite.ai.toolkit/lib
    cp you-path-to-downloaded-or-built-MNN/lib/*MNN* lite.ai.toolkit/lib
    cp you-path-to-downloaded-or-built-ncnn/lib/*ncnn* lite.ai.toolkit/lib
    cp you-path-to-downloaded-or-built-TNN/lib/*TNN* lite.ai.toolkit/lib
  ```


* Windows: You can reference to [issue#6](https://github.com/DefTruth/lite.ai.toolkit/issues/6)  
* Linux: The Docs and Docker image for Linux will be coming soon ~ [issue#2](https://github.com/DefTruth/lite.ai.toolkit/issues/2)  
* Happy News !!! : 🚀 You can download the latest *ONNXRuntime* official built libs of Windows, Linux, MacOS and Arm !!! Both CPU and GPU versions are available. No more attentions needed pay to build it from source. Download the official built libs from [v1.8.1](https://github.com/microsoft/onnxruntime/releases). I have used version 1.7.0 for Lite.AI.ToolKit now, you can downlod it from [v1.7.0](https://github.com/microsoft/onnxruntime/releases/tag/v1.7.0), but version 1.8.1 should also work, I guess ~  🙃🤪🍀. For *OpenCV*, try to build from source(Linux) or down load the official built(Windows) from [OpenCV 4.5.3](https://github.com/opencv/opencv/releases). Then put the includes and libs into specific directory of Lite.AI.ToolKit. 

</details>  

```shell
    git clone --depth=1 https://github.com/DefTruth/lite.ai.toolkit.git  # latest
    cd lite.ai.toolkit && sh ./build.sh  # On MacOS, you can use the built OpenCV, ONNXRuntime, MNN, NCNN and TNN libs in this repo.
```

```
cd build
cmake -DINCLUDE_OPENCV=ON -DENABLE_MNN=OFF -DENABLE_NCNN=OFF -DENABLE_TNN=OFF ..
cmake --build . --config MinSizeRel
```

* GPU Compatibility for Windows: See [issue#10](https://github.com/DefTruth/lite.ai.toolkit/issues/10).  
* GPU Compatibility for Linux: See [issue#97](https://github.com/DefTruth/lite.ai.toolkit/issues/97).
  
* To link Lite.AI.ToolKit, you can follow the CMakeLists.txt listed belows.  

```cmake
cmake_minimum_required(VERSION 3.17)
project(lite.ai.toolkit.demo)

set(CMAKE_CXX_STANDARD 11)

# setting up lite.ai.toolkit
set(LITE_AI_DIR ${CMAKE_SOURCE_DIR}/lite.ai.toolkit)
set(LITE_AI_INCLUDE_DIR ${LITE_AI_DIR}/include)
set(LITE_AI_LIBRARY_DIR ${LITE_AI_DIR}/lib)
include_directories(${LITE_AI_INCLUDE_DIR})
link_directories(${LITE_AI_LIBRARY_DIR})

set(OpenCV_LIBS
        opencv_highgui
        opencv_core
        opencv_imgcodecs
        opencv_imgproc
        opencv_video
        opencv_videoio
        )
# add your executable
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_SOURCE_DIR}/examples/build)

add_executable(lite_rvm examples/test_lite_rvm.cpp)
target_link_libraries(lite_rvm
        lite.ai.toolkit
        onnxruntime
        MNN  # need, if built lite.ai.toolkit with ENABLE_MNN=ON,  default OFF
        ncnn # need, if built lite.ai.toolkit with ENABLE_NCNN=ON, default OFF 
        TNN  # need, if built lite.ai.toolkit with ENABLE_TNN=ON,  default OFF 
        ${OpenCV_LIBS})  # link lite.ai.toolkit & other libs.
```

<details>
<summary> Expand for more details of How to link the shared lib of Lite.AI.ToolKit?</summary>  

```shell
cd ./build/lite.ai.toolkit/lib && otool -L liblite.ai.toolkit.0.0.1.dylib 
liblite.ai.toolkit.0.0.1.dylib:
        @rpath/liblite.ai.toolkit.0.0.1.dylib (compatibility version 0.0.1, current version 0.0.1)
        @rpath/libopencv_highgui.4.5.dylib (compatibility version 4.5.0, current version 4.5.2)
        @rpath/libonnxruntime.1.7.0.dylib (compatibility version 0.0.0, current version 1.7.0)
        ...
```


```shell
cd ../ && tree .
├── bin
├── include
│   ├── lite
│   │   ├── backend.h
│   │   ├── config.h
│   │   └── lite.h
│   └── ort
└── lib
    └── liblite.ai.toolkit.0.0.1.dylib
```
* Run the built examples:
```shell
cd ./build/lite.ai.toolkit/bin && ls -lh | grep lite
-rwxr-xr-x  1 root  staff   301K Jun 26 23:10 liblite.ai.toolkit.0.0.1.dylib
...
-rwxr-xr-x  1 root  staff   196K Jun 26 23:10 lite_yolov4
-rwxr-xr-x  1 root  staff   196K Jun 26 23:10 lite_yolov5
...
```

```shell
./lite_yolov5
LITEORT_DEBUG LogId: ../../../hub/onnx/cv/yolov5s.onnx
=============== Input-Dims ==============
...
detected num_anchors: 25200
generate_bboxes num: 66
Default Version Detected Boxes Num: 5
```

* To link `lite.ai.toolkit` shared lib. You need to make sure that `OpenCV` and `onnxruntime` are linked correctly. Just like:

```cmake
cmake_minimum_required(VERSION 3.17)
project(lite.ai.toolkit.demo)

set(CMAKE_CXX_STANDARD 11)

# setting up lite.ai.toolkit
set(LITE_AI_DIR ${CMAKE_SOURCE_DIR}/lite.ai.toolkit)
set(LITE_AI_INCLUDE_DIR ${LITE_AI_DIR}/include)
set(LITE_AI_LIBRARY_DIR ${LITE_AI_DIR}/lib)
include_directories(${LITE_AI_INCLUDE_DIR})
link_directories(${LITE_AI_LIBRARY_DIR})

set(OpenCV_LIBS
        opencv_highgui
        opencv_core
        opencv_imgcodecs
        opencv_imgproc
        opencv_video
        opencv_videoio
        )
# add your executable
set(EXECUTABLE_OUTPUT_PATH ${CMAKE_SOURCE_DIR}/examples/build)

add_executable(lite_rvm examples/test_lite_rvm.cpp)
target_link_libraries(lite_rvm
        lite.ai.toolkit
        onnxruntime
        MNN
        ncnn
        ${OpenCV_LIBS})  # link lite.ai.toolkit & other libs.
```
A minimum example to show you how to link the shared lib of Lite.AI.ToolKit correctly for your own project can be found at [lite.ai.toolkit.demo](https://github.com/DefTruth/lite.ai.toolkit.demo).

</details>


## 2. Model Zoo.

<div id="lite.ai.toolkit-Model-Zoo"></div>

*Lite.AI.ToolKit* contains *[70+](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md)* AI models with *[500+](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md)* frozen pretrained *.onnx/.mnn/.param&bin(ncnn)/.tnnmodel&tnnproto* files now. Most of the files are converted by myself. You can use it through *lite::cv::Type::Class* syntax, such as *[lite::cv::detection::YoloV5](#lite.ai.toolkit-object-detection)*. More details can be found at [Examples for Lite.AI.ToolKit](#lite.ai.toolkit-Examples-for-Lite.AI.ToolKit).  

<details>
<summary> Expand Details for Namespace and Lite.AI.ToolKit modules.</summary>  

### Namespace and Lite.AI.ToolKit modules.

| Namepace                   | Details                                                      |
| :------------------------- | :----------------------------------------------------------- |
| *lite::cv::detection*      | Object Detection. one-stage and anchor-free detectors, YoloV5, YoloV4, SSD, etc. ✅ |
| *lite::cv::classification* | Image Classification. DensNet, ShuffleNet, ResNet, IBNNet, GhostNet, etc. ✅ |
| *lite::cv::faceid*         | Face Recognition. ArcFace, CosFace, CurricularFace, etc. ❇️   |
| *lite::cv::face*           | Face Analysis. *detect*, *align*, *pose*, *attr*, etc. ❇️    |
| *lite::cv::face::detect*   | Face Detection. UltraFace, RetinaFace, FaceBoxes, PyramidBox, etc. ❇️ |
| *lite::cv::face::align*    | Face Alignment. PFLD(106), FaceLandmark1000(1000 landmarks), PRNet, etc. ❇️ |
| *lite::cv::face::pose*     | Head Pose Estimation.  FSANet, etc. ❇️                        |
| *lite::cv::face::attr*     | Face Attributes. Emotion, Age, Gender. EmotionFerPlus, VGG16Age, etc. ❇️ |
| *lite::cv::segmentation*   | Object Segmentation. Such as FCN, DeepLabV3, etc. ⚠️          |
| *lite::cv::style*          | Style Transfer. Contains neural style transfer now, such as FastStyleTransfer.  ⚠️ |
| *lite::cv::matting*        | Image Matting. Object and Human matting.  ⚠️                  |
| *lite::cv::colorization*   | Colorization. Make Gray image become RGB. ⚠️                  |
| *lite::cv::resolution*     | Super Resolution.  ⚠️                                         |


### Lite.AI.ToolKit's Classes and Pretrained Files.

Correspondence between the classes in *Lite.AI.ToolKit* and pretrained model files can be found at [lite.ai.toolkit.hub.onnx.md](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md). For examples, the pretrained model files for *lite::cv::detection::YoloV5* and *lite::cv::detection::YoloX* are listed as follows.


|             Class             | Pretrained ONNX Files |                   Rename or Converted From (Repo)                   | Size  |
| :---------------------------: | :-------------------: | :----------------------------------------------------: | :---: |
| *lite::cv::detection::YoloV5* |     yolov5l.onnx      | [yolov5](https://github.com/ultralytics/yolov5) (🔥🔥💥↑) | 188Mb |
| *lite::cv::detection::YoloV5* |     yolov5m.onnx      | [yolov5](https://github.com/ultralytics/yolov5) (🔥🔥💥↑) | 85Mb  |
| *lite::cv::detection::YoloV5* |     yolov5s.onnx      | [yolov5](https://github.com/ultralytics/yolov5) (🔥🔥💥↑) | 29Mb  |
| *lite::cv::detection::YoloV5* |     yolov5x.onnx      | [yolov5](https://github.com/ultralytics/yolov5) (🔥🔥💥↑) | 351Mb |
| *lite::cv::detection::YoloX* |     yolox_x.onnx      | [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) (🔥🔥!!↑) | 378Mb |
| *lite::cv::detection::YoloX* |     yolox_l.onnx      | [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) (🔥🔥!!↑) | 207Mb  |
| *lite::cv::detection::YoloX* |     yolox_m.onnx      | [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) (🔥🔥!!↑) | 97Mb  |
| *lite::cv::detection::YoloX* |     yolox_s.onnx      | [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) (🔥🔥!!↑) | 34Mb |
| *lite::cv::detection::YoloX* |     yolox_tiny.onnx      | [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) (🔥🔥!!↑) | 19Mb |
| *lite::cv::detection::YoloX* |     yolox_nano.onnx      | [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) (🔥🔥!!↑) | 3.5Mb |

It means that you can load the the any one `yolov5*.onnx` and  `yolox_*.onnx` according to your application through the same Lite.AI.ToolKit's classes, such as *YoloV5*, *YoloX*, etc.

```c++
auto *yolov5 = new lite::cv::detection::YoloV5("yolov5x.onnx");  // for server
auto *yolov5 = new lite::cv::detection::YoloV5("yolov5l.onnx"); 
auto *yolov5 = new lite::cv::detection::YoloV5("yolov5m.onnx");  
auto *yolov5 = new lite::cv::detection::YoloV5("yolov5s.onnx");  // for mobile device 
auto *yolox = new lite::cv::detection::YoloX("yolox_x.onnx");  
auto *yolox = new lite::cv::detection::YoloX("yolox_l.onnx");  
auto *yolox = new lite::cv::detection::YoloX("yolox_m.onnx");  
auto *yolox = new lite::cv::detection::YoloX("yolox_s.onnx");  
auto *yolox = new lite::cv::detection::YoloX("yolox_tiny.onnx");  
auto *yolox = new lite::cv::detection::YoloX("yolox_nano.onnx");  // 3.5Mb only !
```

</details>

* Downloads: <div id="lite.ai.toolkit-2"></div> 
  Note, for Google Drive, I can not upload all the *.onnx files because of the storage limitation (15G).

  * ONNX files 👉 [Baidu Drive](https://pan.baidu.com/s/1elUGcx7CZkkjEoYhTMwTRQ) code: 8gin && [Google Drive](https://drive.google.com/drive/folders/1p6uBcxGeyS1exc-T61vL8YRhwjYL4iD2?usp=sharing). See [lite.ai.toolkit.hub.onnx.md](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md)
  * MNN files 👉 [Baidu Drive](https://pan.baidu.com/s/1KyO-bCYUv6qPq2M8BH_Okg) code: 9v63 && Google Drive(Wait). See [lite.ai.toolkit.hub.mnn.md](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md)
  * NCNN files 👉 [Baidu Drive](https://pan.baidu.com/s/1hlnqyNsFbMseGFWscgVhgQ) code: sc7f && Google Drive(Wait). See [lite.ai.toolkit.hub.ncnn.md](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md)  
  * TNN files 👉 [Baidu Drive](https://pan.baidu.com/s/1lvM2YKyUbEc5HKVtqITpcw) code: 6o6k && Google Drive(Wait). See [lite.ai.toolkit.hub.tnn.md](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md)  
    

* Object Detection.  

|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[YoloV5](https://github.com/ultralytics/yolov5)|28M|[yolov5](https://github.com/ultralytics/yolov5)|🔥🔥💥↑| [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection)  | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolov5.cpp) |
|[YoloV3](https://github.com/onnx/models/blob/master/vision/object_detection_segmentation/yolov3)|236M|[onnx-models](https://github.com/onnx/models)|🔥🔥🔥↑| [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolov3.cpp) |
|[TinyYoloV3](https://github.com/onnx/models/blob/master/vision/object_detection_segmentation/tiny-yolov3)|33M|        [onnx-models](https://github.com/onnx/models)         | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_tiny_yolov3.cpp) |
|[YoloV4](https://github.com/argusswift/YOLOv4-pytorch)|176M| [YOLOv4...](https://github.com/argusswift/YOLOv4-pytorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolov4.cpp) |
|[SSD](https://github.com/onnx/models/blob/master/vision/object_detection_segmentation/ssd)|76M|        [onnx-models](https://github.com/onnx/models)         | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_ssd.cpp) |
|[SSDMobileNetV1](https://github.com/onnx/models/blob/master/vision/object_detection_segmentation/ssd-mobilenetv1)|27M|        [onnx-models](https://github.com/onnx/models)         | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_ssd_mobilenetv1.cpp) |
|[YoloX](https://github.com/Megvii-BaseDetection/YOLOX)|3.5M| [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolox.cpp) |
|[TinyYoloV4VOC](https://github.com/bubbliiiing/yolov4-tiny-pytorch)|22M| [yolov4-tiny...](https://github.com/bubbliiiing/yolov4-tiny-pytorch) | 🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_tiny_yolov4_voc.cpp) |
|[TinyYoloV4COCO](https://github.com/bubbliiiing/yolov4-tiny-pytorch)|22M| [yolov4-tiny...](https://github.com/bubbliiiing/yolov4-tiny-pytorch) | 🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_tiny_yolov4_coco.cpp) |
|[YoloR](https://github.com/WongKinYiu/yolor)|39M| [yolor](https://github.com/WongKinYiu/yolor) | 🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolor.cpp) |
|[ScaledYoloV4](https://github.com/WongKinYiu/ScaledYOLOv4)|270M| [ScaledYOLOv4](https://github.com/WongKinYiu/ScaledYOLOv4) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_scaled_yolov4.cpp) |
|[EfficientDet](https://github.com/zylo117/Yet-Another-EfficientDet-Pytorch)|15M| [...EfficientDet...](https://github.com/zylo117/Yet-Another-EfficientDet-Pytorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_efficientdet.cpp) |
|[EfficientDetD7](https://github.com/zylo117/Yet-Another-EfficientDet-Pytorch)|220M| [...EfficientDet...](https://github.com/zylo117/Yet-Another-EfficientDet-Pytorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_efficientdet_d7.cpp) |
|[EfficientDetD8](https://github.com/zylo117/Yet-Another-EfficientDet-Pytorch)|322M| [...EfficientDet...](https://github.com/zylo117/Yet-Another-EfficientDet-Pytorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_efficientdet_d8.cpp) |
|[YOLOP](https://github.com/hustvl/YOLOP)|30M| [YOLOP](https://github.com/hustvl/YOLOP) | 🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolop.cpp) |
|[NanoDet](https://github.com/RangiLyu/nanodet)|1.1M| [nanodet](https://github.com/RangiLyu/nanodet) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_nanodet.cpp) |
|[NanoDetEfficientNetLite](https://github.com/RangiLyu/nanodet)|12M| [nanodet](https://github.com/RangiLyu/nanodet) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_nanodet_efficientnet_lite.cpp) |
|[YoloX_V_0_1_1](https://github.com/Megvii-BaseDetection/YOLOX)|3.5M| [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolox_v0.1.1.cpp) |
|[YoloV5_V_6_0](https://github.com/ultralytics/yolov5)|7.5M|[yolov5](https://github.com/ultralytics/yolov5)|🔥🔥💥↑| [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-object-detection)  | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolov5_v6.0.cpp) |


|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|  
|[YoloV5](https://github.com/ultralytics/yolov5)|28M|[yolov5](https://github.com/ultralytics/yolov5)|🔥🔥💥↑| [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-object-detection)  | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolov5.cpp) |
|[YoloX](https://github.com/Megvii-BaseDetection/YOLOX)|3.5M| [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolox.cpp) |
|[YOLOP](https://github.com/hustvl/YOLOP)|30M| [YOLOP](https://github.com/hustvl/YOLOP) | 🔥🔥↑ | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolop.cpp) |
|[NanoDet](https://github.com/RangiLyu/nanodet)|1.1M| [nanodet](https://github.com/RangiLyu/nanodet) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_nanodet.cpp) |
|[NanoDetEfficientNetLite](https://github.com/RangiLyu/nanodet)|12M| [nanodet](https://github.com/RangiLyu/nanodet) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_nanodet_efficientnet_lite.cpp) |
|[YoloX_V_0_1_1](https://github.com/Megvii-BaseDetection/YOLOX)|3.5M| [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolox_v0.1.1.cpp) |
|[YoloR](https://github.com/WongKinYiu/yolor)|39M| [yolor](https://github.com/WongKinYiu/yolor) | 🔥🔥↑ | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolor.cpp) |
|[YoloV5_V_6_0](https://github.com/ultralytics/yolov5)|7.5M|[yolov5](https://github.com/ultralytics/yolov5)|🔥🔥💥↑| [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-object-detection)  | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolov5_v6.0.cpp) |


|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|  
|[YoloV5](https://github.com/ultralytics/yolov5)|28M|[yolov5](https://github.com/ultralytics/yolov5)|🔥🔥💥↑| [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-object-detection)  | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolov5.cpp) |
|[YoloX](https://github.com/Megvii-BaseDetection/YOLOX)|3.5M| [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolox.cpp) |
|[YOLOP](https://github.com/hustvl/YOLOP)|30M| [YOLOP](https://github.com/hustvl/YOLOP) | 🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolop.cpp) |  
|[NanoDet](https://github.com/RangiLyu/nanodet)|1.1M| [nanodet](https://github.com/RangiLyu/nanodet) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_nanodet.cpp) |
|[NanoDetEfficientNetLite](https://github.com/RangiLyu/nanodet)|12M| [nanodet](https://github.com/RangiLyu/nanodet) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_nanodet_efficientnet_lite.cpp) |
|[NanoDetDepreciated](https://github.com/RangiLyu/nanodet)|1.1M| [nanodet](https://github.com/RangiLyu/nanodet) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_nanodet_depreciated.cpp) |
|[NanoDetEfficientNetLiteD...](https://github.com/RangiLyu/nanodet)|12M| [nanodet](https://github.com/RangiLyu/nanodet) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_nanodet_efficientnet_lite_depreciated.cpp) |
|[YoloX_V_0_1_1](https://github.com/Megvii-BaseDetection/YOLOX)|3.5M| [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolox_v0.1.1.cpp) |
|[YoloR](https://github.com/WongKinYiu/yolor)|39M| [yolor](https://github.com/WongKinYiu/yolor) | 🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolor.cpp) |
|[YoloRssss](https://github.com/WongKinYiu/yolor)|39M| [yolor](https://github.com/WongKinYiu/yolor) | 🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolor.cpp) |
|[YoloV5_V_6_0](https://github.com/ultralytics/yolov5)|7.5M|[yolov5](https://github.com/ultralytics/yolov5)|🔥🔥💥↑| [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-object-detection)  | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolov5_v6.0.cpp) |
|[YoloV5_V_6_0_P6](https://github.com/ultralytics/yolov5)|7.5M|[yolov5](https://github.com/ultralytics/yolov5)|🔥🔥💥↑| [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-object-detection)  | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolov5_v6.0.cpp) |


|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|  
|[YoloV5](https://github.com/ultralytics/yolov5)|28M|[yolov5](https://github.com/ultralytics/yolov5)|🔥🔥💥↑| [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-object-detection)  | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolov5.cpp) |  
|[YoloX](https://github.com/Megvii-BaseDetection/YOLOX)|3.5M| [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolox.cpp) |
|[YOLOP](https://github.com/hustvl/YOLOP)|30M| [YOLOP](https://github.com/hustvl/YOLOP) | 🔥🔥↑ | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolop.cpp) |
|[NanoDet](https://github.com/RangiLyu/nanodet)|1.1M| [nanodet](https://github.com/RangiLyu/nanodet) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_nanodet.cpp) |
|[NanoDetEfficientNetLite](https://github.com/RangiLyu/nanodet)|12M| [nanodet](https://github.com/RangiLyu/nanodet) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_nanodet_efficientnet_lite.cpp) |
|[YoloX_V_0_1_1](https://github.com/Megvii-BaseDetection/YOLOX)|3.5M| [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolox_v0.1.1.cpp) |
|[YoloR](https://github.com/WongKinYiu/yolor)|39M| [yolor](https://github.com/WongKinYiu/yolor) | 🔥🔥↑ | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-object-detection) | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolor.cpp) |
|[YoloV5_V_6_0](https://github.com/ultralytics/yolov5)|7.5M|[yolov5](https://github.com/ultralytics/yolov5)|🔥🔥💥↑| [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-object-detection)  | *detection* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_yolov5_v6.0.cpp) |


* Face Recognition.  

|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[GlintArcFace](https://github.com/deepinsight/insightface/tree/master/recognition/arcface_torch)|92M|  [insightface](https://github.com/deepinsight/insightface)   | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_glint_arcface.cpp) |
|[GlintCosFace](https://github.com/deepinsight/insightface/tree/master/recognition/arcface_torch)|92M|  [insightface](https://github.com/deepinsight/insightface)   | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_glint_cosface.cpp) |
|[GlintPartialFC](https://github.com/deepinsight/insightface/tree/master/recognition/partial_fc)|170M|  [insightface](https://github.com/deepinsight/insightface)   | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_glint_partial_fc.cpp) |
|[FaceNet](https://github.com/timesler/facenet-pytorch)|89M| [facenet...](https://github.com/timesler/facenet-pytorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_facenet.cpp) |
|[FocalArcFace](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch)|166M| [face.evoLVe...](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_focal_arcface.cpp) |
|[FocalAsiaArcFace](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch)|166M| [face.evoLVe...](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_focal_asia_arcface.cpp) |
|[TencentCurricularFace](https://github.com/Tencent/TFace/tree/master/tasks/distfc)|249M|          [TFace](https://github.com/Tencent/TFace)           |  🔥🔥↑  | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_tencent_curricular_face.cpp) |
|[TencentCifpFace](https://github.com/Tencent/TFace/tree/master/tasks/cifp)|130M|          [TFace](https://github.com/Tencent/TFace)           |  🔥🔥↑  | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_tencent_cifp_face.cpp) |
|[CenterLossFace](https://github.com/louis-she/center-loss.pytorch)| 280M |  [center-loss...](https://github.com/louis-she/center-loss.pytorch)           |  🔥🔥↑  | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_center_loss_face.cpp) |
|[SphereFace](https://github.com/clcarwin/sphereface_pytorch)| 80M |  [sphere...](https://github.com/clcarwin/sphereface_pytorch)   |  🔥🔥↑  | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅️ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_sphere_face.cpp) |
|[PoseRobustFace](https://github.com/penincillin/DREAM)| 92M | [DREAM](https://github.com/penincillin/DREAM)  |  🔥🔥↑  | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅️ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_pose_robust_face.cpp) |
|[NaivePoseRobustFace](https://github.com/penincillin/DREAM)| 43M | [DREAM](https://github.com/penincillin/DREAM)  |  🔥🔥↑  | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅️ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_naive_pose_robust_face.cpp) |
|[MobileFaceNet](https://github.com/Xiaoccer/MobileFaceNet_Pytorch)| 3.8M |  [MobileFace...](https://github.com/Xiaoccer/MobileFaceNet_Pytorch)           |  🔥🔥↑  | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_mobile_facenet.cpp) |
|[CavaGhostArcFace](https://github.com/cavalleria/cavaface.pytorch)| 15M | [cavaface...](https://github.com/cavalleria/cavaface.pytorch) |  🔥🔥↑  | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* |  ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_cava_ghost_arcface.cpp) |
|[CavaCombinedFace](https://github.com/cavalleria/cavaface.pytorch)| 250M | [cavaface...](https://github.com/cavalleria/cavaface.pytorch) |  🔥🔥↑  | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_cava_combined_face.cpp) |
|[MobileSEFocalFace](https://github.com/grib0ed0v/face_recognition.pytorch)|4.5M| [face_recog...](https://github.com/grib0ed0v/face_recognition.pytorch) | 🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-recognition) | *faceid* | ✅ |  [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_mobilese_focal_face.cpp) |

|Class|Size|From|Awesome|File|Type|State|Usage|  
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[GlintArcFace](https://github.com/deepinsight/insightface/tree/master/recognition/arcface_torch)|92M|  [insightface](https://github.com/deepinsight/insightface)   | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_glint_arcface.cpp) |
|[GlintCosFace](https://github.com/deepinsight/insightface/tree/master/recognition/arcface_torch)|92M|  [insightface](https://github.com/deepinsight/insightface)   | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_glint_cosface.cpp) |
|[GlintPartialFC](https://github.com/deepinsight/insightface/tree/master/recognition/partial_fc)|170M|  [insightface](https://github.com/deepinsight/insightface)   | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_glint_partial_fc.cpp) |
|[FaceNet](https://github.com/timesler/facenet-pytorch)|89M| [facenet...](https://github.com/timesler/facenet-pytorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_facenet.cpp) |
|[FocalArcFace](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch)|166M| [face.evoLVe...](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_focal_arcface.cpp) |
|[FocalAsiaArcFace](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch)|166M| [face.evoLVe...](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_focal_asia_arcface.cpp) |
|[TencentCurricularFace](https://github.com/Tencent/TFace/tree/master/tasks/distfc)|249M|          [TFace](https://github.com/Tencent/TFace)           |  🔥🔥↑  | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_tencent_curricular_face.cpp) |
|[TencentCifpFace](https://github.com/Tencent/TFace/tree/master/tasks/cifp)|130M|          [TFace](https://github.com/Tencent/TFace)           |  🔥🔥↑  | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_tencent_cifp_face.cpp) |
|[CenterLossFace](https://github.com/louis-she/center-loss.pytorch)| 280M |  [center-loss...](https://github.com/louis-she/center-loss.pytorch)           |  🔥🔥↑  | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_center_loss_face.cpp) |
|[SphereFace](https://github.com/clcarwin/sphereface_pytorch)| 80M |  [sphere...](https://github.com/clcarwin/sphereface_pytorch)   |  🔥🔥↑  | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-face-recognition) | *faceid* | ✅️ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_sphere_face.cpp) |
|[MobileFaceNet](https://github.com/Xiaoccer/MobileFaceNet_Pytorch)| 3.8M |  [MobileFace...](https://github.com/Xiaoccer/MobileFaceNet_Pytorch)           |  🔥🔥↑  | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_mobile_facenet.cpp) |
|[CavaGhostArcFace](https://github.com/cavalleria/cavaface.pytorch)| 15M | [cavaface...](https://github.com/cavalleria/cavaface.pytorch) |  🔥🔥↑  | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-face-recognition) | *faceid* |  ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_cava_ghost_arcface.cpp) |
|[CavaCombinedFace](https://github.com/cavalleria/cavaface.pytorch)| 250M | [cavaface...](https://github.com/cavalleria/cavaface.pytorch) |  🔥🔥↑  | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_cava_combined_face.cpp) |
|[MobileSEFocalFace](https://github.com/grib0ed0v/face_recognition.pytorch)|4.5M| [face_recog...](https://github.com/grib0ed0v/face_recognition.pytorch) | 🔥🔥↑ | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-face-recognition) | *faceid* | ✅ |  [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_mobilese_focal_face.cpp) |


|Class|Size|From|Awesome|File|Type|State|Usage|  
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[GlintArcFace](https://github.com/deepinsight/insightface/tree/master/recognition/arcface_torch)|92M|  [insightface](https://github.com/deepinsight/insightface)   | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_glint_arcface.cpp) |
|[GlintCosFace](https://github.com/deepinsight/insightface/tree/master/recognition/arcface_torch)|92M|  [insightface](https://github.com/deepinsight/insightface)   | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_glint_cosface.cpp) |
|[GlintPartialFC](https://github.com/deepinsight/insightface/tree/master/recognition/partial_fc)|170M|  [insightface](https://github.com/deepinsight/insightface)   | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_glint_partial_fc.cpp) |
|[FaceNet](https://github.com/timesler/facenet-pytorch)|89M| [facenet...](https://github.com/timesler/facenet-pytorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_facenet.cpp) |
|[FocalArcFace](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch)|166M| [face.evoLVe...](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_focal_arcface.cpp) |
|[FocalAsiaArcFace](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch)|166M| [face.evoLVe...](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_focal_asia_arcface.cpp) |
|[TencentCurricularFace](https://github.com/Tencent/TFace/tree/master/tasks/distfc)|249M|          [TFace](https://github.com/Tencent/TFace)           |  🔥🔥↑  | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_tencent_curricular_face.cpp) |
|[TencentCifpFace](https://github.com/Tencent/TFace/tree/master/tasks/cifp)|130M|          [TFace](https://github.com/Tencent/TFace)           |  🔥🔥↑  | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_tencent_cifp_face.cpp) |
|[CenterLossFace](https://github.com/louis-she/center-loss.pytorch)| 280M |  [center-loss...](https://github.com/louis-she/center-loss.pytorch)           |  🔥🔥↑  | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_center_loss_face.cpp) |
|[SphereFace](https://github.com/clcarwin/sphereface_pytorch)| 80M |  [sphere...](https://github.com/clcarwin/sphereface_pytorch)   |  🔥🔥↑  | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-face-recognition) | *faceid* | ✅️ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_sphere_face.cpp) |
|[MobileFaceNet](https://github.com/Xiaoccer/MobileFaceNet_Pytorch)| 3.8M |  [MobileFace...](https://github.com/Xiaoccer/MobileFaceNet_Pytorch)           |  🔥🔥↑  | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_mobile_facenet.cpp) |
|[CavaGhostArcFace](https://github.com/cavalleria/cavaface.pytorch)| 15M | [cavaface...](https://github.com/cavalleria/cavaface.pytorch) |  🔥🔥↑  | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-face-recognition) | *faceid* |  ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_cava_ghost_arcface.cpp) |
|[CavaCombinedFace](https://github.com/cavalleria/cavaface.pytorch)| 250M | [cavaface...](https://github.com/cavalleria/cavaface.pytorch) |  🔥🔥↑  | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_cava_combined_face.cpp) |
|[MobileSEFocalFace](https://github.com/grib0ed0v/face_recognition.pytorch)|4.5M| [face_recog...](https://github.com/grib0ed0v/face_recognition.pytorch) | 🔥🔥↑ | [![](https://img.shields.io/badge/NCNN-done-yellow.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-face-recognition) | *faceid* | ✅ |  [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_mobilese_focal_face.cpp) |


|Class|Size|From|Awesome|File|Type|State|Usage|  
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[GlintArcFace](https://github.com/deepinsight/insightface/tree/master/recognition/arcface_torch)|92M|  [insightface](https://github.com/deepinsight/insightface)   | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_glint_arcface.cpp) |
|[GlintCosFace](https://github.com/deepinsight/insightface/tree/master/recognition/arcface_torch)|92M|  [insightface](https://github.com/deepinsight/insightface)   | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_glint_cosface.cpp) |
|[GlintPartialFC](https://github.com/deepinsight/insightface/tree/master/recognition/partial_fc)|170M|  [insightface](https://github.com/deepinsight/insightface)   | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_glint_partial_fc.cpp) |
|[FaceNet](https://github.com/timesler/facenet-pytorch)|89M| [facenet...](https://github.com/timesler/facenet-pytorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_facenet.cpp) |
|[FocalArcFace](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch)|166M| [face.evoLVe...](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_focal_arcface.cpp) |
|[FocalAsiaArcFace](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch)|166M| [face.evoLVe...](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_focal_asia_arcface.cpp) |
|[TencentCurricularFace](https://github.com/Tencent/TFace/tree/master/tasks/distfc)|249M|          [TFace](https://github.com/Tencent/TFace)           |  🔥🔥↑  | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_tencent_curricular_face.cpp) |
|[TencentCifpFace](https://github.com/Tencent/TFace/tree/master/tasks/cifp)|130M|          [TFace](https://github.com/Tencent/TFace)           |  🔥🔥↑  | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_tencent_cifp_face.cpp) |
|[CenterLossFace](https://github.com/louis-she/center-loss.pytorch)| 280M |  [center-loss...](https://github.com/louis-she/center-loss.pytorch)           |  🔥🔥↑  | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_center_loss_face.cpp) |
|[SphereFace](https://github.com/clcarwin/sphereface_pytorch)| 80M |  [sphere...](https://github.com/clcarwin/sphereface_pytorch)   |  🔥🔥↑  | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-face-recognition) | *faceid* | ✅️ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_sphere_face.cpp) |
|[MobileFaceNet](https://github.com/Xiaoccer/MobileFaceNet_Pytorch)| 3.8M |  [MobileFace...](https://github.com/Xiaoccer/MobileFaceNet_Pytorch)           |  🔥🔥↑  | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_mobile_facenet.cpp) |
|[CavaGhostArcFace](https://github.com/cavalleria/cavaface.pytorch)| 15M | [cavaface...](https://github.com/cavalleria/cavaface.pytorch) |  🔥🔥↑  | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-face-recognition) | *faceid* |  ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_cava_ghost_arcface.cpp) |
|[CavaCombinedFace](https://github.com/cavalleria/cavaface.pytorch)| 250M | [cavaface...](https://github.com/cavalleria/cavaface.pytorch) |  🔥🔥↑  | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-face-recognition) | *faceid* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_cava_combined_face.cpp) |
|[MobileSEFocalFace](https://github.com/grib0ed0v/face_recognition.pytorch)|4.5M| [face_recog...](https://github.com/grib0ed0v/face_recognition.pytorch) | 🔥🔥↑ | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.tnn.md#lite.ai.toolkit.hub.tnn-face-recognition) | *faceid* | ✅ |  [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_mobilese_focal_face.cpp) |


* Matting.

|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[RobustVideoMatting](https://github.com/PeterL1n/RobustVideoMatting)|14M| [RobustVideoMatting](https://github.com/PeterL1n/RobustVideoMatting)  |   🔥🔥🔥↑   | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-matting) | *matting* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_rvm.cpp) |

|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[RobustVideoMatting](https://github.com/PeterL1n/RobustVideoMatting)|14M| [RobustVideoMatting](https://github.com/PeterL1n/RobustVideoMatting)  |   🔥🔥🔥↑   | [![](https://img.shields.io/badge/MNN-done-blue.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.mnn.md#lite.ai.toolkit.hub.mnn-matting) | *matting* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_rvm.cpp) |

|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[RobustVideoMatting](https://github.com/PeterL1n/RobustVideoMatting)|14M| [RobustVideoMatting](https://github.com/PeterL1n/RobustVideoMatting)  |   🔥🔥🔥↑   | [![](https://img.shields.io/badge/NCNN-failed-red.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.ncnn-matting) | *matting* | ⚠️ | [code](https://github.com/DefTruth/lite.ai.toolkit/blob/main/lite/ncnn/cv/ncnn_rvm.cpp) |

Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[RobustVideoMatting](https://github.com/PeterL1n/RobustVideoMatting)|14M| [RobustVideoMatting](https://github.com/PeterL1n/RobustVideoMatting)  |   🔥🔥🔥↑   | [![](https://img.shields.io/badge/TNN-done-pink.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.ncnn.md#lite.ai.toolkit.hub.tnn-matting) | *matting* | ✅️ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_rvm.cpp) |

<!-----
<details>
<summary> ⚠️ Expand More Details for Lite.AI.ToolKit's Model Zoo.</summary>
----->

* Face Detection.

|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[UltraFace](https://github.com/Linzaer/Ultra-Light-Fast-Generic-Face-Detector-1MB)|1.1M| [Ultra-Light...](https://github.com/Linzaer/Ultra-Light-Fast-Generic-Face-Detector-1MB) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-detection) | *face::detect* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_ultraface.cpp) |
|[RetinaFace](https://github.com/biubug6/Pytorch_Retinaface)|1.6M| [...Retinaface](https://github.com/biubug6/Pytorch_Retinaface) | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-detection) | *face::detect* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_retinaface.cpp) |
|[FaceBoxes](https://github.com/zisianw/FaceBoxes.PyTorch)|3.8M| [FaceBoxes](https://github.com/zisianw/FaceBoxes.PyTorch) | 🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-detection) | *face::detect* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_faceboxes.cpp) |


* Face Alignment.

|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[PFLD](https://github.com/Hsintao/pfld_106_face_landmarks)|1.0M| [pfld_106_...](https://github.com/Hsintao/pfld_106_face_landmarks) |  🔥🔥↑  | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-alignment) | *face::align* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_pfld.cpp) |
|[PFLD98](https://github.com/polarisZhao/PFLD-pytorch)|4.8M| [PFLD...](https://github.com/polarisZhao/PFLD-pytorch) | 🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-alignment) | *face::align* | ✅️ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_pfld98.cpp) |
|[MobileNetV268](https://github.com/cunjian/pytorch_face_landmark)|9.4M| [...landmark](https://github.com/cunjian/pytorch_face_landmark) | 🔥🔥↑ |  [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-alignment) | *face::align* | ✅️️ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_mobilenetv2_68.cpp) |
|[MobileNetV2SE68](https://github.com/cunjian/pytorch_face_landmark)|11M| [...landmark](https://github.com/cunjian/pytorch_face_landmark) | 🔥🔥↑ |  [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-alignment) | *face::align* | ✅️️ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_mobilenetv2_se_68.cpp) |
|[PFLD68](https://github.com/cunjian/pytorch_face_landmark)|2.8M| [...landmark](https://github.com/cunjian/pytorch_face_landmark) | 🔥🔥↑ |  [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-alignment) | *face::align* | ✅️ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_pfld68.cpp) |
|[FaceLandmark1000](https://github.com/Single430/FaceLandmark1000)|2.0M| [FaceLandm...](https://github.com/Single430/FaceLandmark1000) | 🔥↑ |  [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-alignment) | *face::align* | ✅️ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_face_landmarks_1000.cpp) |



* Head Pose Estimation.  

|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[FSANet](https://github.com/omasaht/headpose-fsanet-pytorch)|1.2M| [...fsanet...](https://github.com/omasaht/headpose-fsanet-pytorch) | 🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-head-pose-estimation) | *face::pose* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_fsanet.cpp) |


* Face Attributes.

|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[AgeGoogleNet](https://github.com/onnx/models/tree/master/vision/body_analysis/age_gender)|23M|        [onnx-models](https://github.com/onnx/models)         | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-attributes) | *face::attr* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_age_googlenet.cpp) |
|[GenderGoogleNet](https://github.com/onnx/models/tree/master/vision/body_analysis/age_gender)|23M|        [onnx-models](https://github.com/onnx/models)         | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-attributes) | *face::attr* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_gender_googlenet.cpp) |
|[EmotionFerPlus](https://github.com/onnx/models/blob/master/vision/body_analysis/emotion_ferplus)|33M|        [onnx-models](https://github.com/onnx/models)         | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-attributes) | *face::attr* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_emotion_ferplus.cpp) |
|[VGG16Age](https://github.com/onnx/models/tree/master/vision/body_analysis/age_gender)|514M|        [onnx-models](https://github.com/onnx/models)         | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-attributes) | *face::attr* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_vgg16_age.cpp) |
|[VGG16Gender](https://github.com/onnx/models/tree/master/vision/body_analysis/age_gender)|512M|        [onnx-models](https://github.com/onnx/models)         | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-attributes) | *face::attr* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_vgg16_gender.cpp) |
|[SSRNet](https://github.com/oukohou/SSR_Net_Pytorch)|190K| [SSR_Net...](https://github.com/oukohou/SSR_Net_Pytorch) | 🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-attributes) | *face::attr* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_ssrnet.cpp) |
|[EfficientEmotion7](https://github.com/HSE-asavchenko/face-emotion-recognition)|15M| [face-emo...](https://github.com/HSE-asavchenko/face-emotion-recognition) | 🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-attributes) | *face::attr* | ✅️ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_efficient_emotion7.cpp) |
|[EfficientEmotion8](https://github.com/HSE-asavchenko/face-emotion-recognition)|15M| [face-emo...](https://github.com/HSE-asavchenko/face-emotion-recognition) | 🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-attributes) | *face::attr* | ✅  | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_efficient_emotion8.cpp) |
|[MobileEmotion7](https://github.com/HSE-asavchenko/face-emotion-recognition)|13M| [face-emo...](https://github.com/HSE-asavchenko/face-emotion-recognition) | 🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-attributes) | *face::attr* |  ✅  | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_mobile_emotion7.cpp) |
|[ReXNetEmotion7](https://github.com/HSE-asavchenko/face-emotion-recognition)|30M| [face-emo...](https://github.com/HSE-asavchenko/face-emotion-recognition) | 🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-face-attributes) | *face::attr* |  ✅  | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_rexnet_emotion7.cpp) |


* Classification.

|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[EfficientNetLite4](https://github.com/onnx/models/blob/master/vision/classification/efficientnet-lite4)|49M|        [onnx-models](https://github.com/onnx/models)         | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-classification)  | *classification* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_efficientnet_lite4.cpp) |
|[ShuffleNetV2](https://github.com/onnx/models/blob/master/vision/classification/shufflenet)|8.7M|        [onnx-models](https://github.com/onnx/models)         | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-classification)  | *classification* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_shufflenetv2.cpp) |
|[DenseNet121](https://pytorch.org/hub/pytorch_vision_densenet/)|30.7M|       [torchvision](https://github.com/pytorch/vision)       | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-classification)  | *classification* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_densenet.cpp) |
|[GhostNet](https://pytorch.org/hub/pytorch_vision_ghostnet/)|20M|       [torchvision](https://github.com/pytorch/vision)       | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-classification)  | *classification* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_ghostnet.cpp) |
|[HdrDNet](https://pytorch.org/hub/pytorch_vision_hardnet//)|13M|       [torchvision](https://github.com/pytorch/vision)       | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-classification) | *classification* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_hardnet.cpp) |
|[IBNNet](https://pytorch.org/hub/pytorch_vision_ibnnet/)|97M|       [torchvision](https://github.com/pytorch/vision)       | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-classification)  | *classification* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_ibnnet.cpp) |
|[MobileNetV2](https://pytorch.org/hub/pytorch_vision_mobilenet_v2/)|13M|       [torchvision](https://github.com/pytorch/vision)       | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-classification)  | *classification* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_mobilenetv2.cpp) |
|[ResNet](https://pytorch.org/hub/pytorch_vision_resnet/)|44M|       [torchvision](https://github.com/pytorch/vision)       | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-classification)  | *classification* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_resnet.cpp) |
|[ResNeXt](https://pytorch.org/hub/pytorch_vision_resnext/)|95M|       [torchvision](https://github.com/pytorch/vision)       | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-classification)  | *classification* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_resnext.cpp) |


* Segmentation.   

|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[DeepLabV3ResNet101](https://pytorch.org/hub/pytorch_vision_deeplabv3_resnet101/)|232M|       [torchvision](https://github.com/pytorch/vision)       | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-segmentation) | *segmentation* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_deeplabv3_resnet101.cpp) |
|[FCNResNet101](https://pytorch.org/hub/pytorch_vision_fcn_resnet101/)|207M|       [torchvision](https://github.com/pytorch/vision)       | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-segmentation) | *segmentation* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_fcn_resnet101.cpp) |


* Style Transfer.  

|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[FastStyleTransfer](https://github.com/onnx/models/blob/master/vision/style_transfer/fast_neural_style)|6.4M|        [onnx-models](https://github.com/onnx/models)         | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-style-transfer) | *style* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_fast_style_transfer.cpp) |


* Colorization.  

|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[Colorizer](https://github.com/richzhang/colorization)|123M|  [colorization](https://github.com/richzhang/colorization)   | 🔥🔥🔥↑ | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-colorization) | *colorization* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_colorizer.cpp) |


* Super Resolution.  

|Class|Size|From|Awesome|File|Type|State|Usage|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|[SubPixelCNN](https://github.com/niazwazir/SUB_PIXEL_CNN)|234K| [...PIXEL...](https://github.com/niazwazir/SUB_PIXEL_CNN)  |    🔥↑    | [![](https://img.shields.io/badge/onnx-done-brightgreen.svg)](https://github.com/DefTruth/lite.ai.toolkit/tree/main/docs/hub/lite.ai.toolkit.hub.onnx.md#lite.ai.toolkit.hub.onnx-super-resolution) | *resolution* | ✅ | [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_subpixel_cnn.cpp) |

<!-----
</details>
----->

## 3. Examples for Lite.AI.ToolKit.  

<div id="lite.ai.toolkit-Examples-for-Lite.AI.ToolKit"></div>

More examples can be found at [lite.ai.toolkit.examples](https://github.com/DefTruth/lite.ai.toolkit/tree/main/examples/lite/cv). Click ▶️ will show you more examples for the specific topic you are interested in.

<div id="lite.ai.toolkit-object-detection"></div>

#### Example0: Object Detection using [YoloV5](https://github.com/ultralytics/yolov5). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).
```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/yolov5s.onnx";
  std::string test_img_path = "../../../examples/lite/resources/test_lite_yolov5_1.jpg";
  std::string save_img_path = "../../../logs/test_lite_yolov5_1.jpg";

  auto *yolov5 = new lite::cv::detection::YoloV5(onnx_path); 
  std::vector<lite::types::Boxf> detected_boxes;
  cv::Mat img_bgr = cv::imread(test_img_path);
  yolov5->detect(img_bgr, detected_boxes);
  
  lite::utils::draw_boxes_inplace(img_bgr, detected_boxes);
  cv::imwrite(save_img_path, img_bgr);  
  
  delete yolov5;
}
```

The output is:
<div align='center'>
  <img src='logs/test_lite_yolov5_1.jpg' height="256px">
  <img src='logs/test_lite_yolov5_2.jpg' height="256px">
</div>

Or you can use Newest 🔥🔥 ! YOLO series's detector [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) or [YoloR](https://github.com/WongKinYiu/yolor). They got the similar results.  

****

<div id="lite.ai.toolkit-matting"></div>  

#### Example1: Video Matting using [RobustVideoMatting2021🔥🔥🔥](https://github.com/PeterL1n/RobustVideoMatting). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).

```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/rvm_mobilenetv3_fp32.onnx";
  std::string video_path = "../../../examples/lite/resources/test_lite_rvm_0.mp4";
  std::string output_path = "../../../logs/test_lite_rvm_0.mp4";
  
  auto *rvm = new lite::cv::matting::RobustVideoMatting(onnx_path, 16); // 16 threads
  std::vector<lite::types::MattingContent> contents;
  
  // 1. video matting.
  rvm->detect_video(video_path, output_path, contents, false, 0.4f);
  
  delete rvm;
}
```
The output is:

<div align='center'>
  <img src='docs/resources/interviewi.gif' height="80px" width="150px">
  <img src='docs/resources/interview.gif' height="80px" width="150px">  
  <img src='docs/resources/dance3i.gif' height="80px" width="150px">
  <img src='docs/resources/dance3.gif' height="80px" width="150px">
  <br>
  <img src='docs/resources/teslai.gif' height="80px" width="150px">
  <img src='docs/resources/tesla.gif' height="80px" width="150px">  
  <img src='docs/resources/b5i.gif' height="80px" width="150px">
  <img src='docs/resources/b5.gif' height="80px" width="150px">
</div>


****

<div id="lite.ai.toolkit-face-alignment"></div>

#### Example2: 1000 Facial Landmarks Detection using [FaceLandmarks1000](https://github.com/Single430/FaceLandmark1000). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).
```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/FaceLandmark1000.onnx";
  std::string test_img_path = "../../../examples/lite/resources/test_lite_face_landmarks_0.png";
  std::string save_img_path = "../../../logs/test_lite_face_landmarks_1000.jpg";
    
  auto *face_landmarks_1000 = new lite::cv::face::align::FaceLandmark1000(onnx_path);

  lite::types::Landmarks landmarks;
  cv::Mat img_bgr = cv::imread(test_img_path);
  face_landmarks_1000->detect(img_bgr, landmarks);
  lite::utils::draw_landmarks_inplace(img_bgr, landmarks);
  cv::imwrite(save_img_path, img_bgr);
  
  delete face_landmarks_1000;
}
```
The output is:
<div align='center'>
  <img src='logs/test_lite_face_landmarks_1000.jpg' height="224px" width="224px">
  <img src='logs/test_lite_face_landmarks_1000_2.jpg' height="224px" width="224px">
  <img src='logs/test_lite_face_landmarks_1000_0.jpg' height="224px" width="224px">
</div>    

****  

<div id="lite.ai.toolkit-colorization"></div>

#### Example3: Colorization using [colorization](https://github.com/richzhang/colorization). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).
```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/eccv16-colorizer.onnx";
  std::string test_img_path = "../../../examples/lite/resources/test_lite_colorizer_1.jpg";
  std::string save_img_path = "../../../logs/test_lite_eccv16_colorizer_1.jpg";
  
  auto *colorizer = new lite::cv::colorization::Colorizer(onnx_path);
  
  cv::Mat img_bgr = cv::imread(test_img_path);
  lite::types::ColorizeContent colorize_content;
  colorizer->detect(img_bgr, colorize_content);
  
  if (colorize_content.flag) cv::imwrite(save_img_path, colorize_content.mat);
  delete colorizer;
}
```
The output is:

<div align='center'>
  <img src='examples/lite/resources/test_lite_colorizer_1.jpg' height="224px" width="224px">
  <img src='examples/lite/resources/test_lite_colorizer_2.jpg' height="224px" width="224px">
  <img src='examples/lite/resources/test_lite_colorizer_3.jpg' height="224px" width="224px">  
  <br> 
  <img src='logs/test_lite_siggraph17_colorizer_1.jpg' height="224px" width="224px">
  <img src='logs/test_lite_siggraph17_colorizer_2.jpg' height="224px" width="224px">
  <img src='logs/test_lite_siggraph17_colorizer_3.jpg' height="224px" width="224px">
</div>    

****

<div id="lite.ai.toolkit-face-recognition"></div>  

#### Example4: Face Recognition using [ArcFace](https://github.com/deepinsight/insightface/tree/master/recognition/arcface_torch). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).

```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/ms1mv3_arcface_r100.onnx";
  std::string test_img_path0 = "../../../examples/lite/resources/test_lite_faceid_0.png";
  std::string test_img_path1 = "../../../examples/lite/resources/test_lite_faceid_1.png";
  std::string test_img_path2 = "../../../examples/lite/resources/test_lite_faceid_2.png";

  auto *glint_arcface = new lite::cv::faceid::GlintArcFace(onnx_path);

  lite::types::FaceContent face_content0, face_content1, face_content2;
  cv::Mat img_bgr0 = cv::imread(test_img_path0);
  cv::Mat img_bgr1 = cv::imread(test_img_path1);
  cv::Mat img_bgr2 = cv::imread(test_img_path2);
  glint_arcface->detect(img_bgr0, face_content0);
  glint_arcface->detect(img_bgr1, face_content1);
  glint_arcface->detect(img_bgr2, face_content2);

  if (face_content0.flag && face_content1.flag && face_content2.flag)
  {
    float sim01 = lite::utils::math::cosine_similarity<float>(
        face_content0.embedding, face_content1.embedding);
    float sim02 = lite::utils::math::cosine_similarity<float>(
        face_content0.embedding, face_content2.embedding);
    std::cout << "Detected Sim01: " << sim  << " Sim02: " << sim02 << std::endl;
  }

  delete glint_arcface;
}
```

The output is:
<div align='center'>
  <img src='examples/lite/resources/test_lite_arcface_resnet_0.png' height="224px" width="224px">
  <img src='examples/lite/resources/test_lite_arcface_resnet_1.png' height="224px" width="224px">
  <img src='examples/lite/resources/test_lite_arcface_resnet_2.png' height="224px" width="224px">
</div>  

> Detected Sim01: 0.721159  Sim02: -0.0626267  

****

<div id="lite.ai.toolkit-face-detection"></div>

#### Example5: Face Detection using [UltraFace](https://github.com/Linzaer/Ultra-Light-Fast-Generic-Face-Detector-1MB). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).
```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/ultraface-rfb-640.onnx";
  std::string test_img_path = "../../../examples/lite/resources/test_lite_ultraface.jpg";
  std::string save_img_path = "../../../logs/test_lite_ultraface.jpg";

  auto *ultraface = new lite::cv::face::detect::UltraFace(onnx_path);

  std::vector<lite::types::Boxf> detected_boxes;
  cv::Mat img_bgr = cv::imread(test_img_path);
  ultraface->detect(img_bgr, detected_boxes);
  lite::utils::draw_boxes_inplace(img_bgr, detected_boxes);
  cv::imwrite(save_img_path, img_bgr);

  delete ultraface;
}
```
The output is:
<div align='center'>
  <img src='logs/test_lite_ultraface.jpg' height="224px" width="224px">
  <img src='logs/test_lite_ultraface_2.jpg' height="224px" width="224px">
  <img src='logs/test_lite_ultraface_3.jpg' height="224px" width="224px">
</div>  


<div id="lite.ai.toolkit-segmentation"></div>  
<div id="lite.ai.toolkit-face-attributes-analysis"></div>  
<div id="lite.ai.toolkit-image-classification"></div>  
<div id="lite.ai.toolkit-head-pose-estimation"></div>
<div id="lite.ai.toolkit-style-transfer"></div>

<details>
<summary> ⚠️ Expand All Examples for Each Topic in Lite.AI.ToolKit </summary>  

<details>
<summary> 3.1 Expand Examples for Object Detection.</summary>

#### 3.1 Object Detection using [YoloV5](https://github.com/ultralytics/yolov5). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).
```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/yolov5s.onnx";
  std::string test_img_path = "../../../examples/lite/resources/test_lite_yolov5_1.jpg";
  std::string save_img_path = "../../../logs/test_lite_yolov5_1.jpg";
  
  auto *yolov5 = new lite::cv::detection::YoloV5(onnx_path);
  std::vector<lite::types::Boxf> detected_boxes;
  cv::Mat img_bgr = cv::imread(test_img_path);
  yolov5->detect(img_bgr, detected_boxes);
  
  lite::utils::draw_boxes_inplace(img_bgr, detected_boxes);
  cv::imwrite(save_img_path, img_bgr);
  
  delete yolov5;
}
```

The output is:
<div align='center'>
  <img src='logs/test_lite_yolov5_1.jpg' height="256px">
  <img src='logs/test_lite_yolov5_2.jpg' height="256px">
</div>

Or you can use Newest 🔥🔥 ! YOLO series's detector [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) . They got the similar results.  

```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/yolox_s.onnx";
  std::string test_img_path = "../../../examples/lite/resources/test_lite_yolox_1.jpg";
  std::string save_img_path = "../../../logs/test_lite_yolox_1.jpg";

  auto *yolox = new lite::cv::detection::YoloX(onnx_path); 
  std::vector<lite::types::Boxf> detected_boxes;
  cv::Mat img_bgr = cv::imread(test_img_path);
  yolox->detect(img_bgr, detected_boxes);
  
  lite::utils::draw_boxes_inplace(img_bgr, detected_boxes);
  cv::imwrite(save_img_path, img_bgr);  
  
  delete yolox;
}
```
The output is:
<div align='center'>
  <img src='logs/test_lite_yolox_1.jpg' height="256px">
  <img src='logs/test_lite_yolox_2.jpg' height="256px">
</div>    

More classes for general object detection.
```c++
auto *detector = new lite::cv::detection::YoloX(onnx_path);  // Newest YOLO detector !!! 2021-07
auto *detector = new lite::cv::detection::YoloV4(onnx_path); 
auto *detector = new lite::cv::detection::YoloV3(onnx_path); 
auto *detector = new lite::cv::detection::TinyYoloV3(onnx_path); 
auto *detector = new lite::cv::detection::SSD(onnx_path); 
auto *detector = new lite::cv::detection::YoloV5(onnx_path); 
auto *detector = new lite::cv::detection::YoloR(onnx_path);  // Newest YOLO detector !!! 2021-05
auto *detector = new lite::cv::detection::TinyYoloV4VOC(onnx_path); 
auto *detector = new lite::cv::detection::TinyYoloV4COCO(onnx_path); 
auto *detector = new lite::cv::detection::ScaledYoloV4(onnx_path); 
auto *detector = new lite::cv::detection::EfficientDet(onnx_path); 
auto *detector = new lite::cv::detection::EfficientDetD7(onnx_path); 
auto *detector = new lite::cv::detection::EfficientDetD8(onnx_path); 
auto *detector = new lite::cv::detection::YOLOP(onnx_path);
auto *detector = new lite::cv::detection::NanoDet(onnx_path); // Super fast and tiny!
auto *detector = new lite::cv::detection::NanoDetEfficientNetLite(onnx_path); // Super fast and tiny!
```

</details>


<details>
<summary> 3.2 Expand Examples for Face Recognition.</summary>

#### 3.2 Face Recognition using [ArcFace](https://github.com/deepinsight/insightface/tree/master/recognition/arcface_torch). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).

```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/ms1mv3_arcface_r100.onnx";
  std::string test_img_path0 = "../../../examples/lite/resources/test_lite_faceid_0.png";
  std::string test_img_path1 = "../../../examples/lite/resources/test_lite_faceid_1.png";
  std::string test_img_path2 = "../../../examples/lite/resources/test_lite_faceid_2.png";

  auto *glint_arcface = new lite::cv::faceid::GlintArcFace(onnx_path);

  lite::types::FaceContent face_content0, face_content1, face_content2;
  cv::Mat img_bgr0 = cv::imread(test_img_path0);
  cv::Mat img_bgr1 = cv::imread(test_img_path1);
  cv::Mat img_bgr2 = cv::imread(test_img_path2);
  glint_arcface->detect(img_bgr0, face_content0);
  glint_arcface->detect(img_bgr1, face_content1);
  glint_arcface->detect(img_bgr2, face_content2);

  if (face_content0.flag && face_content1.flag && face_content2.flag)
  {
    float sim01 = lite::utils::math::cosine_similarity<float>(
        face_content0.embedding, face_content1.embedding);
    float sim02 = lite::utils::math::cosine_similarity<float>(
        face_content0.embedding, face_content2.embedding);
    std::cout << "Detected Sim01: " << sim  << " Sim02: " << sim02 << std::endl;
  }

  delete glint_arcface;
}
```

The output is:
<div align='center'>
  <img src='examples/lite/resources/test_lite_arcface_resnet_0.png' height="224px" width="224px">
  <img src='examples/lite/resources/test_lite_arcface_resnet_1.png' height="224px" width="224px">
  <img src='examples/lite/resources/test_lite_arcface_resnet_2.png' height="224px" width="224px">
</div>  

> Detected Sim01: 0.721159  Sim02: -0.0626267  

More classes for face recognition.
```c++
auto *recognition = new lite::cv::faceid::GlintCosFace(onnx_path);  // DeepGlint(insightface)
auto *recognition = new lite::cv::faceid::GlintArcFace(onnx_path);  // DeepGlint(insightface)
auto *recognition = new lite::cv::faceid::GlintPartialFC(onnx_path); // DeepGlint(insightface)
auto *recognition = new lite::cv::faceid::FaceNet(onnx_path);
auto *recognition = new lite::cv::faceid::FocalArcFace(onnx_path);
auto *recognition = new lite::cv::faceid::FocalAsiaArcFace(onnx_path);
auto *recognition = new lite::cv::faceid::TencentCurricularFace(onnx_path); // Tencent(TFace)
auto *recognition = new lite::cv::faceid::TencentCifpFace(onnx_path); // Tencent(TFace)
auto *recognition = new lite::cv::faceid::CenterLossFace(onnx_path);
auto *recognition = new lite::cv::faceid::SphereFace(onnx_path);
auto *recognition = new lite::cv::faceid::PoseRobustFace(onnx_path);
auto *recognition = new lite::cv::faceid::NaivePoseRobustFace(onnx_path);
auto *recognition = new lite::cv::faceid::MobileFaceNet(onnx_path); // 3.8Mb only !
auto *recognition = new lite::cv::faceid::CavaGhostArcFace(onnx_path);
auto *recognition = new lite::cv::faceid::CavaCombinedFace(onnx_path);
auto *recognition = new lite::cv::faceid::MobileSEFocalFace(onnx_path); // 4.5Mb only !
```

</details>


<details>
<summary> 3.3 Expand Examples for Segmentation.</summary>

#### 3.3 Segmentation using [DeepLabV3ResNet101](https://pytorch.org/hub/pytorch_vision_deeplabv3_resnet101/). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).
```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/deeplabv3_resnet101_coco.onnx";
  std::string test_img_path = "../../../examples/lite/resources/test_lite_deeplabv3_resnet101.png";
  std::string save_img_path = "../../../logs/test_lite_deeplabv3_resnet101.jpg";

  auto *deeplabv3_resnet101 = new lite::cv::segmentation::DeepLabV3ResNet101(onnx_path, 16); // 16 threads

  lite::types::SegmentContent content;
  cv::Mat img_bgr = cv::imread(test_img_path);
  deeplabv3_resnet101->detect(img_bgr, content);

  if (content.flag)
  {
    cv::Mat out_img;
    cv::addWeighted(img_bgr, 0.2, content.color_mat, 0.8, 0., out_img);
    cv::imwrite(save_img_path, out_img);
    if (!content.names_map.empty())
    {
      for (auto it = content.names_map.begin(); it != content.names_map.end(); ++it)
      {
        std::cout << it->first << " Name: " << it->second << std::endl;
      }
    }
  }
  delete deeplabv3_resnet101;
}
```

The output is:
<div align='center'>
  <img src='examples/lite/resources/test_lite_deeplabv3_resnet101.png' height="256px">
  <img src='logs/test_lite_deeplabv3_resnet101.jpg' height="256px">
</div> 

More classes for segmentation.
```c++
auto *segment = new lite::cv::segmentation::FCNResNet101(onnx_path);
```

</details>


<details>
<summary> 3.4 Expand Examples for Face Attributes Analysis.</summary>

#### 3.4 Age Estimation using [SSRNet](https://github.com/oukohou/SSR_Net_Pytorch) . Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).
```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/ssrnet.onnx";
  std::string test_img_path = "../../../examples/lite/resources/test_lite_ssrnet.jpg";
  std::string save_img_path = "../../../logs/test_lite_ssrnet.jpg";

  lite::cv::face::attr::SSRNet *ssrnet = new lite::cv::face::attr::SSRNet(onnx_path);

  lite::types::Age age;
  cv::Mat img_bgr = cv::imread(test_img_path);
  ssrnet->detect(img_bgr, age);
  lite::utils::draw_age_inplace(img_bgr, age);
  cv::imwrite(save_img_path, img_bgr);
  std::cout << "Default Version Done! Detected SSRNet Age: " << age.age << std::endl;

  delete ssrnet;
}
```
The output is:
<div align='center'>
  <img src='logs/test_lite_ssrnet.jpg' height="224px" width="224px">
  <img src='logs/test_lite_gender_googlenet.jpg' height="224px" width="224px">
  <img src='logs/test_lite_emotion_ferplus.jpg' height="224px" width="224px">
</div>    

More classes for face attributes analysis.
```c++
auto *attribute = new lite::cv::face::attr::AgeGoogleNet(onnx_path);  
auto *attribute = new lite::cv::face::attr::GenderGoogleNet(onnx_path); 
auto *attribute = new lite::cv::face::attr::EmotionFerPlus(onnx_path);
auto *attribute = new lite::cv::face::attr::VGG16Age(onnx_path);
auto *attribute = new lite::cv::face::attr::VGG16Gender(onnx_path);
auto *attribute = new lite::cv::face::attr::EfficientEmotion7(onnx_path); // 7 emotions, 15Mb only!
auto *attribute = new lite::cv::face::attr::EfficientEmotion8(onnx_path); // 8 emotions, 15Mb only!
auto *attribute = new lite::cv::face::attr::MobileEmotion7(onnx_path); // 7 emotions
auto *attribute = new lite::cv::face::attr::ReXNetEmotion7(onnx_path); // 7 emotions
```

</details>



<details>
<summary> 3.5 Expand Examples for Image Classification.</summary>

#### 3.5 1000 Classes Classification using [DenseNet](https://pytorch.org/hub/pytorch_vision_densenet/). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).
```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/densenet121.onnx";
  std::string test_img_path = "../../../examples/lite/resources/test_lite_densenet.jpg";

  auto *densenet = new lite::cv::classification::DenseNet(onnx_path);

  lite::types::ImageNetContent content;
  cv::Mat img_bgr = cv::imread(test_img_path);
  densenet->detect(img_bgr, content);
  if (content.flag)
  {
    const unsigned int top_k = content.scores.size();
    if (top_k > 0)
    {
      for (unsigned int i = 0; i < top_k; ++i)
        std::cout << i + 1
                  << ": " << content.labels.at(i)
                  << ": " << content.texts.at(i)
                  << ": " << content.scores.at(i)
                  << std::endl;
    }
  }
  delete densenet;
}
```

The output is:
<div align='center'>
  <img src='examples/lite/resources/test_lite_densenet.jpg' height="224px" width="224px">
  <img src='logs/test_lite_densenet.png' height="224px" width="500px">
</div>  

More classes for image classification.
```c++
auto *classifier = new lite::cv::classification::EfficientNetLite4(onnx_path);  
auto *classifier = new lite::cv::classification::ShuffleNetV2(onnx_path); 
auto *classifier = new lite::cv::classification::GhostNet(onnx_path);
auto *classifier = new lite::cv::classification::HdrDNet(onnx_path);
auto *classifier = new lite::cv::classification::IBNNet(onnx_path);
auto *classifier = new lite::cv::classification::MobileNetV2(onnx_path); 
auto *classifier = new lite::cv::classification::ResNet(onnx_path); 
auto *classifier = new lite::cv::classification::ResNeXt(onnx_path);
```

</details>



<details>
<summary> 3.6 Expand Examples for Face Detection.</summary>

#### 3.6 Face Detection using [UltraFace](https://github.com/Linzaer/Ultra-Light-Fast-Generic-Face-Detector-1MB). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).
```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/ultraface-rfb-640.onnx";
  std::string test_img_path = "../../../examples/lite/resources/test_lite_ultraface.jpg";
  std::string save_img_path = "../../../logs/test_lite_ultraface.jpg";

  auto *ultraface = new lite::cv::face::detect::UltraFace(onnx_path);

  std::vector<lite::types::Boxf> detected_boxes;
  cv::Mat img_bgr = cv::imread(test_img_path);
  ultraface->detect(img_bgr, detected_boxes);
  lite::utils::draw_boxes_inplace(img_bgr, detected_boxes);
  cv::imwrite(save_img_path, img_bgr);

  delete ultraface;
}
```
The output is:  
<div align='center'>
  <img src='logs/test_lite_ultraface.jpg' height="224px" width="224px">
  <img src='logs/test_lite_ultraface_2.jpg' height="224px" width="224px">
  <img src='logs/test_lite_ultraface_3.jpg' height="224px" width="224px">
</div>  

More classes for face detection.
```c++
auto *detector = new lite::face::detect::UltraFace(onnx_path);  // 1.1Mb only !
auto *detector = new lite::face::detect::FaceBoxes(onnx_path);  // 3.8Mb only ! 
auto *detector = new lite::face::detect::RetinaFace(onnx_path);  // 1.6Mb only ! CVPR2020
```

</details>


<details>
<summary> 3.7 Expand Examples for Colorization.</summary>

#### 3.7 Colorization using [colorization](https://github.com/richzhang/colorization). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).
```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/eccv16-colorizer.onnx";
  std::string test_img_path = "../../../examples/lite/resources/test_lite_colorizer_1.jpg";
  std::string save_img_path = "../../../logs/test_lite_eccv16_colorizer_1.jpg";
  
  auto *colorizer = new lite::cv::colorization::Colorizer(onnx_path);
  
  cv::Mat img_bgr = cv::imread(test_img_path);
  lite::types::ColorizeContent colorize_content;
  colorizer->detect(img_bgr, colorize_content);
  
  if (colorize_content.flag) cv::imwrite(save_img_path, colorize_content.mat);
  delete colorizer;
}
```
The output is:

<div align='center'>
  <img src='examples/lite/resources/test_lite_colorizer_1.jpg' height="224px" width="224px">
  <img src='examples/lite/resources/test_lite_colorizer_2.jpg' height="224px" width="224px">
  <img src='examples/lite/resources/test_lite_colorizer_3.jpg' height="224px" width="224px">  
  <br> 
  <img src='logs/test_lite_siggraph17_colorizer_1.jpg' height="224px" width="224px">
  <img src='logs/test_lite_siggraph17_colorizer_2.jpg' height="224px" width="224px">
  <img src='logs/test_lite_siggraph17_colorizer_3.jpg' height="224px" width="224px">
</div>  

</details>


<details>
<summary> 3.8 Expand Examples for Head Pose Estimation.</summary>

#### 3.8 Head Pose Estimation using [FSANet](https://github.com/omasaht/headpose-fsanet-pytorch). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).

```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/fsanet-var.onnx";
  std::string test_img_path = "../../../examples/lite/resources/test_lite_fsanet.jpg";
  std::string save_img_path = "../../../logs/test_lite_fsanet.jpg";

  auto *fsanet = new lite::cv::face::pose::FSANet(onnx_path);
  cv::Mat img_bgr = cv::imread(test_img_path);
  lite::types::EulerAngles euler_angles;
  fsanet->detect(img_bgr, euler_angles);
  
  if (euler_angles.flag)
  {
    lite::utils::draw_axis_inplace(img_bgr, euler_angles);
    cv::imwrite(save_img_path, img_bgr);
    std::cout << "yaw:" << euler_angles.yaw << " pitch:" << euler_angles.pitch << " row:" << euler_angles.roll << std::endl;
  }
  delete fsanet;
}
```

The output is:
<div align='center'>
  <img src='logs/test_lite_fsanet.jpg' height="224px" width="224px">
  <img src='logs/test_lite_fsanet_2.jpg' height="224px" width="224px">
  <img src='logs/test_lite_fsanet_3.jpg' height="224px" width="224px">
</div>  

</details>


<details>
<summary> 3.9 Expand Examples for Face Alignment.</summary>

#### 3.9 1000 Facial Landmarks Detection using [FaceLandmarks1000](https://github.com/Single430/FaceLandmark1000). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).
```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/FaceLandmark1000.onnx";
  std::string test_img_path = "../../../examples/lite/resources/test_lite_face_landmarks_0.png";
  std::string save_img_path = "../../../logs/test_lite_face_landmarks_1000.jpg";
    
  auto *face_landmarks_1000 = new lite::cv::face::align::FaceLandmark1000(onnx_path);

  lite::types::Landmarks landmarks;
  cv::Mat img_bgr = cv::imread(test_img_path);
  face_landmarks_1000->detect(img_bgr, landmarks);
  lite::utils::draw_landmarks_inplace(img_bgr, landmarks);
  cv::imwrite(save_img_path, img_bgr);
  
  delete face_landmarks_1000;
}
```
The output is:
<div align='center'>
  <img src='logs/test_lite_face_landmarks_1000.jpg' height="224px" width="224px">
  <img src='logs/test_lite_face_landmarks_1000_2.jpg' height="224px" width="224px">
  <img src='logs/test_lite_face_landmarks_1000_0.jpg' height="224px" width="224px">
</div>    

More classes for face alignment.
```c++
auto *align = new lite::cv::face::align::PFLD(onnx_path);  // 106 landmarks
auto *align = new lite::cv::face::align::PFLD98(onnx_path);  // 98 landmarks
auto *align = new lite::cv::face::align::PFLD68(onnx_path);  // 68 landmarks
auto *align = new lite::cv::face::align::MobileNetV268(onnx_path);  // 68 landmarks
auto *align = new lite::cv::face::align::MobileNetV2SE68(onnx_path);  // 68 landmarks
auto *align = new lite::cv::face::align::FaceLandmark1000(onnx_path);  // 1000 landmarks !
```

</details>


<details>
<summary> 3.10 Expand Examples for Style Transfer.</summary>

#### 3.10 Style Transfer using [FastStyleTransfer](https://github.com/onnx/models/tree/master/vision/style_transfer/fast_neural_style). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2).
```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/style-candy-8.onnx";
  std::string test_img_path = "../../../examples/lite/resources/test_lite_fast_style_transfer.jpg";
  std::string save_img_path = "../../../logs/test_lite_fast_style_transfer_candy.jpg";
  
  auto *fast_style_transfer = new lite::cv::style::FastStyleTransfer(onnx_path);
 
  lite::types::StyleContent style_content;
  cv::Mat img_bgr = cv::imread(test_img_path);
  fast_style_transfer->detect(img_bgr, style_content);

  if (style_content.flag) cv::imwrite(save_img_path, style_content.mat);
  delete fast_style_transfer;
}
```
The output is:

<div align='center'>
  <img src='examples/lite/resources/test_lite_fast_style_transfer.jpg' height="224px">
  <img src='logs/test_lite_fast_style_transfer_candy.jpg' height="224px">
  <img src='logs/test_lite_fast_style_transfer_mosaic.jpg' height="224px">  
  <br> 
  <img src='logs/test_lite_fast_style_transfer_pointilism.jpg' height="224px">
  <img src='logs/test_lite_fast_style_transfer_rain_princes.jpg' height="224px">
  <img src='logs/test_lite_fast_style_transfer_udnie.jpg' height="224px">
</div>

</details>


<details>
<summary> 3.11 Expand Examples for Image Matting.</summary>

#### 3.11 Video Matting using [RobustVideoMatting](https://github.com/PeterL1n/RobustVideoMatting). Download model from Model-Zoo[<sup>2</sup>](#lite.ai.toolkit-2). 

```c++
#include "lite/lite.h"

static void test_default()
{
  std::string onnx_path = "../../../hub/onnx/cv/rvm_mobilenetv3_fp32.onnx";
  std::string video_path = "../../../examples/lite/resources/test_lite_rvm_0.mp4";
  std::string output_path = "../../../logs/test_lite_rvm_0.mp4";
  
  auto *rvm = new lite::cv::matting::RobustVideoMatting(onnx_path, 16); // 16 threads
  std::vector<lite::types::MattingContent> contents;
  
  // 1. video matting.
  rvm->detect_video(video_path, output_path, contents);
  
  delete rvm;
}
```
The output is:

<div align='center'>
  <img src='docs/resources/interviewi.gif' height="200px" width="200px">
  <img src='docs/resources/interview.gif' height="200px" width="200px">  
  <img src='docs/resources/dance3i.gif' height="200px" width="200px">
  <img src='docs/resources/dance3.gif' height="200px" width="200px">
  <br>
  <img src='docs/resources/teslai.gif' height="200px" width="200px">
  <img src='docs/resources/tesla.gif' height="200px" width="200px">  
  <img src='docs/resources/b5i.gif' height="200px" width="200px">
  <img src='docs/resources/b5.gif' height="200px" width="200px">
</div>


</details>

</details>


## 4. Lite.AI.ToolKit API Docs.

<div id="lite.ai.toolkit-Lite.AI.ToolKit-API-Docs"></div>

### 4.1 Default Version APIs.  
More details of Default Version APIs can be found at [api.default.md](https://github.com/DefTruth/lite.ai.toolkit/blob/main/docs/api/api.default.md) . For examples, the interface for YoloV5 is:

> `lite::cv::detection::YoloV5`
```c++
void detect(const cv::Mat &mat, std::vector<types::Boxf> &detected_boxes, 
            float score_threshold = 0.25f, float iou_threshold = 0.45f,
            unsigned int topk = 100, unsigned int nms_type = NMS::OFFSET);
```


<details>
<summary> Expand for ONNXRuntime, MNN, NCNN and TNN version APIs.</summary>

### 4.2 ONNXRuntime Version APIs.  
More details of ONNXRuntime Version APIs can be found at [api.onnxruntime.md](https://github.com/DefTruth/lite.ai.toolkit/blob/main/docs/api/api.onnxruntime.md) . For examples, the interface for YoloV5 is:

> `lite::onnxruntime::cv::detection::YoloV5`
```c++
void detect(const cv::Mat &mat, std::vector<types::Boxf> &detected_boxes, 
            float score_threshold = 0.25f, float iou_threshold = 0.45f,
            unsigned int topk = 100, unsigned int nms_type = NMS::OFFSET);
```


### 4.3 MNN Version APIs. 

(*todo*⚠️: Not implementation now, coming soon.)  

> `lite::mnn::cv::detection::YoloV5`

> `lite::mnn::cv::detection::YoloV4`

> `lite::mnn::cv::detection::YoloV3`

> `lite::mnn::cv::detection::SSD`  

...


### 4.4 NCNN Version APIs.

(*todo*⚠️: Not implementation now, coming soon.)

> `lite::ncnn::cv::detection::YoloV5`

> `lite::ncnn::cv::detection::YoloV4`

> `lite::ncnn::cv::detection::YoloV3`

> `lite::ncnn::cv::detection::SSD`

...

### 4.5 TNN Version APIs.

(*todo*⚠️: Not implementation now, coming soon.)

> `lite::tnn::cv::detection::YoloV5`

> `lite::tnn::cv::detection::YoloV4`

> `lite::tnn::cv::detection::YoloV3`

> `lite::tnn::cv::detection::SSD`

...

</details>



## 5. Other Docs.  

<div id="lite.ai.toolkit-Other-Docs"></div>  
<div id="lite.ai.toolkit-1"></div>

<details>
<summary> Expand More Details for Other Docs.</summary>

### 5.1 Docs for ONNXRuntime. 
* [Rapid implementation of your inference using BasicOrtHandler](https://github.com/DefTruth/lite.ai.toolkit/blob/main/docs/ort/ort_handler.zh.md)  
* [Some very useful onnxruntime c++ interfaces](https://github.com/DefTruth/lite.ai.toolkit/blob/main/docs/ort/ort_useful_api.zh.md)  
* [How to compile a single model in this library you needed](https://github.com/DefTruth/lite.ai.toolkit/blob/main/docs/ort/ort_build_single.zh.md)
* [How to convert SubPixelCNN to ONNX and implements with onnxruntime c++](https://github.com/DefTruth/lite.ai.toolkit/blob/main/docs/ort/ort_subpixel_cnn.zh.md)
* [How to convert Colorizer to ONNX and implements with onnxruntime c++](https://github.com/DefTruth/lite.ai.toolkit/blob/main/docs/ort/ort_colorizer.zh.md)
* [How to convert SSRNet to ONNX and implements with onnxruntime c++](https://github.com/DefTruth/lite.ai.toolkit/blob/main/docs/ort/ort_ssrnet.zh.md)
* [How to convert YoloV3 to ONNX and implements with onnxruntime c++](https://github.com/DefTruth/lite.ai.toolkit/blob/main/docs/ort/ort_yolov3.zh.md)
* [How to convert YoloV5 to ONNX and implements with onnxruntime c++](https://github.com/DefTruth/lite.ai.toolkit/blob/main/docs/ort/ort_yolov5.zh.md)


### 5.2 Docs for [third_party](https://github.com/DefTruth/lite.ai.toolkit/tree/main/third_party).  
Other build documents for different engines and different targets will be added later.


|Library|Target|Docs|
|:---:|:---:|:---:|
|OpenCV| mac-x86_64 | [opencv-mac-x86_64-build.zh.md](https://github.com/DefTruth/lite.ai.toolkit/blob/main/docs/third_party/opencv-mac-x86_64-build.zh.md) |
|OpenCV| android-arm | [opencv-static-android-arm-build.zh.md](https://github.com/DefTruth/lite.ai.toolkit/blob/main/docs/third_party/opencv-static-android-arm-build.zh.md) |
|onnxruntime| mac-x86_64 | [onnxruntime-mac-x86_64-build.zh.md](https://github.com/DefTruth/lite.ai.toolkit/blob/main/docs/third_party/onnxruntime-mac-x86_64-build.zh.md) |
|onnxruntime| android-arm | [onnxruntime-android-arm-build.zh.md](https://github.com/DefTruth/lite.ai.toolkit/blob/main/docs/third_party/onnxruntime-android-arm-build.zh.md) |
|NCNN| mac-x86_64 | todo⚠️ |
|MNN| mac-x86_64 | todo⚠️ |
|TNN| mac-x86_64 | todo⚠️ |

</details>

## 6. License.

<div id="lite.ai.toolkit-License"></div>

The code of [Lite.AI.ToolKit](#lite.ai.toolkit-Introduction) is released under the GPL-3.0 License.


## 7. References.  

<div id="lite.ai.toolkit-References"></div>

Many thanks to these following projects. All the Lite.AI.ToolKit's models are sourced from these repos. 

* [RobustVideoMatting](https://github.com/PeterL1n/RobustVideoMatting) (🔥🔥🔥new!!↑)
* [nanodet](https://github.com/RangiLyu/nanodet) (🔥🔥🔥↑)   
* [YOLOX](https://github.com/Megvii-BaseDetection/YOLOX) (🔥🔥🔥new!!↑)
* [YOLOP](https://github.com/hustvl/YOLOP) (🔥🔥new!!↑)
* [YOLOR](https://github.com/WongKinYiu/yolor) (🔥🔥new!!↑)
* [ScaledYOLOv4](https://github.com/WongKinYiu/ScaledYOLOv4) (🔥🔥🔥↑)
* [insightface](https://github.com/deepinsight/insightface) (🔥🔥🔥↑)
* [yolov5](https://github.com/ultralytics/yolov5) (🔥🔥💥↑)
* [TFace](https://github.com/Tencent/TFace) (🔥🔥↑)
* [YOLOv4-pytorch](https://github.com/argusswift/YOLOv4-pytorch) (🔥🔥🔥↑)
* [Ultra-Light-Fast-Generic-Face-Detector-1MB](https://github.com/Linzaer/Ultra-Light-Fast-Generic-Face-Detector-1MB) (🔥🔥🔥↑)  

<details>
<summary> Expand for More References.</summary>  

* [headpose-fsanet-pytorch](https://github.com/omasaht/headpose-fsanet-pytorch) (🔥↑)
* [pfld_106_face_landmarks](https://github.com/Hsintao/pfld_106_face_landmarks) (🔥🔥↑)
* [onnx-models](https://github.com/onnx/models) (🔥🔥🔥↑)
* [SSR_Net_Pytorch](https://github.com/oukohou/SSR_Net_Pytorch) (🔥↑)
* [colorization](https://github.com/richzhang/colorization) (🔥🔥🔥↑)
* [SUB_PIXEL_CNN](https://github.com/niazwazir/SUB_PIXEL_CNN) (🔥↑)
* [torchvision](https://github.com/pytorch/vision) (🔥🔥🔥↑)
* [facenet-pytorch](https://github.com/timesler/facenet-pytorch) (🔥↑)
* [face.evoLVe.PyTorch](https://github.com/ZhaoJ9014/face.evoLVe.PyTorch) (🔥🔥🔥↑)
* [center-loss.pytorch](https://github.com/louis-she/center-loss.pytorch) (🔥🔥↑)
* [sphereface_pytorch](https://github.com/clcarwin/sphereface_pytorch) (🔥🔥↑)
* [DREAM](https://github.com/penincillin/DREAM) (🔥🔥↑)
* [MobileFaceNet_Pytorch](https://github.com/Xiaoccer/MobileFaceNet_Pytorch) (🔥🔥↑)
* [cavaface.pytorch](https://github.com/cavalleria/cavaface.pytorch) (🔥🔥↑)
* [CurricularFace](https://github.com/HuangYG123/CurricularFace) (🔥🔥↑)
* [face-emotion-recognition](https://github.com/HSE-asavchenko/face-emotion-recognition) (🔥↑)
* [face_recognition.pytorch](https://github.com/grib0ed0v/face_recognition.pytorch) (🔥🔥↑)
* [PFLD-pytorch](https://github.com/polarisZhao/PFLD-pytorch) (🔥🔥↑)
* [pytorch_face_landmark](https://github.com/cunjian/pytorch_face_landmark) (🔥🔥↑)
* [FaceLandmark1000](https://github.com/Single430/FaceLandmark1000) (🔥🔥↑)
* [Pytorch_Retinaface](https://github.com/biubug6/Pytorch_Retinaface) (🔥🔥🔥↑)
* [FaceBoxes](https://github.com/zisianw/FaceBoxes.PyTorch) (🔥🔥↑)  

</details>  

## 8. Citations. 

Cite it as follows if you use *Lite.AI.ToolKit*. 
```BibTeX
@misc{lite.ai.toolkit2021,
  title={lite.ai.toolkit: A lite C++ toolkit of awesome AI models.},
  url={https://github.com/DefTruth/lite.ai.toolkit},
  note={Open-source software available at https://github.com/DefTruth/lite.ai.toolkit},
  author={Yan Jun},
  year={2021}
}
```    

## 9. Notification.

If there is a model you are interested in and want to be supported by Lite.AI.ToolKit🚀🚀🌟, you can fork this repo and modify [TODOLIST.md](https://github.com/DefTruth/lite.ai.toolkit/tree/main/TODOLIST.md), then submit a PR~ I will review this PR and try to support this model in the future, but I don’t make sure this can be done. In addition, [MNN](https://github.com/alibaba/MNN), [NCNN](https://github.com/Tencent/ncnn) and [TNN](https://github.com/Tencent/TNN) support for some models will be added in the future, but due to operator compatibility and some other reasons, it is impossible to ensure that all models supported by [ONNXRuntime C++](https://github.com/microsoft/onnxruntime) can run through [MNN](https://github.com/alibaba/MNN), [NCNN](https://github.com/Tencent/ncnn) and [TNN](https://github.com/Tencent/TNN). So, if you want to use all the models supported by this repo and don't care about the performance gap of *1~2ms*, please use the implementation of ONNXRuntime version. [ONNXRuntime](https://github.com/microsoft/onnxruntime) is the default inference engine for this repo. However, you can follow the steps below if you want to build Lite.AI.ToolKit🚀🚀🌟 with [MNN](https://github.com/alibaba/MNN), [NCNN](https://github.com/Tencent/ncnn) or [TNN](https://github.com/Tencent/TNN) support (⚠️ NOT STABLE NOW! NOT RECOMMENDED!!!🤦)  

* change the `build.sh` with `DENABLE_MNN=ON`,`DENABLE_NCNN=ON` or `DENABLE_TNN=ON`, such as  
```shell
cd build && cmake \
  -DCMAKE_BUILD_TYPE=MinSizeRel \
  -DINCLUDE_OPENCV=ON \   # Whether to package OpenCV into lite.ai.toolkit, default ON; otherwise, you need to setup OpenCV yourself.
  -DENABLE_MNN=ON \       # Whether to build with MNN,  default OFF, only some models are supported now.
  -DENABLE_NCNN=OFF \     # Whether to build with NCNN, default OFF, only some models are supported now.
  -DENABLE_TNN=OFF \      # Whether to build with TNN,  default OFF, only some models are supported now.
  .. && make -j8
```  
* use the MNN, NCNN or TNN version interface, see [demo](https://github.com/DefTruth/lite.ai.toolkit/blob/main/examples/lite/cv/test_lite_nanodet.cpp), such as  
```C++
auto *nanodet = new lite::mnn::cv::detection::NanoDet(mnn_path);
auto *nanodet = new lite::tnn::cv::detection::NanoDet(proto_path, model_path);
auto *nanodet = new lite::ncnn::cv::detection::NanoDet(param_path, bin_path);
```

## 10. Related projects.
* [NanoDet.lite.ai.toolkit 🚀🚀🌟](https://github.com/DefTruth/nanodet.lite.ai.toolkit)
* [RobustVideoMatting.lite.ai.toolkit 🚀🚀🌟](https://github.com/DefTruth/RobustVideoMatting.lite.ai.toolkit)
* [YOLOX.lite.ai.toolkit 🚀🚀🌟](https://github.com/DefTruth/yolox.lite.ai.toolkit)  
* [YOLOP.lite.ai.toolkit 🚀🚀🌟](https://github.com/DefTruth/yolop.lite.ai.toolkit)
  
  ```
lite::types::MattingContent content;
  cv::VideoCapture cap(0);
  cap.set(cv::CAP_PROP_FRAME_WIDTH, 640.0);
  cap.set(cv::CAP_PROP_FRAME_HEIGHT, 480.0);
  while (1) {
      cv::Mat frame; //定义Mat变量，用来存储每一帧 
      cap >> frame; //读取当前帧方法一 
      //cap.read(frame); //读取当前帧方法二 
      // 1. video matting.
      rvm->detect(frame, content, 0.3);
      cv::imshow("视频显示", content.merge_mat); //显示一帧画面 
      cv::waitKey(30); //延时30ms 
  }
  ```
