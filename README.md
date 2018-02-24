## AICamera

AICamera is a demo app that was displayed at Facebook's F8 event.  The previous version (also on this repo) was getting quite old and attempted to demonstrate a build system that happened inside Android Studio.  This led to some hacky techniques and I decided to rewrite the demo with a prebuilt Caffe2 library (which can be built using `build_android.sh` in the Caffe2 source).
### Download
    git clone https://github.com/bwasti/AICamera.git
### Build
Click the green play button in Android Studio 2.2 and everything should build :)
### Tests
| Device             | Network       |  FPS  |
| ------------------ | ------------- | ----- |
| Samsung Galaxy S7  | SqueezeNet    |  5.8  |
| Google Pixel       | SqueezeNet    |  5.7  |



This is a 7-class classification demo with caffe2, the model is a Squeezenet1_1 I trained with pytorch and then transformed to caffe2 with onnx.

More detailed introduction on my zhihu:
    https://zhuanlan.zhihu.com/p/32342366
