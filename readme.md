| **解读论文**                                                 |
| :----------------------------------------------------------- |
| [**CCNet--于"阡陌交通"处超越恺明 Non-local**](https://mp.weixin.qq.com/s/l3TIZNfUYEIXpY3f5wrlXw) |
| 介绍了CCNet，这篇工作以何凯铭在2018年CVPR的工作“Non-local Neural Networks”为基础的改进工作，对于图像卷积，仅考虑了一个像素点和周围像素点的关系，这是一种局部的思想，而Non-local代表对于当前这个像素点，考虑其他所有像素点和当前像素点的相关关系，通过一种类似于attention的机制来实现（类似于graph attention neural networks）。而CCNet是专门为语义分割设计的十字形attention，相比于non local neural networks，他的运算复杂度大大减小（原为(H*W)^2，现为(H * W)*(H + W -1 )），因为它仅考虑当前点与其所在位置上的十字形的相关关系，但也能达到较好的效果，作者给出的原因是如果设计两层十字形attention的话，仍可以在任意两个点之间建立关系。这点设计可以借鉴 |
| [一图胜千言: 解读阿里的Deep Image CTR Model](https://mp.weixin.qq.com/s/JWxcwGLoqDNLmAs-Jt98Jg) |
| [带你读论文数据到文本生成的近期优质论文，我们为你挑选了这六篇](https://mp.weixin.qq.com/s/9YIZV4B2rEswydWLhNFc3A) |
| [5篇顶会论文带你了解知识图谱最新研究进展](https://mp.weixin.qq.com/s/nomVWAuvuxFJLWoxHoUCqg) |
| [**清华张敏教授: 个性化推荐的可解释性、鲁棒性和公平性( 附报告下载)**](https://mp.weixin.qq.com/s/RAQrW6Fchynbc1Rd9IcOJQ) |
| [**KDD 18 & AAAI 19 异构信息网络表示学习论文解读**](https://mp.weixin.qq.com/s/xyE9o8nx6TrabGGJwMzzIg) |
| [图分类：结合胶囊网络Capsule和图卷积GCN（附代码）](https://mp.weixin.qq.com/s/6vhFfSh2mveBiZXB1oZb1Q) |







| 知识点                                                       |
| ------------------------------------------------------------ |
| [**分享神经网络中关于multi-task设计loss function的一些技巧**](https://mp.weixin.qq.com/s/7Jg-YvS3nvcPJ-zYhK96EA) |
| [如何利用深度学习模型实现多任务学习？这里有三点经验](https://mp.weixin.qq.com/s/MPhKUosKZbLtVjJ1XYGXYA) |
| [一文道尽softmax loss及其变种](https://mp.weixin.qq.com/s/cYcztl8N9JF-XXp9xLJIxg) |
| [从最优化的角度看待 Softmax 损失函数](https://mp.weixin.qq.com/s/MTeuRYutMiCmthEAObyAIg) |
| [**图卷积网络到底怎么做，这是一份极简的Numpy实现**](https://mp.weixin.qq.com/s/sg9O761F0KHAmCPOfMW_kQ) |
| [AAAI 2019教程—361页PPT带你回顾最新词句Embedding技术和应用](https://mp.weixin.qq.com/s/caG7kwZfo2qpvLDbrvfpng) |
| [神经信息检索导论，微软研究员129页最新书册](https://mp.weixin.qq.com/s/5ba3EM6e9R-i3UpzUhm49w) |
| [一文解读NLP中的注意力机制](https://mp.weixin.qq.com/s/TM5poGwSGi5C9szO13GYxg) |
| [卷积有多少种？一文读懂深度学习中的各种卷积](https://mp.weixin.qq.com/s/Olliwe3ux77H4Vlsn4IrCw) |
| [机器学习中最最好用的提升方法：Boosting 与 AdaBoost](https://mp.weixin.qq.com/s/zx9eveRJ4b8EWxI7z4-f6w) |
|                                                              |



| 资源整理汇总                                                 |
| ------------------------------------------------------------ |
| [收藏最全中科大计算机学院课程资源（含答案）](https://mp.weixin.qq.com/s/q79wpijKxGW8V5sLfFIntw) |
|                                                              |
|                                                              |





| 作图工具                                                     |
| ------------------------------------------------------------ |
| [怎么画高大上的神经网络结构？试试这个！](https://mp.weixin.qq.com/s/UwPCDA89GH5X-HubeJddnQ) |
|                                                              |
|                                                              |



| 论文写作                                                     |
| ------------------------------------------------------------ |
| [一文教你如何快速高效阅读Paper（硕士生版）](https://mp.weixin.qq.com/s/u3D1RX-ZCfwNa0IATvX0ug) |
|                                                              |
|                                                              |





| 数据处理                                                     |
| ------------------------------------------------------------ |
| [数据清洗&预处理入门完整指南](https://mp.weixin.qq.com/s/r7ngZOM9tO-_OSfvs2aDJw) |
|                                                              |
|                                                              |



| PPT分享                                                      |
| ------------------------------------------------------------ |
| [带你全面认识自然语言处理三大特征抽取器](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247494178&idx=1&sn=3190dbf682a3315e55b5ff6801ff3f2c&chksm=e9e1e3a9de966abf7774459344a35dd6010dcf4cfbb45c1cc9b5324a76856c755850d4bf5f23&scene=0#rd) |
| [回顾腾讯信息流平台部高级研究员赖坤锋：语意匹配—搜索和推荐的幕后](https://mp.weixin.qq.com/s?__biz=MzU1NTUxNTM0Mg==&mid=2247490419&idx=3&sn=0b5a995f33aff85846f743c15577289b&chksm=fbd277d2cca5fec4157f35ed5762036e21afcb0f385c7aea19cd29bebeef49210f67a509d62a&mpshare=1&scene=1&srcid=#rd) |
|                                                              |



| 框架工具                                                     |
| ------------------------------------------------------------ |
| [Pytorch常见模型代码](https://github.com/ritchieng/the-incredible-pytorch) |
| [如何自动为IPython/Jupyter NoteBook 引入库](https://mp.weixin.qq.com/s/xZEIwTsfhkcQQBIJNqhPJg) |
| [PyTorch 中文手册 - 帮助你使用PyTorch进深度学习快速入门！](https://mp.weixin.qq.com/s/oNaDNcxGGOr7ZkY5sFuXvQ) |
| [微软开源项目提供企业级可扩展推荐系统最新实践指南](https://mp.weixin.qq.com/s/pBAnC06NQXhT3_q4jNimsQ) |

