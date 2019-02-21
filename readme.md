| **解读论文**                                                 |
| ------------------------------------------------------------ |
| [**CCNet--于"阡陌交通"处超越恺明 Non-local**](https://mp.weixin.qq.com/s/l3TIZNfUYEIXpY3f5wrlXw) |
| 介绍了CCNet，这篇工作以何凯铭在2018年CVPR的工作“Non-local Neural Networks”为基础的改进工作，对于图像卷积，仅考虑了一个像素点和周围像素点的关系，这是一种局部的思想，而Non-local代表对于当前这个像素点，考虑其他所有像素点和当前像素点的相关关系，通过一种类似于attention的机制来实现（类似于graph attention neural networks）。而CCNet是专门为语义分割设计的十字形attention，相比于non local neural networks，他的运算复杂度大大减小（原为(H*W)^2，现为(H * W)*(H + W -1 )），因为它仅考虑当前点与其所在位置上的十字形的相关关系，但也能达到较好的效果，作者给出的原因是如果设计两层十字形attention的话，仍可以在任意两个点之间建立关系。这点设计可以借鉴 |
|                                                              |
|                                                              |







| 知识点                                                       |
| ------------------------------------------------------------ |
| [**分享神经网络中关于multi-task设计loss function的一些技巧**](https://mp.weixin.qq.com/s/7Jg-YvS3nvcPJ-zYhK96EA) |
|                                                              |
| [**一文道尽softmax loss及其变种**](https://mp.weixin.qq.com/s/cYcztl8N9JF-XXp9xLJIxg) |
|                                                              |





|      |
| ---- |
|      |
|      |
|      |

