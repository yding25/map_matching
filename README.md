# MapMatching
It is just a brief description about this project.
这只是一个关于这个项目的简单描述

Map matching is an essential pre-process for many LBS applications, which is to project a GPS point 
to an edge in a road network.   
Map matching是许多基于位置应用的一个必要的预处理步骤，它是将一个gps点投射到路网的路段上去。

There are many famous methods, for example ST-matching. 
现在有需要的著名的方法，比如ST-Matching方法（微软郑宇）。

Though ST-matching is a good method, it will cost many time to perform the temporal analysis 
which need to find the shortest route. 
虽然ST-Matching是一个好方法，不过它会花费大量的时间在时间分析上，这个过程需要找到最短路线。

In this project, I will give two code versions. 
在这个项目中，我将给出两个代码版本

In the first version, I abandon the temporal analysis to cost less time in the cost of low accuracy, only use the spatial analysis.
在第一个版本中，我放弃了时间分析来追寻更少的运行时间，但是牺牲了准确率为代价。

The second verson is complete one, which I will use the temporal anaysis in.
第二个版本是一个完全的版本，我将使用时间分析。
