# Dog_Classification
百度西交大宠物狗识别比赛baseline【keras】
    
    整体是按照杨培文大佬的开源做的：https://ypw.io/
    没有用Resnet50，因为用了发现效果不好。
    训练集进行了数据增强2倍，测试集进行了2倍增强得到三个测试集，分别预测最后取平均结果。
    线上成绩0.1867.
    机器配置：笔记本，显卡M1050ti，cpuI5。
    目的：为了保存代码。
