# HMM
#Hidden Markov Model for natural language processing
HMM模型相关的算法主要分为三类，分别解决三种问题：
（1）隐含状态的数量、隐含状态间的转移概率，根据可见状态链求得隐含状态链。
    在语音识别领域，我们可以称之为解码问题。它主要有两种解法，每个解法的结果可能各不相同，各自有各自的意义。
    第一种解法是求最大思然概率路径，也就是求得一个状态系列使得观测结果序列的概率最大；
    第二种解法是求每个观测结果是由某种状态产生的概率。
（2）隐含状态的数量、隐含状态间的转移概率，来计算观测序列的概率
（3）隐含状态的数量，根据观测结果计算隐含状态间的转移概率，

