![MisakaTranslator](https://github.com/hanmin0822/MisakaTranslator/blob/master/MisakaTranslator/Resources/Background.jpg)

<h1 align="center">
  MisakaTranslator 御坂翻译器
  <br>
</h1>

<p align="center">
  <b>Galgame/文字游戏多语种实时机翻工具</b>
  <br>
  <b>开源 | 高效 | 易用</b>
  <br>
  <br>
</p>

<p align="center">
  <a href="/README.md">中文</a> •
  <a href="/README_EN.md">English</a>
</p>

~~MisakaTranslator的名字由来是因为本软件连接到了一万多名御坂妹妹所组成的『御坂网络』，利用其强大的计算能力来提供实时可靠的翻译（误）~~

演示视频：https://www.bilibili.com/video/av94082641

以上视频仅为测试版第一版功能，目前的实际功能和其他效果见最新版本！


## 软件功能及特点

* 兼容性强：支持`Hook+OCR`两种方式提取游戏文本，能适配绝大多数游戏
* 可离线：支持完全离线工作(`Hook模块离线、可选的Tesseract-OCR模块离线、三种离线翻译API`)
* 高度可拓展的文本修复：针对Hook提取到的重复文本提供多种去重方式
* 提供更好体验的在线API：提供多种在线API(`百度OCR+百度翻译+腾讯翻译(两种)+彩云翻译+两种公共接口翻译`)
* 更高的OCR精度：支持在提交OCR前对图片进行预处理（多种处理方法）
* 分词及字典：支持Mecab分词和字典功能，可针对单词进行查询
* 翻译优化系统：支持人名地名欲翻译，提高翻译质量，这个系统正在被不断完善
* 高效：使用C#开发，程序效率较使用Python开发的VNR要高
* 易用：UI亲切，易上手，有详细教程
* 更多功能，正在开发

## 帮助开发者

如果您对这个项目感兴趣，想提供任何帮助，欢迎联系作者。

作者的联系方式在下方。

## 本项目所使用到的其他开源项目

* [~~IgnaceMaes/MaterialSkin~~](https://github.com/IgnaceMaes/MaterialSkin) 
* [~~平原君关于MaterialSkin的fork~~](https://gitee.com/victorzhao/MaterialSkin)
* [~~kwwwvagaa/NetWinformControl~~](https://github.com/kwwwvagaa/NetWinformControl)
* [Artikash/Textractor](https://github.com/Artikash/Textractor)
* [JamesNK/Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json)
* [Config.Net](https://github.com/aloneguid/config)
* [charlesw/tesseract](https://github.com/charlesw/tesseract/)
* [tesseract-ocr/tesseract](https://github.com/tesseract-ocr/tesseract)
* [kekyo/MeCab.DotNet](https://github.com/kekyo/MeCab.DotNet)
* [HandyOrg/HandyControl](https://github.com/HandyOrg/HandyControl)
* [lgztx96/texthost](https://github.com/lgztx96/texthost)

## 本项目开发过程中使用到的重要参考文献

* [C#调用多种翻译API和使用Textractor提取文本](https://www.lgztx.com/) 
* [C#图像处理(二值化,灰阶)](https://blog.csdn.net/chaoguodong/article/details/7877312)
* [C#中使用全局键盘鼠标钩子](https://www.cnblogs.com/CJSTONE/p/4961865.html)

## 联系作者

E-Mail/QQ:512240272@qq.com

## 合作开发者

* [unlsycn](https://github.com/HumphreyDotSln) 
* [tpxxn](https://github.com/tpxxn)

## 项目团队成员

* 画师担当-百川行
* 官网制作-[Disviel](https://github.com/Disviel)

## 贡献者名单

感谢所有对本项目开发提供帮助的人！

* [点此查看贡献者名单](https://github.com/hanmin0822/MisakaTranslator/blob/master/THANKLIST.MD)

## 其他注意

2.0beta3之前的版本运行时需要调用Textractor的CLI版本读输出，但原版的控制台输出可能导致本软件无法读取或读取存在问题，针对CLI版本的修改如下，请自行编译后使用

* [hanmin0822/Textractor](https://github.com/hanmin0822/Textractor)

软件开发过程中使用到部分网络素材，如果侵犯到您的权益，请第一时间联系作者删除，谢谢！
