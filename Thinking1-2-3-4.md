## Thinking1	逻辑回归的假设条件是怎样的？

** 假设数据服从伯努利分布
假设1：数据服从伯努利分布
伯努力分布为离散型概率分布，如果成功，随机变量取值为1；如果失败，随机变量取值为0。成功概率记为p，失败概率为 q=1-p
假设2：正类的概率由sigmoid函数计算

## Thinking2	逻辑回归的损失函数是怎样的？
Cost函数与J函数是基于最大似然估计推导得到的, 求最大似然估计就是求使对数似然函数取最大值时的θ，可以使用梯度上升法求解.
关于统计模型中的参数的函数，表示模型参数中的似然性
给定输出x时，关于参数θ的似然函数L(θ|x)等于给定参数θ后变量X的概率

## Thinking3	逻辑回归如何进行分类？

设定一个阈值，判断正类概率是否大于该阈值，一般阈值是0.5，所以只用判断正类概率是否大于0.5即可
但是也需要根据样本的数据探索进行判断。

## Thinking4	为什么在训练中需要将高度相关的特征去掉？
1）可解释性更好
2）提高训练的速度，因为特征多，会增大训练的时间

