# AI-VITS-Howto
AI VITS Howto documents

## Q&A
#### 1、So-VITS-SVC 4.0 训练/推理常见报错和Q&A - 哔哩哔哩
[https://www.bilibili.com/read/cv22206231/]
```

```

## 一、Toolbox

### 1、AudioSlicer（音频分割）
[https://github.com/henrymaas/AudioSlicer.git]
```
A simple Audio Slicer in Python which can split .wav audio files into multiple .wav samples, based on silence detection.

批量分割：Git: https://github.com/maminge/AudioSlicerBat.git
RUN:
python AudioSegBat.py <Source-Wave-File-Dir> <Output-Sliced-Wave-File_dir>
```

### 2、Ultimate Vocal Remover（UVR）（人声音乐分离）
[https://github.com/Anjok07/ultimatevocalremovergui]
```
目前最强的人声分离工具
工具介绍：https://www.bilibili.com/read/cv24883000/
```

### 3、OCR

##### 3-1、Python Tesseract (Google Tesseract)
```
https://github.com/madmaze/pytesseract
Python-tesseract is a wrapper for Google's Tesseract-OCR Engine.
```
##### 3-2、Tesseract.js
```
https://tesseract.projectnaptha.com
https://github.com/naptha/tesseract.js#tesseractjs
Tesseract.js is a javascript library that gets words in almost any language out of images.
```

#### 3-2、PaddleOCR
```
https://github.com/PaddlePaddle/PaddleOCR
```

#### 3-3、TrOCR——基于transformer模型的OCR手写文字识别
```
https://zhuanlan.zhihu.com/p/656620989
```

### 4、Text Segmentation
```
https://github.com/koomri/text-segmentation

古文断句
https://github.com/ToolsForAncientChineseText/Text-segmentation


```

## 二、Audio To Text
### Whisper<br>
Whisper是一种强大的语音识别模型，能够将语音转换为文本，并支持多种语言。我们将使用 Whisper 将视频中的原始语音提取为文本，并通过翻译服务将其转换为目标语言的文本。

#### 1、OpenAI Whisper: (Mac/Linux)
[https://github.com/openai/whisper/tree/main]
```
```
#### 2、Whisper for Windows
2-1、Download：Whisper （CPU）
[https://github.com/Const-me/Whisper]
```
https://github.com/Const-me/Whisper
https://github.com/Const-me/Whisper/releases
Download：Model https://huggingface.co/ggerganov/whisper.cpp
https://github.com/ggerganov/whisper.cpp/tree/master/models
https://huggingface.co/ggerganov/whisper.cpp
```
2-2、Download：Whisper（GPU）
[https://github.com/guillaumekln/faster-whisper]
```
```
2-3、Whisper输出中文
[https://wulu.zone/posts/whisper-cn]
```
```

## 三、Text To Audio（train）

## 四、Text To Audio（run）

## 五、Text To Audio（Demos OR Project）
#### 1、原神语音包测试
在线测试：[https://huggingface.co/spaces/Plachta/VITS-Umamusume-voice-synthesizer]
```
原神语音包（中/日/韩/英）: https://pan.baidu.com/s/1dWtW7qpVacRTXswfMUMqFw?pwd=2qxc 提取码: 2qxc 
```
#### 2、AI声音克隆vits：一键启动包（VITS-fast-fine-tuning）

```
Download: 链接: https://pan.baidu.com/s/14z7V6n530MZiAMXr7KW3MA?pwd=6h88 提取码: 6h88 
https://docs.qq.com/doc/DT0x6dHd5WER6VExr
https://www.bilibili.com/read/cv25689788/
https://www.bilibili.com/video/BV1K94y1k7Bw/?share_source=copy_web&vd_source=b55b8a2cb4d0e92a42df58f6ee597187

Original Download:
环境+代码+权重文件打包（提取码：o89H）：
https://pan.baidu.com/s/11e7Tgm49_5MZt74BmQc4Ww?pwd=o89H
unzip password: cuijiahua.com
```

## 六、其它系统
###### VITS-fast-fine-tuning (AI声音克隆)
```
https://github.com/Plachtaa/VITS-fast-fine-tuning/
```
###### Others
```
MockingBird（Real Time Voice Clone）（效果差） 
你只需要提供一个人短短几秒钟的录音（3-10秒），就能模仿出那个人的声音。
https://github.com/babysor/MockingBird/tree/main
```
```
VALL-E X
https://github.com/Plachtaa/VALL-E-X/blob/master/README-ZH.md
实时语音Clone，该模型支持多种语言（英语、中文和日语）和零样本语音克隆，你只需要提供一个人短短几秒钟的录音（3-10秒），就能模仿出那个人的声音。
Demo(不成功): https://huggingface.co/spaces/Plachta/VALL-E-X
```
```
AI作画保姆级教程来了！逆天，太强了！
https://www.bilibili.com/video/BV1q84y1i78L/?share_source=copy_web&vd_source=b55b8a2cb4d0e92a42df58f6ee597187
```
```
Bert-Vits2:
https://github.com/fishaudio/Bert-VITS2
https://www.bilibili.com/video/BV1yz4y1M71e/?buvid=XYFCFA4F89A607273CA316B8F30FBDB21831C&is_story_h5=false&mid=1BdCQC4JGQbdG4lCFG58cw%3D%3D&p=1&plat_id=116&share_from=ugc&share_plat=android&share_session_id=4d499b7c-e423-4164-965a-13a15e1ccfbe&share_tag=s_i&unique_k=Ir2OG5d&up_id=284799364&vd_source=09c09be7267697fb21e6ec8f56b2016f
```
```
TTS-Vue（微软语音合成）Mac/win
https://loker-page.lgwawork.com
https://github.com/LokerL/tts-vue/releases/tag/1.9.15
```
```
长风4.2:
https://www.bilibili.com/video/BV1bN41117ot/?vd_source=09c09be7267697fb21e6ec8f56b2016f
```
```
Coqui TTS：（很奇怪）
https://github.com/coqui-ai/TTS
```
```
OpenAI Whisper + FFmpeg + TTS：动态实现跨语言视频音频翻译
https://zhuanlan.zhihu.com/p/631644803
```


