# 第三届中国AI+创新创业大赛：半监督学习目标定位竞赛第6名方案


## 项目描述

![image](https://github.com/yongxinliao-hqu/PaddleSeg/blob/main/ReadmeImages/方法介绍.jpg)


![image](https://github.com/yongxinliao-hqu/PaddleSeg/blob/main/ReadmeImages/方法介绍2.jpg)


![image](https://github.com/yongxinliao-hqu/PaddleSeg/blob/main/ReadmeImages/方法介绍3.jpg)

## 项目结构
- 程序1 数据处理、训练及A榜预测
- 程序2 B榜预测 
- 程序3 增强对比度 
- 程序4 投票系统
- README.MD
- 所有模型的链接.docx
- 方法介绍.pdf


## 使用方法
一共有四个程序

程序1 需要

（1）先修改PaddleSeg中的 dataset.py

（2）上传utils.py

（3）打开 “所有模型的链接.docx”，下载对应的config.yml进行训练

注意删掉括号和括号中的中文

程序2 需要

（1）打开 “所有模型的链接.docx”，下载对应的 模型 和 config.yml 进行预测

（2）以数据集的方式上传到notebook项目中进行解压

（3）将train.txt和val.txt放到data文件夹中，避免config.yml找不到文件报错

程序3 需要

（1）上传预测好的图片zip，解压后放入对应路径再进行对比对增强

程序4 需要

（2）上传对比度增强后的图片zip文件进行投票
