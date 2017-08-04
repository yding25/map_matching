# MapMatching
It is just a brief description about this project 'Map Matching for Vehicle'.
这只是一个关于这个项目的简单描述

Map matching is an essential pre-process for many LBS applications, which projects a GPS point 
to an edge in a road network.
Map matching是许多基于位置应用的一个必要的预处理步骤，它是将一个gps点投射到路网的路段上去。

There are many famous methods, for example 'ST-Matching Algorithm'. 
现在有需要的著名的方法，比如ST-Matching算法（微软郑宇）。

Though ST-matching is a good method, it will cost many time to perform the temporal analysis 
which needs to find the shortest route from two nodes. 
虽然ST-Matching是一个好方法，不过它会花费大量的时间在判定两个node是否相连上，这个过程的判定是依据最短路线来的。

More information about ST-algorithm: http://m.www.cnblogs.com/LBSer/p/4612031.html#!comments
更多信息请见这个网址：http://m.www.cnblogs.com/LBSer/p/4612031.html#!comments



In this project, I will give three code versions and some datasets. 
在这个项目中，我将给出三个代码版本

In the first version, I find the matched result only based on the distance from the gps point to the edge, without other information. This method is fast but low-accuarcy.
在第一个版本中，我只通过gps点到edge的距离来寻找匹配结果，这个方法最快但是精确度很低。

In the second version, I will reproduce the ST-Matching Algorithm in Matlab.
在第二个版本中，我会用matlab复现ST算法。

The third verson is SD--Matching Algorithm, which is a novel, high-accuarcy and time saving method. 
第三个版本是我自己提出的新算法，我将其命名为SD算法。

The deadline that all work are put on this platform may be long.
这些工作会逐渐放在我的Github主页上，但是这个截止日期可能会很长。



Map_Matching_Version1.m是主函数

DivideDistrict.m和dis_node.m是里面调用的函数，可以不用考虑

SubRN.mat是将是分成9个小块的北京市路网，方便搜索。路网非常大，都到区县了(代码里对每一列的数据类型都有详细介绍)。

test_gps.mat是gps数据，因为保密性，只提供2000个point(代码里对每一列的数据类型都有详细介绍)。

如果有问题，请联系qq：1040515761@qq.com
