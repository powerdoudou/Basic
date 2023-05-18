# 李宏毅深度学习笔记：Batch Nor*ma*lization

本文是学习李宏毅老师讲解batch normalization[公开课](https://www.bilibili.com/video/av9770302/?p=10)的笔记。\
Batch Normalization的paper：[Batch Normalization: Accelerating Deep Network Training by Reducing Internal Covariate Shift](https://arxiv.org/abs/1502.03167v2)\
最后补充pytorch里面的nn.BatchNorm2d使用方法和注意事项。

## Feature Scaling

**Feature Scaling**指特征缩放，是将不同的feature缩放到相同的scale上。这里scale指的是取值范围。

1.  **Feature Scaling**的对training的影响\
    下图是一个简单的例子：
