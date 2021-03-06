本项目欢迎提交issue, 欢迎PR.

### 简介   
为什么要创建这个项目？ 百度paddlepaddle工程化不是太好，为了方便大家在各种端上进行ocr推理，我们将它转换为onnx格式，使用python/c++/java/swift 将它移植到各个平台。

白富美OCR(名称由来：白富美→又白又漂亮→白漂), 模型来源于百度，富人家的千金 -- 白富美。
 
基于百度的开源PaddleOCR，任何人可以使用本推理库，也可以根据自己的需求使用百度的paddlepaddle 框架进行模型优化。 

### 当前进展
* C++范例(Windows/Linux/macOS): [demo](https://github.com/znsoftm/BaiPiaoOCR/tree/main/cpp)
* Jvm范例(Java/Kotlin): [demo](https://github.com/znsoftm/BaiPiaoOCR/tree/main/jvm)
* .Net范例(C#): [demo](https://github.com/znsoftm/BaiPiaoOCR/tree/main/dotnet)
* Android范例: [demo](https://github.com/znsoftm/BaiPiaoOCR/tree/main/android)
* IOS范例: 暂缺
* python范例: [demo](https://github.com/znsoftm/BaiPiaoOCR/tree/main/python)

### 模型训练
https://zhuanlan.zhihu.com/p/268761718

### 模型转换
[模型转换说明](https://github.com/znsoftm/BaiPiaoOCR/tree/main/models)

## 授权：
OCR模型版权归百度所有，其它工程代码版权归本仓库所有者所有。 本软件采用LGPL 授权方式，欢迎大家贡献代码，提交issue 甚至pr.

您可以通过QQ群联系到我们： 887298230 , 群号搜索不到时，请直接点链接加群： https://jq.qq.com/?_wv=1027&k=P9b3olx6

### C++/JVM Demo识别展示
![avatar](test_imgs/test_cpp.png)

### .Net Demo识别展示
![avatar](test_imgs/test_cs.png)

