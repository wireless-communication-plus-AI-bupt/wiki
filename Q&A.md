# Q&A

### 1. 对于一个很宽泛、且从未接触过的任务，该如何快速上手？

+ 拆解任务
  + 找老师、师兄师姐沟通，完成拆解
  + 和AI提问与讨论，完成拆解
  + 自己结合自身情况做一个规划
  
+ 查阅各种资料-quick start

  + 让老师和师兄师姐给你做一个简单的文献综述，也可以让AI给你做一个
  + 上手最好的方式是看懂现成的代码
    + 及时找师兄师姐沟通，哪怕要不到核心的代码，要一些数据集生成或者简单的demo也可以争取
    + 开源代码，通常在GitHub上。通常不好直接搜索，可以看该领域相关的论文，质量高的、偏AI的论文可能会给出本工作的开源链接
    + 用AI写一些demo，然后通过和AI的交互学习一些基本的知识，进行入门

  + 自己做一个简单的文献综述（该过程可循环）
    + 关键词下载10篇近期论文（可以让AI帮你查）
    + 排除5篇相关性没那么强的论文
    + 找到两篇你感兴趣的细读他的Introduction中的related work。通过这个方式对该领域有大致的了解
    + 在introduction引用的其他文献中找到其他的文献，选取你感兴趣的、觉得经典的文献递归式的阅读
  + 直接Google，知乎或者其他的一些平台会有一些相关的问题，可以查阅

### 2. 我是一个科研新手，面对一个我不是很熟悉的领域，我应该如何阅读文献？

熟悉论文结构，并可以按照以下推荐顺序阅读

- 标题+作者+论文类型：通常这会是文章的第一印象。
  - 标题里是否有你比较感兴趣的词？
  - 作者什么单位、头衔（IEEE Fellow通常很权威）？单位是否权威（高校？大公司）？在这个领域是否多次出现？（深耕领域的人更值得关注）
  - 论文是期刊还是会议？什么级别的论文？
- 摘要（关键词）+引言+结论：文章的第一印象，引言里会引用大量文章作为本文的支撑，看看他的表述有助于对本领域有更全面的了解。引言也可以帮助你找新的文献
- 模型：文章主体，System Model + proposed Model。先看图，再看字。通常系统模型一个领域的文章会类似
- 实验：有时候一个领域会有一些通用的实验方式

阅读中可能遇到的困难？让GPT帮你解决，哪怕解决的你不是很满意，也可以让他给你一些建议。把AI当作你读论文的**助手**。

- 论文里太多关键词、概念陌生？需要适应期，记笔记，多次出现的概念能归类，慢慢就好了
- 这个方法我没见过或者我看不懂？有些技术可能并非这篇论文提出来的，要看懂得针对性地找这方面的技术资料去阅读。想要真正理解一篇论文甚至一个领域的工作，基本上得复现论文。
  - 如果你的领域涉及AI的知识偏多，建议早点开始学习AI。
- 论文里出现算法流程图、伪代码很陌生？论文的图表和文章内容是相互呼应的，静下心来两相印证可解。



附：无线通信中期刊、会议的级别与缩写（待补充）

期刊：[论文类型Journal、magazine、transaction、letter等的区别_magazine和journal的区别-CSDN博客](https://blog.csdn.net/zzc15806/article/details/83186423)、[通信及信号处理领域期刊影响因子、分区及期刊推荐_通信类期刊排名-CSDN博客](https://blog.csdn.net/yrwang_xd/article/details/130947549)

- t1：IEEE Transactions on Wireless Communications (TWC)、IEEE Wireless Communications（WC） 、IEEE Journal on Selected Areas in Communications（J-SAC）
  - 其他领域：、IEEE Transactions on Information Theory（TIT）、IEEE Transactions on Signal Processing（TSP）
- t2：IEEE Transactions on Communications（TC）、IEEE Transactions on Vehicular Technology(TVT)、IEEE Communications Letters（CL）、IEEE Transactions on Antennas an Propagation 、IEEE Wireless Communications、IEEE Transactions on Cognitive Communications and Networking
- t3：IEEE Wireless Communications Letters（WCL）、IEEE Signal Processing Letters (SPL)
- t4：China Communications、IEEE Access

附：Letters文章短，可当会议看，不如长文量大价值高，但通常会有比较简单新颖的技术

会议

+ t1：IEEE Global Communications Conference (GLOBECOM)、IEEE International Conference on Communications (ICC)、IEEE International Conference on Computer Communications (INFOCOM)
+ t1.5：IEEE Wireless Communications and Networking Conference (WCNC)、International Conference on Acoustics, Speech, and Signal Processing（ICASSP，CCF-B）
+ t2：IEEE Vehicular Technology Conference (VTC)、IEEE International Symposium on Personal, Indoor and Mobile Radio Communications (PIMRC)
+ t3：IEEE/CIC International Conference on Communications in China（ICCC）、The annual International Conference on Wireless Communications and Signal Processing (WCSP) 

arxiv：一个特殊的论外的存在、神奇的预印版。偏AI的论文为了抢占先机会先挂Arxiv再投最近的会。约定俗成地，审稿人不能以Idea可以在Arxiv中搜到拒稿。通常是给会议论文用。



