## 随机行走
* 王硕
* 2015301020103    
#### 摘要
使用Python对随机过程进行了模拟。研究了一维与二维随机行走，发现它们是类似扩散的。并且模拟了二维随机行走的熵。    
#### 引言
随机行走（random walk）也称随机漫步，随机行走等是指基于过去的表现，无法预测将来的发展步骤和方向。核心概念是指任何无规则行走者所带的守恒量都各自对应着一个扩散运输定律 ，接近于布朗运动，是布朗运动理想的数学状态。一维情况下的随机行走问题，指的是一个粒子初始时刻位于原点，之后每次经过同样的时间间隔，其或者向左行走或者向右行走，两个方向的概率可能相同，也可能不同，步长可能一定也可能在一个范围内随机。其二维情况下则其每一步的方向任意，其它性质和一维情况相似。
    
#### 1.等概率的随机行走
每一步步长一定，向左向右的概率相等。假设有5000个相同的粒子，观察它们运动的平均性质。
它们距离原点的平均距离随步数的变化关系为    
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/w1.png)    
可见，这个系统中粒子距离原点的平均距离保持在0附近波动。按照概率论，粒子向左向右的概率相同，其距离原点的平均距离应该为0。这里数值结果和理论结果是一致的。
它们距离原点距离平方随步数的变化关系为    
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/w2.png)    
x的平方的平均值与步数近似为线性关系。这种线性关系在一维扩散系统中也有出现，表明这个随机行走的过程是“类扩散的”。
取每一步的步长为-1~+1之间的一个值，且取每一个值的概率是一定的。此时两个平均值随步数的变化关系为    
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/w3.png)    
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/w4.png)    

#### 2.不等概率的随机行走
令向右行走的概率为0.75，向左为0.25，固定步长为1，观察两种平均值随步长的变化关系为    
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/w5.png)    
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/w6.png)    
由图可知，x的平均值随步数线性增大，其平方的平均与步数成二次关系,与概率论的结论相同。
#### 3.扩散过程
选取大量随机行走者，模拟其在空间上密度随时间的变化关系，在一维情况下，可得    
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/d1.png)    
由图可知，随着时间的增大，密度曲线的峰值下降，范围增大，总面积保持不变。
在二维情况下，可得
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/d2.png)    
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/d3.png)    
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/d4.png)    
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/d5.png)    
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/d6.png)    

可见，二维情况下结论与一维时是一致的。这种行为符合我们对一个扩散过程的物理直觉，例如初始时刻在某点滴入一定的扩散物，之后扩散物以该点为中心向四方扩散，直到各处的密度相同。
#### 3.扩散过程熵的变化
我们考察二维系统点阵，熵与时间的关系为：    
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/d7.png)    
可见，随着时间增大，熵的值增大，但是其增长速度降低。最终它会收敛到一个定值。
