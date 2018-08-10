# metrics
- accuracy（准确率）
- precision（精确率）
- recall（召回率）
- F1
## accuracy
accuracy需要得到的是此君分正确的人占总人数的比例

但accuracy有问题：如果两类相差悬殊 则可以耍赖：都分成其中占比超大的类

因此祭出其他的方法
## TP FN FP TN
T是猜对了

F是猜错了

P是预测为1

N是预测为0

FP：type I error

FN：type II error

## precision
检测准确的病人占所有被检测为病人的比率 即TP/(TP + FP)

在混淆矩阵中是对角线上元素比上纵行元素和


## recall
检测准确的病人占样本中所有病人的比率 即TP/(TP + FN)

在混淆矩阵中是对角线上元素比上横行元素和

## F1值
F1 = 2RP/（R + P）
