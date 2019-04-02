| **解读论文**                                                 |
| :----------------------------------------------------------- |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [**CCNet--于"阡陌交通"处超越恺明 Non-local**](https://mp.weixin.qq.com/s/l3TIZNfUYEIXpY3f5wrlXw) |
| 介绍了CCNet，这篇工作以何凯铭在2018年CVPR的工作“Non-local Neural Networks”为基础的改进工作，对于图像卷积，仅考虑了一个像素点和周围像素点的关系，这是一种局部的思想，而Non-local代表对于当前这个像素点，考虑其他所有像素点和当前像素点的相关关系，通过一种类似于attention的机制来实现（类似于graph attention neural networks）。而CCNet是专门为语义分割设计的十字形attention，相比于non local neural networks，他的运算复杂度大大减小（原为(H*W)^2，现为(H * W)*(H + W -1 )），因为它仅考虑当前点与其所在位置上的十字形的相关关系，但也能达到较好的效果，作者给出的原因是如果设计两层十字形attention的话，仍可以在任意两个点之间建立关系。这点设计可以借鉴 |
| [一图胜千言: 解读阿里的Deep Image CTR Model](https://mp.weixin.qq.com/s/JWxcwGLoqDNLmAs-Jt98Jg) |
| [带你读论文数据到文本生成的近期优质论文，我们为你挑选了这六篇](https://mp.weixin.qq.com/s/9YIZV4B2rEswydWLhNFc3A) |
| [5篇顶会论文带你了解知识图谱最新研究进展](https://mp.weixin.qq.com/s/nomVWAuvuxFJLWoxHoUCqg) |
| [**清华张敏教授: 个性化推荐的可解释性、鲁棒性和公平性( 附报告下载)**](https://mp.weixin.qq.com/s/RAQrW6Fchynbc1Rd9IcOJQ) |
| [**KDD 18 & AAAI 19 异构信息网络表示学习论文解读**](https://mp.weixin.qq.com/s/xyE9o8nx6TrabGGJwMzzIg) |
| [图分类：结合胶囊网络Capsule和图卷积GCN（附代码）](https://mp.weixin.qq.com/s/6vhFfSh2mveBiZXB1oZb1Q) |
| [注意力能提高模型可解释性？实验表明：并没有](https://mp.weixin.qq.com/s/LqjBFMXNl5KoUlfktp0w9w) |







| 知识点                                                       |
| ------------------------------------------------------------ |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [**分享神经网络中关于multi-task设计loss function的一些技巧**](https://mp.weixin.qq.com/s/7Jg-YvS3nvcPJ-zYhK96EA) |
| [如何利用深度学习模型实现多任务学习？这里有三点经验](https://mp.weixin.qq.com/s/MPhKUosKZbLtVjJ1XYGXYA) |
| [一文道尽softmax loss及其变种](https://mp.weixin.qq.com/s/cYcztl8N9JF-XXp9xLJIxg) |
| [从最优化的角度看待 Softmax 损失函数](https://mp.weixin.qq.com/s/MTeuRYutMiCmthEAObyAIg) |
| [**图卷积网络到底怎么做，这是一份极简的Numpy实现**](https://mp.weixin.qq.com/s/sg9O761F0KHAmCPOfMW_kQ) |
| [AAAI 2019教程—361页PPT带你回顾最新词句Embedding技术和应用](https://mp.weixin.qq.com/s/caG7kwZfo2qpvLDbrvfpng) |
| [[综述]神经信息检索导论，微软研究员129页最新书册](https://mp.weixin.qq.com/s/5ba3EM6e9R-i3UpzUhm49w) |
| [[综述]最新36页《贝叶斯非参学习综述》，机器学习内功修炼手册](https://mp.weixin.qq.com/s/bjyO4AS1Sjo09qNMpqf6JA) |
| [【综述】万字综述之生成对抗网络（GAN）](<https://mp.weixin.qq.com/s?__biz=MzIwMTc4ODE0Mw==&mid=2247495668&idx=1&sn=e7e959b2bdd7b2763b9207ccb80fa6bc&chksm=96ea3074a19db96208a51d26f7b5b4ef9c3a37a7799ec270becc77203de4294235041ede7206&mpshare=1&scene=1&srcid=&key=c0631fa9ad87741cc520ba6455929cad392803c0f9ea1d2bb04b5e2b359e08fd13e92d6e6ae34668ffcc3300d87bbb64130cc03e611800d6d612cf50882d91a55b8dd17e9c34c0e76b8ddb61ab882745&ascene=1&uin=MTI5ODUxMDk0NA%3D%3D&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=y93mW3Jy%2BZgcd1GQtje4Rb66rgLej%2BokV797xnereS4%2BchmCJi%2BIvyXlcrVYq0ch>) |
| [【综述】最新综述】无监督网络表示学习综述，附18页全文下载](<https://mp.weixin.qq.com/s?__biz=MzU2OTA0NzE2NA==&mid=2247508959&idx=1&sn=e5ef0e9344b2c344e8251729323f023c&chksm=fc8642cccbf1cbdae63432b74486f419d54fc718a0a0e8f3f136b0208c95f920aefd4ce859c2&scene=0&xtrack=1&key=54e754b9be6197c7eda23f08e912e25dddb00e41bd552f8111e699f83bca5dfea88546352b2e7920e9050e0bfe5c4ef6d52858aaedd0c99112c1f01aca0a06612252d83d278ce1d11542b63b053675ab&ascene=1&uin=MTI5ODUxMDk0NA%3D%3D&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=lxHeD4n4yFGLJjjKhJIfhVNUKmQx%2Fo8quenvQfVfdcCIYZwFnKy8wiz7DDwJudKq>) |
| [一文解读NLP中的注意力机制](https://mp.weixin.qq.com/s/TM5poGwSGi5C9szO13GYxg) |
| [卷积有多少种？一文读懂深度学习中的各种卷积](https://mp.weixin.qq.com/s/Olliwe3ux77H4Vlsn4IrCw) |
| [机器学习中最最好用的提升方法：Boosting 与 AdaBoost](https://mp.weixin.qq.com/s/zx9eveRJ4b8EWxI7z4-f6w) |
| [网络新闻真假难辨？机器学习来助你一臂之力](https://mp.weixin.qq.com/s/S0vUBFCfizjVe_L4SIrGqQ) |
| [Ruder博士答辩41页PPT，面向自然语言处理的神经网络迁移学习](https://mp.weixin.qq.com/s/0Zcrwi3WROzm19ApDZINMQ) |
| [CMU Russ教授《如何融合领域知识到深度学习中》, 38页ppt](https://mp.weixin.qq.com/s/87QkA36gXuEJeORVkR_ndQ)![1551255282854](readme.assets/1551255282854.png) |
| [利用pytorch计算wasserstein距离](https://github.com/dfdazac/wassdistance)![1551255282854](readme.assets/1551255282854.png) |
| [利用pytorch去implenment常见KG模型](https://github.com/DeepGraphLearning/KnowledgeGraphEmbedding) |
| [**常见模型的发展路线解析和代码**![1551255282854](readme.assets/1551255282854.png)](https://skymind.ai/wiki/attention-mechanism-memory-network) |
| [[综述]迁移自适应学习最新综述，附21页论文下载](https://mp.weixin.qq.com/s/nIV7n8o7t2F3j0XFr9v-vg) |
| [伯克利大学蒙特卡洛估计和重要性采样讲义](https://github.com/kevinzakka/monte-carlo)![1551255282854](readme.assets/1551255282854.png) |
| [AAAI2019 Tutorial 《图表示学习》, 180页PPT带你从入门到精通](https://mp.weixin.qq.com/s/xc_TnMLs3o2LQ8eM4naZDw)![1551255282854](readme.assets/1551255282854.png) |
| [知识图谱深度学习综述](https://wx.zsxq.com/mweb/views/topicdetail/topicdetail.html?topic_id=111182115221412&user_id=5448515554) |
| [【面试】机器学习算法中的概率方法](https://mp.weixin.qq.com/s?__biz=MzI4MDYzNzg4Mw==&mid=2247489053&idx=4&sn=bb477e2af97d0f4c0a1d11ae1b8a2af3&chksm=ebb42ec9dcc3a7dffef3cb633cce58c79d4d3c6b835394b43d64fc296908f5d277f549dc42c6&scene=0&xtrack=1&key=c0631fa9ad87741c7766f0b177ce4bd2d411750707800b6795a0dbc65d1c9c048dcd5ccd6f433dcc2b6dc5f66c54bf26f4869dd513960f4c333df6d1263ee3fba559c80115d85387c01c48cbc049d194&ascene=1&uin=MTI5ODUxMDk0NA%3D%3D&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=b7aCz5SYWACzEngozNpdsQ4hrW5EImxRRnOYIfoVdDcBHQdV1qeLQmwaDbEfZadx) |
| [【面试】75道常见AI面试题，看看你的知识盲点在哪？（附解析）](https://mp.weixin.qq.com/s?__biz=MzI4MDYzNzg4Mw==&mid=2247489053&idx=3&sn=f09ab8882a7df178e451b1f2561bbc19&chksm=ebb42ec9dcc3a7df8a32311f9502a26cb10b2439b0a2ac370017e87835c820ee25ca6e8ebc25&scene=0&xtrack=1&key=a9d4b584c784361897a3fe6e1145acfb6e956e4ed8079cffcb38d6b8eac56f21a68c8ac8e16a37d75012e40c1d5ada521776c1c8d84ac68683a21e061f51581e2befe735a4ee06802480a0af4f810f33&ascene=1&uin=MTI5ODUxMDk0NA%3D%3D&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=b7aCz5SYWACzEngozNpdsQ4hrW5EImxRRnOYIfoVdDcBHQdV1qeLQmwaDbEfZadx) |



| 资源整理汇总                                                 |
| ------------------------------------------------------------ |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [收藏最全中科大计算机学院课程资源（含答案）](https://mp.weixin.qq.com/s/q79wpijKxGW8V5sLfFIntw) |
| [一文洞悉Python必备50种算法（附解析）](https://mp.weixin.qq.com/s/Y1uCF-aWMj2FuVp_4auKyQ) |
|                                                              |





| 工具                                                         |
| ------------------------------------------------------------ |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [怎么画高大上的神经网络结构？试试这个！](https://mp.weixin.qq.com/s/UwPCDA89GH5X-HubeJddnQ) |
| [**hyperopt网络参数调整工具**](https://github.com/hyperopt/hyperopt)![1551255282854](readme.assets/1551255282854.png) |
| [SHERPA: A Python Hyperparameter Optimization Library（ tensorflow和keras的调参工具）](https://github.com/sherpa-ai/sherpa) |
| [paper with code 论文代码查询网站](https://paperswithcode.com)![1551255282854](readme.assets/1551255282854.png) |
| [GSP Toolbox](https://arxiv.org/pdf/1408.5781v1.pdf)![1551255282854](readme.assets/1551255282854.png) |



| 论文写作                                                     |
| ------------------------------------------------------------ |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [一文教你如何快速高效阅读Paper（硕士生版）](https://mp.weixin.qq.com/s/u3D1RX-ZCfwNa0IATvX0ug) |
| [Latex写作注意事项github项目](https://github.com/Wookai/paper-tips-and-tricks#tips-and-tricks-for-writing-scientific-papers) |
|                                                              |





| 数据处理                                                     |
| ------------------------------------------------------------ |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [数据清洗&预处理入门完整指南](https://mp.weixin.qq.com/s/r7ngZOM9tO-_OSfvs2aDJw) |
|                                                              |
|                                                              |



| PPT分享                                                      |
| ------------------------------------------------------------ |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [带你全面认识自然语言处理三大特征抽取器](https://mp.weixin.qq.com/s?__biz=MzI1MjQ2OTQ3Ng==&mid=2247494178&idx=1&sn=3190dbf682a3315e55b5ff6801ff3f2c&chksm=e9e1e3a9de966abf7774459344a35dd6010dcf4cfbb45c1cc9b5324a76856c755850d4bf5f23&scene=0#rd) |
| [回顾腾讯信息流平台部高级研究员赖坤锋：语意匹配—搜索和推荐的幕后](https://mp.weixin.qq.com/s?__biz=MzU1NTUxNTM0Mg==&mid=2247490419&idx=3&sn=0b5a995f33aff85846f743c15577289b&chksm=fbd277d2cca5fec4157f35ed5762036e21afcb0f385c7aea19cd29bebeef49210f67a509d62a&mpshare=1&scene=1&srcid=#rd) |
| [推荐系统召回四模型之全能的FM模型](https://mp.weixin.qq.com/s?__biz=MzU1NTUxNTM0Mg==&mid=2247490516&idx=3&sn=9d27d35479ce45020b2c0e02a50b5872&chksm=fbd27775cca5fe6348bff06f3caa48375bd94b6c1cd2db6458234f19fbc1adb47891c4097491&scene=0&xtrack=1&key=b824cb4e3d5c36e8c6329adc818a837da8d1ad88d58b259f6592e34404b1ab30d3bfba08c778b4e821ed0ae5051469e3c2b7f14cc19dd09de2c876959591ee0780373f7392fcd36793df418b68d7a69c&ascene=1&uin=MTI5ODUxMDk0NA%3D%3D&devicetype=Windows+10&version=62060728&lang=zh_CN&pass_ticket=LP6wPjODpYEahKUrIp%2FDQd4qrQdAVnLev%2B%2BDjIPNsVb9k3OAEncdeEqdR56umvRm)![1551255282854](readme.assets/1551255282854.png) |



| 框架工具/github 资源                                         |
| ------------------------------------------------------------ |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| [用keras搭建的常见NLP模型，如分类，sequence tagging等](https://github.com/BrikerMan/Kashgari)![1551255282854](readme.assets/1551255282854.png) |
| [TensorFlow 2.0快速上手指南12条：“Keras之父”亲授](https://mp.weixin.qq.com/s/YJMKiPP5e5quhks5E09yvw) |
| [“让Keras更酷一些！”：分层的学习率和自由的梯度](https://mp.weixin.qq.com/s/4Nz2e_vNYgq_y01JFneSfw) |
| [Pytorch常见模型代码](https://github.com/ritchieng/the-incredible-pytorch) |
| [一文解构PyTorch：40页PPT理解内部机制](https://mp.weixin.qq.com/s?__biz=MzI3MTA0MTk1MA==&mid=2652039363&idx=5&sn=a7c858e6c8217414cb9a40d742adf5fe&chksm=f1219c32c65615241941cb72930ccab8bd05f899a027d761c3e526f08d5e19ddedbbe0bbdec1&scene=0&xtrack=1&key=65174d7f09beb1f54bf2a0cfcfd6823124597eab79ca79e3016cdf0b6fac638835ba35ffa6d231177df501e2f064dfbb80e0071716228ff1ff7bd93ec25c312663e1a7b8ac9f412437fd7ad417ed23cb&ascene=1&uin=MTI5ODUxMDk0NA%3D%3D&devicetype=Windows+10&version=62060728&lang=zh_CN&pass_ticket=LHwKo%2Bj8qIAvY3lpcQuaq64N28FNrgviPoCX7g5KLBFrD0zZQjByum%2BgRA9nr28m) |
| [如何自动为IPython/Jupyter NoteBook 引入库](https://mp.weixin.qq.com/s/xZEIwTsfhkcQQBIJNqhPJg) |
| [PyTorch 中文手册 - 帮助你使用PyTorch进深度学习快速入门！](https://mp.weixin.qq.com/s/oNaDNcxGGOr7ZkY5sFuXvQ) |
| [微软开源项目提供企业级可扩展推荐系统最新实践指南](https://mp.weixin.qq.com/s/pBAnC06NQXhT3_q4jNimsQ) |
| [TensorFlow可以“预装”数据集了，新功能Datasets出炉](https://mp.weixin.qq.com/s/maO5Cs2hU-PDXIVbvwPa3Q) |
| [500+星标，简单易用 TensorFlow 代码集，随查随看！](https://mp.weixin.qq.com/s/i6TihkjhfuRrlye162fTpw) |
| [想读读PyTorch底层代码？这份内核机制简介送给你](https://mp.weixin.qq.com/s/TsR-jgO2c2-dbqnk1mEj8w) |



| 网络课程                                                     |
| ------------------------------------------------------------ |
| [中文课程！台大李宏毅机器学习公开课2019版上线](<https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650758780&idx=2&sn=25dbf006ead8e67676ba3d7062324ede&chksm=871a9a02b06d1314b4b76e4f4f2c35c0f47e378a12909ceeb1643e40d654cfe997fefef8e005&mpshare=1&scene=1&srcid=&key=14af0718ac9cde95a75ddda240e3a7d2c3d155d006124138c942bd2c63335aa0cb71179bcc2c624eda1121c80804ee152b50e524201068fd007deadccdd7c4a31ee8493ce28ce090b2ccecc0b5297153&ascene=1&uin=MTI5ODUxMDk0NA%3D%3D&devicetype=Windows+10&version=62060739&lang=zh_CN&pass_ticket=b7aCz5SYWACzEngozNpdsQ4hrW5EImxRRnOYIfoVdDcBHQdV1qeLQmwaDbEfZadx>) |
|                                                              |
|                                                              |

