
电面
第一轮 Weighted Random Number
第二轮 LRU

Onsite
1. wildcard matching
2. best time to buy & sell stock II & III ,要求设计一个stack支持min, max, avg, mod 功能
3. Project Deep Dive, 这一轮是个director面, 因为我说的project好多内容都基于AWS那个面试官似乎不是特别懂, 问的问题都很基础, 然后他想了半天决定不继续deep dive了而是让我面一轮System design. 题目是设计一个 stock subscrip‍‍‍‍‍‌‍‍‌‍‌‌‌‌‌‌‍‌tion notification system
4. BQ
5. BQ




还是老配方
随机数和一些pro和 thre的问题


1. Process vs Thread
2. Hashmap
3. TokenGenerater, followup多线程
4. most challenge project

电话面试的几道题：1. 线程和进程；2. 延迟和吞吐量 就是Latency和Troughput；3. 不重复随机数生成器，随机数的范围可能会更新


现实一个array 转 circular linked list。 然后是寻找maximum sum in circular linkedlist

第二轮是技术店面，题目倒是不难，一共两道题：
1）求一个数组中最大的子数组和是多少，记得是原题‍‍‍‍‍‌‍‍‌‍‌‌‌‌‌‌‍‌
2）求一个树的立方根，返回整数部分即可，其实就是二分查找




1. Most chanllenging Project
2. Processes vs Thread How does processes communicate?
3. Latency vs Throughput

Random Number Generator without repeat
给定min和max，每次call generate()都会生成一个在(min, max)范围内的随机数，但是每个数字最多return一次。所有数字都用尽后重置。
follow up是增加一个update(min, max)方法可以更新min和max，但即使更新了之后也不能return已经return过的数。
还问了这个generator是不是thread safe，如果不用数组做怎么做