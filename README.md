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

（1）先修改PaddleSeg中的 dataset.py （注意删掉括号和括号中的中文）

（2）上传utils.py （注意删掉括号和括号中的中文）

（3）打开 “所有模型的链接.docx”，下载对应的config.yml进行训练

对应 模型及参数文件夹 及 B榜预测结果（对比度曾强后）
pred_0722_solution4_22000_77874_jpg # 0.77031
pred_0730_solution16_31000_enlage_ORC_Aunk_B_jpg # 0.76909
pred_0730_solution15_31000_enlage_dv3p_Aunk_B_jpg # 0.76538
pred_0730_solution16_17500_Aunk_B_jpg # 0.76677
pred_0720_solution2_10000_77842_jpg # 0.77004
pred_0718_solution1_16000_76161_jpg # 0.76223
pred_0726_solution12_15000_75331u_jpg # 0.76359
0803_solution17_57500_Aunk_B_jpg # 0.77094
pred_0804_solution19_60000_Aunk_B_jpg # 0.76701
pred_0804_solution18_37600_Aunk_B_jpg # 0.76324

程序2 需要

（1）打开 “所有模型的链接.docx”，下载对应的 模型 和 config.yml 进行预测

（2）以数据集的方式上传到notebook项目中进行解压

（3）将train.txt和val.txt放到data文件夹中，避免config.yml找不到文件报错

程序3 需要

（1）上传预测好的图片zip，解压后放入对应路径再进行对比对增强

程序4 需要

（2）上传对比度增强后的图片zip文件进行投票
