  ## Exercise 4.16
* 姓名：王硕
* 学号：2015301020103
#### 1.摘要
研究一个简单的三体：地球，木星和太阳。
#### 2.正文    
三体问题是天体力学中的基本力学模型。它是指三个质量、初始位置和初始速度都是任意的可视为质点的天体，在相互之间万有引力的作用下的运动规律问题。    


对3个天体进行分析，则第i个天体在t时刻的运动方程：     
<div align=center>
<img src="http://latex.codecogs.com/gif.latex?\overrightarrow{f_{i}}=\sum_{k=1}^{3}G\frac{m_{i}m_{k}}{r_{i,k}^{2}}\cdot\,\frac{\overrightarrow{n_{i,k}}}{n_{i,k}}">   ，     
</div><div align=center>
其中<img src="http://latex.codecogs.com/gif.latex?\overrightarrow{n_{i,k}}=\,\overrightarrow{n_{i,k}}=(r_{k}cos\theta\,_{k}-r_{i}cos\theta\,_{i},r_{k}sin\theta\,_{k}-r_{i}sin\theta\,_{i})">     
</div><div align=center>
<img src="http://latex.codecogs.com/gif.latex?r_{i,k}^{2}=r_{i}^{2}+r_{k}^{2}-2cos(\theta\,_{i}-\theta\,_{k})r_{i}r_{k}">     
</div><div align=center>
<img src="http://latex.codecogs.com/gif.latex?\frac{\mathrm{d}^{2}x_{i}\,}{\mathrm{d}\,t^{2}}=\overrightarrow{f_{i}}\cdot\,\overrightarrow{i}">    
</div><div align=center>
<img src="http://latex.codecogs.com/gif.latex?\frac{\mathrm{d}^{2}y_{i}\,}{\mathrm{d}\,t^{2}}=\overrightarrow{f_{i}}\cdot\,\overrightarrow{j}">    
</div>    

[代码](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/temp9.py)    

#### 3.图像   

 1 Jupiter=M    
 
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/F_a_9_1.png)    

 2 Jupiter=10M    
 
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/F_a_9_4.png)    

 3 Jupiter=100M    
 
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/F_a_9_2.png)    

 4 Jupiter=1000M    
 
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/F_a_9_3.png)   


 给太阳一个速度后    
    
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/F_b_9_1.png)     
 ### 4.总结
 木星的引力会使地球进动，当木星的质量过大时，整个系统会变得极不稳定，甚至相撞。
 ### 5.致谢
 参考了刘星辰学长的作业，在此表示感谢

