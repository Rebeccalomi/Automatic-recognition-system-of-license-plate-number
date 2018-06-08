此系统为本人毕业设计时所做的课题，解决的主要是蓝底白字的车牌号码的识别。在车牌检测和
定位阶段参考了EasyPR的思路，利用了HSV颜色空间和Sobel算子进行了车牌定位，没有用到CMser
定位是比较遗憾的。本文的研究内容为：
一、研究利用车牌颜色信息对图片或视频中的车牌区域进行定位
二、研究利用车牌边缘信息对图片或视频中的车牌区域进行定位
三、研究利用SVM算法对定位到的车牌区域和干扰区域进行分类
四、研究利用c++代码能力和思维对车牌区域的7个字符进行切割
五、研究利用深度学习中的卷积神经网络识别车牌上的每个字符
六、研究利用跨平台架构库wxWidgets为系统设计良好的用户界面

整个系统的开发流程如下：
![Alt text](https://github.com/BBuf/Automatic-recognition-system-of-license-plate-number/Screenshots/1.png)
整个系统的前端界面如下：
![Alt text](https://github.com/BBuf/Automatic-recognition-system-of-license-plate-number/Screenshots/2.png)
系统新增用户错误反馈功能如下：
![Alt text](https://github.com/BBuf/Automatic-recognition-system-of-license-plate-number/Screenshots/3.png)
![Alt text](https://github.com/BBuf/Automatic-recognition-system-of-license-plate-number/Screenshots/4.png)


研究成果和展望：
1、本系统利用颜色信息和边缘信息可以检测自然环境下95%以上车牌完好的蓝底白字车牌，并且车牌字符的识别准确率可以达到80%以上，且利用用户的错误反馈信息可以不断的自主学习提高车牌识别率。
2、但是本系统仍旧存在一些不足，当车牌为黄底黑字的教练车型时车牌的检测率会降低，以及出现纯蓝色车身的蓝底白字车牌时会出现检测不到车牌情况，仍需要进一步研究。
3、本系统仍处于实验室研究阶段，但只要给予训练的车牌号码数量足够多并且解决了上述两个问题后，可以应用在实际场景中进行车牌号码自动识别的工作。

