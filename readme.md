# 高阶网络读书会文献阅读清单

本路径主要介绍了高阶网络读书会并汇总了高阶网络读书会的前沿文献及相应领域一线研究者的推荐语。

## 读书会背景

网络科学是一门充满魅力的学科，自上世纪末兴起以来吸引了众多研究者投身该领域。

长期以来，基于二元交互关系的复杂网络已经获得了深入而广泛的研究。然而，基于二元交互作用的网络模型是否足以提供对复杂系统的完整描述？随着对现实世界的探索不断深入，人们发现在许多真实的复杂系统中，组成系统的个体之间不仅存在二元交互关系，也广泛存在多个体同时进行交互，即高阶交互现象。例如，在社交系统中，合作关系往往同时发生在多个体之间，如多名学者共同合作完成科研文章、多个公司共投新项目、多单位协同作战等；在神经系统中，许多神经元之间信号的传递是多个神经元共同调控产生的结果；在生物系统中，新陈代谢过程中的每一个化学反应都是由多种物质参与完成。这种高阶相互作用的动力学过程难以用基于二元交互关系的网络表示方法进行很好地描述。鉴于此，基于二元相互作用关系对复杂系统进行描述的网络表示方法需要进行合理推广，网络中相关的科学问题（比如关键节点与节点群识别问题）的定义需要在新的表示方法下进行扩展，并提出扩展后的科学问题的合理解决方案。本阅读清单希望通过梳理高阶网络的基本概念、模型、方法与应用，为大家呈现该领域的最新研究进展。

![img](https://qiniu.pattern.swarma.org/upload/images/learn_path/1d5f51ce93774ebd57fca5aa560d30eb.png)

高阶交互网络文献聚类分析

![img](https://qiniu.pattern.swarma.org/upload/images/learn_path/337449eb8c91deaa7f1bfb0acca07be2.jpg)

网络的结构与功能
科学课程第三期](https://mp.weixin.qq.com/s/aA5c5g03aJr2KewILCq72w) 专家团队指出：网络科学第一个十年，重点研究了网络的基本模型及其性质；网络科学第二个十年，重点转入了网络动力学的全面研究，以及网络动力学与网络结构相互关系的探索；网络科学第三个十年，高阶相互作用动力学将引起人们的极大兴趣。高阶网络读书会的产生是这一观点及现象的印证，也是国内外网络科学一线研究者的高阶交互平台。
[某网络科学课程第三期](https://mp.weixin.qq.com/s/aA5c5g03aJr2KewILCq72w) 专家团队指出：网络科学第一个十年，重点研究了网络的基本模型及其性质；网络科学第二个十年，重点转入了网络动力学的全面研究，以及网络动力学与网络结构相互关系的探索；网络科学第三个十年，高阶相互作用动力学将引起人们的极大兴趣。高阶网络读书会的产生是这一观点及现象的印证，也是国内外网络科学一线研究者的高阶交互平台。

![img](https://qiniu.pattern.swarma.org/upload/images/learn_path/d2271b57f240c5aded85821aa88d4076.png)

从节点对到高阶交互

## 读书会目标

此次高阶网络读书会，会综合网络科学建模、机器学习、自由夜谈等方法来共同研讨高阶网络中的团、洞计算、关键节点（群）识别、链路预测等理论知识，高阶交互结构在脑网络与科学家合作网络中的应用，来促进大家的科研合作和交流。

## 高阶网络论文阅读清单

### 主题一：高阶交互网络研究的必要性（特色）、发展历程、主要研究模型、基本概念

简介：随着对现实世界的探索不断深入，人们发现在许多真实的复杂系统中，组成系统的个体之间不仅存在二元交互关系，也广泛存在多个体同时（或以特定顺序）进行交互，即高阶交互现象。为此，研究人员分别发展出了基于超图（Hypergraph）、单纯复形（Simplicial Complexes）、依赖关系等网络高阶表示模型，为复杂网络分析和研究提供了新的思路。如何使用高阶拓扑结构描述多个体之间的相互作用，进而分析网络的结构和功能，目前已有众多综述性工作对其中的核心概念、模型和方法进行了介绍。

主要参考文献：

1. Battiston, Federico, and Giovanni Petri. "Higher-Order Systems." (2022).
   [Higher-Order Systems*Battiston Federico*（2022）](https://pattern.swarma.org/paper/63ff2bf0-cdbf-11ec-ac1c-0242ac170006)
   本书包括高阶系统的数学表示、动力学过程及高阶框架应用三大部分的内容。
2. Bianconi, Ginestra. HIGHER ORDER NETWORKS: An Introduction to Simplicial Complexes. Cambridge University Press, 2021.
   [Higher-Order Networks:An Introduction to Simplicial Complexes*Bianconi G.*（2021）](https://pattern.swarma.org/paper/8c04cb78-c6a3-11ec-8d16-0242ac170006)
   本书介绍了单复形网络的众多主题，包括组合和统计性质、拓扑和几何特征，以及同步、渗流、传播等高阶动力学内容。
3. Battiston, Federico, et al. "Networks beyond pairwise interactions: structure and dynamics." Physics Reports 874 (2020): 1-92.
   [Networks beyond pairwise interactions: Structure and dynamics*Federico Battiston**physics reports*（2020）](https://pattern.swarma.org/paper/01fafdc0-1d9e-11ec-b434-0242ac170008)

该综述全面介绍了新兴的超越节点对相互作用的网络，讨论了如何表示高阶相互作用， 并介绍描述高阶系统的模型，介绍了高阶动力学及相关应用。

1. Battiston, Federico, et al. "The physics of higher-order interactions in complex systems." Nature Physics 17.10 (2021): 1093-1098.
   [The physics of higher-order interactions in complex systems*Federico Battiston,Enrico Amico,Alain Barrat.et al.**arXiv*（2021）](https://pattern.swarma.org/paper/8d1c8508-2bdc-11ec-92bc-0242ac17000a)

这篇perspective概述了高阶相互作用下的系统动力学行为，并提出了网络高阶研究的三个挑战。

1. Bick, Christian, et al. "What are higher-order networks?" arXiv preprint arXiv:2104.11329 (2021).
   [What are higher-order networks?*Christian Bick,Elizabeth Gross,Heather A. Harrington.et al.**arXiv*（2022）](https://pattern.swarma.org/paper/11f2f6ac-a647-11eb-8083-0242ac170009)

这篇文章阐述了什么是高阶网络、为什么高阶网络值得研究以及如何将它们应用于实际中。内容包括如何分析数据的结构，并强调高阶网络有助于理解数据的结构特征，讨论了高阶网络动力学与传统网络动力学的关系，及高阶交互模型。

1. Torres, Leo, et al. "The why, how, and when of representations for complex systems." SIAM Review 63.3 (2021): 435-485.
   [The why, how, and when of representations for complex systems*Leo Torres,Ann S. Blevins,Danielle S. Bassett.et al.**arXiv*（2020）](https://pattern.swarma.org/paper/76d19b70-a957-11ea-979e-0242ac1a000b)

介绍了复杂系统研究的基础概念，复杂系统的数学表示方法（图、单复形、超图等）及其之间的关系，并以科学家合作网络和邮件通信网络为例说明系统及其中的交互关系，以及不同表示方法对结果的影响。

1. Benson, Austin R., David F. Gleich, and Desmond J. Higham. "Higher-order network analysis takes off, fueled by classical ideas and new data." arXiv preprint arXiv:2103.05031 (2021).
   [Higher-order Network Analysis Takes Off, Fueled by Classical Ideas and New Data*Austin R. Benson,David F. Gleich,Desmond J. Higham**arXiv*（2021）](https://pattern.swarma.org/paper/baa3232c-8157-11eb-b8c4-0242ac170009)

简单介绍了网络高阶研究的历史、重要性及挑战，给出了网络高阶结构的表示方法及使用这些方法推广PageRank的例子。

### 主题二：高阶交互网络建模

简介：与传统复杂网络研究类似，为了理解网络的高阶结构如何影响网络的功能，需要一系列高阶结构生成模型去重现真实数据集中观察到的真实高阶结构。同时，也需要随机化的高阶结构生成模型作为基准去识别真实网络中哪些高阶结构具有非平凡特性。当前已有一系列工作从高阶视角对网络进行建模，主要包括一系列随机化高阶网络零模型，以及高阶结构生成模型，保度序列、保高阶结构facet数量配置模型等。

主要参考文献：

1. Kovalenko, Kiriil, Irene Sendiña-Nadal, Nagi Khalil, Alex Dainiak, Daniil Musatov, Andrei M. Raigorodskii, Karin Alfaro-Bittner, Baruch Barzel, and Stefano Boccaletti. "Growing scale-free simplices." Communications Physics 4, no. 1 (2021): 1-9.

[Growing scale-free simplices*K. Kovalenko,I. Sendiña-Nadal,N. Khalil.et al.**arXiv*（2020）](https://pattern.swarma.org/paper/5b0509ba-b5cb-11ea-aaaa-0242ac1a000b)
该文章提出了一种保证网络的度以及2-simplex满足无标度特性的生成模型，并对该模型进行了理论分析和仿真实验。

1. Bobrowski, Omer, and Dmitri Krioukov. "Random Simplicial Complexes: Models and Phenomena." arXiv preprint arXiv:2105.12914 (2021).
   [Random Simplicial Complexes: Models and Phenomena*Omer Bobrowski,Dmitri Krioukov**arXiv*（2021）](https://pattern.swarma.org/paper/99894246-bf6b-11eb-b453-0242ac17000d)

该综述对已发表的随机网络高阶模型，以及这些模型上观察到的现象进行了总结, 这些模型主要包括同质随机网络上的单纯复形，非同质随机网络上的单纯复形，超图上的单纯复形。

1. Ghoshal, Gourab, et al. "Random hypergraphs and their applications." Physical Review E 79.6 (2009): 066118.
   Ghoshal, G., Zlatic, V., Caldarelli, G. & Newman, M. E.. Physical Review E 79, 066118, doi:10.1103/PhysRevE.79.066118 (2009).
   [Random hypergraphs and their applications*Ghoshal Gourab*（2009）](https://pattern.swarma.org/paper/9e7af2fe-c79e-11ec-897b-0242ac170006)

作者提出了基于随机超图的三角结构生成模型，通过该模型生成超网络并与实证网络相比较，结果表明，在部分数据集上，生成网络与实证网络的统计特性保持一致，但是在别的数据集上表现完全不同，作者发现导致差异的原因在于这些实证网络中用户具有多重标签属性。

1. Costa, Armindo, and Michael Farber. "Random simplicial complexes." Configuration spaces. Springer, Cham, 2016. 129-153.
   [Random simplicial complexes*Costa Armindo,Farber Michael*（2016）](https://pattern.swarma.org/paper/35c77bd2-c79f-11ec-885d-0242ac170006)

该论文提出了一种应用范围更广泛的随机单纯复形生成模型，该模型首先将节点固定，并给定不同概率随机去生成不同阶的单纯型，最终可以通过控制这组概率，实现对随机单纯型模型的控制，同时作者也对所设置的参数如何影响生成网络的拓扑以及统计特征进行了分析。

1. Courtney, Owen T., and Ginestra Bianconi. "Generalized network structures: The configuration model and the canonical ensemble of simplicial complexes." Physical Review E 93.6 (2016): 062311.
   [Generalized network structures: The configuration model and the canonical ensemble of simplicial complexes*Courtney Owen T.,Bianconi Ginestra*（2016）](https://pattern.swarma.org/paper/976dba40-c79f-11ec-a740-0242ac170006)

作者使用广义度对网络中的单纯复形进行量化，并设计了一种给定网络广义度序列生成单纯复形的配置模型，在理论上分析了单纯复形的正则系综，并给出模型中单纯复形数量的渐进表达式。同时作者也基于数值模拟实验研究了所提出的模型在没有结构截断的情况下，网络中广义度之间的相关性。

1. Yen, Tzu-Chi. "Construction of simplicial complexes with prescribed degree-size sequences." Physical Review E 104.4 (2021): L042303.
   [Construction of simplicial complexes with prescribed degree-size sequences*Tzu-Chi Yen**arXiv*（2021）](https://pattern.swarma.org/paper/6f0502ca-c359-11eb-85df-0242ac17000f)

作者提出了一种给定网络度序列和单纯复形的facet数量的序列，来生成单纯复形的模型。作者发现增大节点的度会导致生成的网络中单纯复形上圈的数量减少。

1. Zuev, Konstantin, Or Eisenberg, and Dmitri Krioukov. "Exponential random simplicial complexes." Journal of Physics A: Mathematical and Theoretical 48.46 (2015): 465002.
   [Exponential random simplicial complexes*Zuev K.,Eisenberg O.,Krioukov D.**Journal of Physics A*（2015）](https://pattern.swarma.org/paper/c15c788e-d5da-11ec-a5b2-0242ac170006)

该论文将最大熵集合与随机单纯复形相结合，证明了当前所提出的大部分随机单纯复形模型，在特定条件约束下， 都可以转换为最大熵集合，并给出了约束条件是随机单纯复形模型需要固定所生成的网络中的单纯形数量以及边界。

### 主题二plus：基于依赖关系的高阶交互网络建模

简介：与基于单纯复形的高阶网络建模不同，基于依赖关系的高阶结构通常是指在实证数据中观察到的或通过数据挖掘得到的特定连边序列。实证研究表明，真实网络中的游走具有记忆性，节点的转移概率不仅取决于节点的当前位置，还会受到历史行为的影响，这种影响可以用高阶依赖关系来描述。识别和表示网络中基于依赖关系的高阶相互作用有助于充分理解复杂系统中的传播行为、探索高阶马尔可夫动力学等在网络中的应用。

主要参考文献：

1. Rosvall, Martin, et al. "Memory in network flows and its effects on spreading dynamics and community detection." Nature communications 5.1 (2014): 1-13.
   [Memory in network flows and its effects on spreading dynamics and community detection*Rosvall Martin*（2014）](https://pattern.swarma.org/paper/11b09ed2-cc21-11ec-9602-0242ac170006)

在网络流分析中，一阶马尔可夫方法忽略了节点游走的一个重要特征：节点的下一步转移概率取决于它的上一步转移路径。本文通过构建二阶马尔可夫动力学捕获这种“节点记忆”，更好地揭示与预测实际的转移模式。

1. Xu, Jian, Thanuka L. Wickramarathne, and Nitesh V. Chawla. "Representing higher-order dependencies in networks." Science advances 2.5 (2016): e1600028.
   [Representing higher-order dependencies in networks*Xu Jian,Wickramarathne Thanuka L.,Chawla Nitesh V.*（2016）](https://pattern.swarma.org/paper/5270d20c-cc21-11ec-a194-0242ac170006)

本文通过分析大量实证数据，定义可变阈值提取网络中的高阶依赖关系，发现很多系统和网络中最多可以呈现5阶依赖的结构。本文还分析了这种高阶结构对社团划分、节点排序等的影响。

1. Scholtes, Ingo, Nicolas Wider, and Antonios Garas. "Higher-order aggregate networks in the analysis of temporal networks: path structures and centralities." The European Physical Journal B 89, no. 3 (2016): 1-15., 89(3), 1-15.
   [Higher-order aggregate networks in the analysis of temporal networks: path structures and centralities*Scholtes Ingo,Wider Nicolas,Garas Antonios*（2016）](https://pattern.swarma.org/paper/00ead08a-cc22-11ec-a8e2-0242ac170006)

本文发现含时网络中连边出现的顺序会极大影响网络的因果拓扑结构，进而影响网络分析结果。作者引入了一个新的框架来研究“高阶聚合网络”中基于路径的中心性，更好地捕捉到了节点在时间上的中心性。

1. Scholtes, Ingo. "When is a network a network? Multi-order graphical model selection in pathways and temporal networks." In Proceedings of the 23rd ACM SIGKDD international conference on knowledge discovery and data mining, pp. 1037-1046. 2017.
   [When is a network a network? Multi-order graphical model selection in pathways and temporal networks*Scholtes Ingo*（2017）](https://pattern.swarma.org/paper/51b094e6-cc22-11ec-8923-0242ac170006)

本文引入了一个框架，用于建模网络中观察到的不同长度的序列数据捕获途径。该框架将多个高阶马尔可夫链组合成一个多层图模型，同时捕捉多个尺度上的路径的时间相关性。然后开发了一种模型选择技术来推断这种模型的最佳层数，并表明它优于以前使用的高阶马尔可夫检测技术。

1. Lambiotte, Renaud, Martin Rosvall, and Ingo Scholtes. "From networks to optimal higher-order models of complex systems." Nature physics 15.4 (2019): 313-320.
   [From networks to optimal higher-order models of complex systems*Renaud Lambiotte,Martin Rosvall,Ingo Scholtes*（2019）](https://pattern.swarma.org/paper/14c5a21a-da11-11ea-82fa-0242ac1a0005)

本前瞻性文章(Perspective) 说明了时间序列数据中非马尔可夫路径的影响，对比了几种流行的高阶网络模型，指出合理地使用高阶网络模型既能利用高阶依赖的丰富数据，又能避免过度拟合的风险。

![img](https://qiniu.pattern.swarma.org/upload/images/learn_path/adf7b05e595b7374bac5d634e0080f4e.png)

高阶网络模型

### 主题三：团、洞计算

简介：圈结构是一种重要的高阶结构，圈结构中有两种非平凡结构——团和洞。团结构是一种全连通结构，代数拓扑中被称为单纯形，是组成网络的一种基本单元结构；按照将网络“剖分”的思想，网络可以看作由各阶单纯形组成的单纯复形，并且可以在以各阶单纯形为基组成的向量空间中表示。洞结构是网络中无关等价类中的代表结构，洞是由该阶的团所组成的，其定义源于代数拓扑中的同调群。基于代数拓扑的复杂网络研究是研究复杂网络的一个全新的研究框架，并且在研究网络同步、传播、大脑的实证检验等方面取得了一定的成果。

相关经典书籍/论文推荐：

1. Shi, Dinghua, et al. "Searching for optimal network topology with best possible synchronizability." IEEE Circuits and Systems Magazine 13.1 (2013): 66-75. https://ieeexplore.ieee.org/abstract/document/6468141
   [Searching for Optimal Network Topology with Best Possible Synchronizability*Dinghua Shi ; Guanrong Chen ; Wilson Wang Kit Thong ; Xiaoyong Yan**IEEE Circuits and Systems Magazine*（2013）](https://pattern.swarma.org/paper/3aef8430-ecbb-11ea-beb2-0242ac1a0005)

本文提出了一个同步能力最优的网络模型：全齐性子网络。

1. Shi, D., Lü, L. & Chen, G. "Totally homogeneous networks." Natl. Sci. Rev. 6. 962–969 (2019). https://academic.oup.com/nsr/article/6/5/962/5435524
   [Totally Homogeneous Networks*Dinghua Shi,Linyuan Lü,Guanrong Chen**National Science Review*（2019）](https://pattern.swarma.org/paper/bcbd4f5e-00b4-11ea-8d16-acde48001122)

本文作者借鉴庞加莱的”剖分”思想，从圈结构的视角出发，把网络分解为全齐性子网络，并提出向量空间作为表示网络的新方法，以此开创新的网络研究框架。

1. Shi, D., Chen, G., et al. "Computing cliques and cavities in networks. "Communications Physics. 4, 249 (2021).
   https://www.nature.com/articles/s42005-021-00748-4[Computing cliques and cavities in networks*Dinghua Shi, Zhifeng Chen, Xiang Sun.et al.**Communications Physics*（2021）](https://pattern.swarma.org/paper/f5127da6-e60f-11eb-b61b-0242ac170008)

本文提出了一个计算团和洞的计算方法，能够计算出网络中的全部团，和部分洞结构。

1. Reimann, Michael W., et al. "Cliques of neurons bound into cavities provide a missing link between structure and function." Frontiers in computational neuroscience(2017): 48.
   https://www.frontiersin.org/articles/10.3389/fncom.2017.00048/full?fbclid=IwAR3pRFXTWZ8soPgEhyRLT2AYT5nFjIA68uMVbcb-e3jJacUXMF5cV1ko748
   [Cliques of neurons bound into cavities provide a missing link between structure and function*Reimann, M. W., Nolte.et al.**Front. Comput. Neurosci*（2017）](https://pattern.swarma.org/paper/f23a8238-e60d-11eb-b82a-0242ac170008)

本文提出了一个构建大脑皮层的模型，发现在大脑中存在着不同种类和巨大数量的高维团、洞结构。当虚拟大脑组织施加刺激时，神经元以一种高度有组织性的方式对刺激作出了反应，整个过程总是遵循从低维到高维，结构越来越复杂的顺序，到最后轰然崩解。

1. Sizemore, Ann E., et al. "Cliques and cavities in the human connectome." Journal of computational neuroscience 44.1 (2018): 115-145.
   https://link.springer.com/content/pdf/10.1007/s10827-017-0672-6.pdf
   [Cliques and cavities in the human connectome*Ann E. Sizemore, Chad Giusti, Ari Kahn.et al.**springer*（2017）](https://pattern.swarma.org/paper/e41bd3ec-e60c-11eb-85c5-0242ac170008)

本文发现人类脑网络中存在大量的团和洞结构，且对于人的认知过程和复杂行为至关重要。洞所扮演的角色尤为重要，与大脑信息传播的模式密切相关。

1. Gebhart, Thomas, and Russell J. Funk. "The emergence of higher-order structure in scientific and technological knowledge networks." arXiv preprint arXiv:2009.13620 (2020). https://arxiv.org/pdf/2009.13620
   [The Emergence of Higher-Order Structure in Scientific and Technological Knowledge Networks*Thomas Gebhart,Russell J. Funk**arXiv*（2020）](https://pattern.swarma.org/paper/b765a730-02d5-11eb-8616-0242ac1a000c)

本文发现在科技论文合作网络中高阶结构随时间迅速增多，同时伴随低阶结构减少。高阶结构的涌现与新颖性强和高影响力的论文和专利有关，并且对应着更为复杂的概念，更为抽象的词汇。

### 主题四：高阶交互网络中的关键节点（群）识别

简介：节点中心性量化评估了不同节点对网络的结构和功能的影响程度。在普通网络上衡量节点重要性的指标已经得到了较多研究，例如度中心性（Degree Centrality）测量了节点与其他节点的连接程度，介数中心性（Betweenness）测量了经过某节点的最短路径的密集程度等。高阶交互作用背景下的节点中心性的不同之处在于，中心性方法的计算对象是高阶结构或具有高阶特性，主要包括两类：一是由多个相关联的简单对交互关系（pairwise interaction）构成的、节点数不小于3的网络子结构，如模体（motifs）；二是表征涉及不小于3个节点的、非对交互关系（non-pairwise interaction）的网络子结构，如超图，以及由这两类混合而成的高阶对象。例如，在超网络中，节点的超度（hyperdegree）中心性刻画了节点之间的关联程度，它等于与目标节点关联的所有超边总数，无论这些超边的阶数是多少。除了重要节点，对重要节点群的识别也是一个重要问题。节点群的重要性与其自身的阶数或在网络中所处的位置相关，一般而言阶数越高、所处位置越接近网络的拓扑中心则越重要。

主要参考文献：

1. Battiston, Federico, et al. "Networks beyond pairwise interactions: structure and dynamics." Physics Reports 874 (2020): 1-92.
   [Networks beyond pairwise interactions: structure and dynamics*Federico Battiston,Giulia Cencetti,Iacopo Iacopini.et al.**arXiv*（2020）](https://pattern.swarma.org/paper/0d2a867e-a55a-11ea-9748-0242ac1a000b)

在本文第3.2节中，作者综述了三种不同类型的高阶节点中心性指标：基于高阶关联程度的中心性、基于高阶路径的中心性和基于高阶特征向量的中心性。

1. Fan, Tianlong, et al. "Characterizing cycle structure in complex networks." Communications Physics 4.1 (2021): 1-9.
   [Characterizing cycle structure in complex networks*Tianlong Fan,Linyuan Lü,Dinghua Shi.et al.**Communications Physics*（2021）](https://pattern.swarma.org/paper/06470156-44c6-11ea-89fc-0242ac1a0007)

本文提出利用网络中的圈信息来识别关键节点，定义了新的圈表示矩阵及重要节点量化指标，并在实证网络上验证了新指标所识别的重要节点（或节点群）在渗流、同步和传播动力学中的重要性。

1. Tudisco, Francesco, and Desmond J. Higham. "Node and edge nonlinear eigenvector centrality for hypergraphs." Communications Physics 4.1 (2021): 1-10.
   [Node and Edge Nonlinear Eigenvector Centrality for Hypergraphs*Francesco Tudisco,Desmond J. Higham**arXiv*（2021）](https://pattern.swarma.org/paper/313006da-5945-11eb-b4ee-0242ac17000a)

为了识别超图中的重要节点和超边，本文借鉴HITS算法的思想，提出了一类新的基于特征向量的中心性指标。

1. Kovalenko, Kirill, et al. "Vector Centrality in Networks with Higher-Order Interactions." arXiv preprint arXiv:2108.13846 (2021).
   [Vector Centrality in Networks with Higher-Order Interactions*Kovalenko Kirill**arXiv*（2021）](https://pattern.swarma.org/paper/2b178dbe-cc39-11ec-85e4-0242ac170006)

本文提出用向量表示超图中节点的重要性，并据此揭示同一个节点在不同阶数的交互关系中所扮演的不同角色。

1. Aktas, Mehmet Emin, et al. "Identifying critical higher-order interactions in complex networks." Scientific reports 11.1 (2021): 1-11.
   [Identifying critical higher-order interactions in complex networks*Mehmet Emin Aktas,Thu Nguyen,Sidra Jawaid.et al.**arXiv*（2021）](https://pattern.swarma.org/paper/cc71b6c4-aeeb-11eb-bf11-0242ac17000f)

基于扩散模型，本文提出了两种新的超图拉普拉斯算子用以识别超图中重要的高阶相互作用（超边），并通过与一般中心性指标的对比分析确认了新方法的性能优势。

1. Wang, Pei, Jinhu Lü, and Xinghuo Yu. "Identification of important nodes in directed biological networks: A network motif approach." PloS one 9.8 (2014): e106132.
   [Identification of important nodes in directed biological networks: A network motif approach*Wang, Pei, Jinhu Lü.et al.*（2014）](https://pattern.swarma.org/paper/c4338e8a-cc39-11ec-8b85-0242ac170006)

本文基于网络模体和主成分分析方法提出了一种新的有向网络中重要节点识别指标，并在多个实证网络上验证了新指标的准确性和预测性。

### 主题五：高阶交互网络中的链路预测

简介：高阶交互网络中的链路预测是经典方法的延伸。因为复杂系统中的许多结构涉及两个以上节点之间的相互作用，如合作关系、多种蛋白质间的功能交互等，高阶链路预测提供了一种用来分析和评估高阶交互结构的方法框架。大多数高阶链路预测方法是基于现有的高阶结构模型而提出的，如单纯复形、集合系统（set systems）、超图和二分关联图（bipartite affiliation graphs）等，这些方法也被用于预测特定高阶结构的出现或者高阶交互。也有一些方法是利用节点间的高阶相似性达到提升经典链路预测精度的目的。

1. Benson, Austin R., Rediet Abebe, Michael T. Schaub, Ali Jadbabaie, and Jon Kleinberg. "Simplicial closure and higher-order link prediction." Proceedings of the National Academy of Sciences 115, no. 48 (2018): E11221-E11230.

[Simplicial closure and higher-order link prediction*Benson Austin R.*（2018）](https://pattern.swarma.org/paper/2b5dd71e-cc3a-11ec-93bf-0242ac170006)

本文研究了来自生物学，医学，社交网络和网络的数据集，并描述了高阶结构是如何出现的以及在不同领域之间的差异。然后提出了一个评估基于链接预测的高阶数据模型的一般框架，该框架被用来从一个系统的结构和过去的历史中预测未来的相互作用。

1. Coutino, Mario, Georgios V. Karanikolas, Geert Leus, and Georgios B. Giannakis. "Self-driven graph volterra models for higher-order link prediction." In ICASSP 2020-2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), pp. 3887-3891. IEEE, 2020.
   [Self-driven graph volterra models for higher-order link prediction*Coutino Mario*（2020）](https://pattern.swarma.org/paper/87b73f46-cc3a-11ec-8f0e-0242ac170006)

本文交叉利用Volterra序列和线性结构方程模型的思想，介绍了自驱动图Volterra模型，该模型可以捕捉网络数据中的节点观测变量之间的高阶相互作用。利用社交网络中的真实交互数据，对该新型模型进行了高阶链接预测任务的验证。

1. Chavan, Neeraj, and Katerina Potika. "Higher-order link prediction using triangle embeddings." In 2020 IEEE International Conference on Big Data (Big Data), pp. 4535-4544. IEEE, 2020.
   [Higher-order link prediction using triangle embeddings*Chavan Neeraj,Potika Katerina*（2020）](https://pattern.swarma.org/paper/5309c9b6-cc3b-11ec-a786-0242ac170006)

本文通过在图神经网络中嵌入三角形来预测高阶链接。实验结果表明三角形嵌入方法在大多数数据集中有较好的效果。

### 主题六：高阶交互网络中的社团结构

简介：社团结构（community structure）是复杂网络中最普遍也是最重要的拓扑特性之一，表现为社团内部结构紧密，社团之间连接稀松。社团发现（community detection）对探索复杂系统的运行机制及其功能特性具有重要意义。由于实际网络不仅存在点和边的低阶关系，还包含了大量的高阶结构，因此如何通过高阶结构更好地刻画网络的社团属性、如何嵌入网络高阶结构信息来增加社团识别的精度及质量是当前社团发现研究中值得深入研究的重要问题。借助网络高阶信息识别更多有意义的子结构并探究高阶结构对社团划分所带来的影响正在成为研究热点。

主要参考文献：

1. Yin, Hao, Austin R. Benson, and Jure Leskovec. "Higher-order clustering in networks." Physical Review E 97, no. 5 (2018): 052306.
   [Higher-order clustering in networks*Yin Hao,Benson Austin R.,Leskovec Jure*（2018）](https://pattern.swarma.org/paper/44350c1a-cc3c-11ec-8491-0242ac170006)

作者引入了高阶聚类系数来衡量高阶网络团的闭合概率，并提供了一个更全面的观点描述复杂网络边的聚集。在传统聚类系数上进行了高阶聚类系数的自然推广，推导了高阶聚类系数的性质，并对常见的随机图模型进行了分析。

1. Yin, Hao, Austin R. Benson, Jure Leskovec, and David F. Gleich. "Local higher-order graph clustering." In Proceedings of the 23rd ACM SIGKDD international conference on knowledge discovery and data mining, pp. 555-564. 2017.
   [Local higher-order graph clustering*Yin Hao*（2017）](https://pattern.swarma.org/paper/939ee1ea-cc3c-11ec-a222-0242ac170006)

当前的局部图划分方法并未涉及高阶结构，也不能有效地处理有向网络。本文介绍了一类基于网络模体（motif）捕获高阶网络信息的局部图聚类方法：近似个性化 PageRank (MAPPR) 算法，该算法能找到包含具有最小模体电导（motif conductance）的种子节点集。

1. Benson, Austin R., David F. Gleich, and Jure Leskovec. "Tensor spectral clustering for partitioning higher-order network structures." In Proceedings of the 2015 SIAM International Conference on Data Mining, pp. 118-126. Society for Industrial and Applied Mathematics, 2015.
   [Tensor spectral clustering for partitioning higher-order network structures*Benson Austin R.,Gleich David F.,Leskovec Jure*（2015）](https://pattern.swarma.org/paper/d63cfc30-cc3c-11ec-bda0-0242ac170006)

本文提出一种张量谱聚类 (TSC) 算法，该算法允许用户指定网络聚类保留哪些高阶网络结构（如循环、前馈循环等），使用张量表示高阶网络结构，通过开发多线性谱方法划分社团。该框架可用于网络的分层流发现以及图异常检测。在有向网络中，该方法可以有效发现长度为3的反馈环这一重要高阶结构。

1. Chodrow, Philip S., Nate Veldt, and Austin R. Benson. "Generative hypergraph clustering: From blockmodels to modularity." Science Advances 7.28 (2021): eabh1303.
   [Generative hypergraph clustering: from blockmodels to modularity*Philip S. Chodrow,Nate Veldt,Austin R. Benson**arXiv*（2021）](https://pattern.swarma.org/paper/8e0b6626-5f8d-11eb-98e9-0242ac17000a)

本文提出了一种可生成具有社团结构的超图（clustered hypergraph）的概率生成模型，受此启发作者推广了Louvain方法并提出一种超图聚类算法。该方法能检测出传统方法识别不到的社团结构。

### 主题七：高阶网络中的机器学习（图表征、图嵌入）

简介：高阶结构的嵌入和表征学习致力于将图数据中的（高阶）拓扑结构以及节点和连边的特征信息嵌入到欧氏空间，有利于用传统的机器学习算法处理（高阶）图上的节点分类、链路预测等下游任务。根据嵌入时是否依赖下游任务，可以粗略地将模型分为图表征和图嵌入两类。现有文献主要关心超图结构下的学习，少数涉及单纯复形的表征学习以及基于依赖关系的高阶结构嵌入。

主要参考文献：

1. 综述性论文：
   Gao, Yue et al. “Hypergraph Learning: Methods and Practices.” IEEE Transactions on Pattern Analysis and Machine Intelligence 44 (2022): 2548-2566.

   [Hypergraph learning: Methods and practices*Gao Yue*（2020）](https://pattern.swarma.org/paper/7081a832-cc50-11ec-afac-0242ac170006)

清华大学高跃老师团队的最新综述，评述了在引入深度学习技术前超图下的机器学习技术，包括如何构建超图和如何利用超图的拉普拉斯矩阵进行超图上的标签学习、动态超图结构学习等。

1. 图表征：

a. Feng, Yifan, et al. "Hypergraph neural networks." AAAI (2019).

[Hypergraph neural networks*Feng Yifan*（2019）](https://pattern.swarma.org/paper/0f4931ce-cc51-11ec-b79a-0242ac170006)

第一篇将神经网络引入超图的工作，来自清华高跃老师课题组。论文利用超图的拉普拉斯矩阵，将简单图上的GCNN结构引入超图，实现数据表示学习。

b. Huang, Jing and Jie Yang. “UniGNN: a Unified Framework for Graph and Hypergraph Neural Networks.” IJCAI (2021).
[UniGNN: a Unified Framework for Graph and Hypergraph Neural Networks*Jing Huang,Jie Yang**arXiv*（2021）](https://pattern.swarma.org/paper/755d8b90-ac90-11eb-9b89-0242ac17000f)

上海交通大学Yang Jie老师的工作，阶段性的总结了超图神经网络的各种架构，基于消息传递，提出了一个两阶段模型，将简单图结构上的GNN和若干种超图上的GNN都统一为同一框架，同时证明了该模型具有和广义WL-test相同的表达能力。

c. Chien, Eli et al. “You are AllSet: A Multiset Function Framework for Hypergraph Neural Networks.” ICLR (2022).
[You are AllSet: A Multiset Function Framework for Hypergraph Neural Networks*Chien Eli**arXiv*（2021）](https://pattern.swarma.org/paper/998fd2d8-cc52-11ec-822c-0242ac170006)

该工作构建了一个两阶段模型，其创新点在于用 multiset function 来拟合两个阶段的信息聚合过程，从而自然地引入了 DeepSet 和 Transformer 技术，实现了目前最好的节点分类效果。

d. Ebli, Stefania et al. “Simplicial Neural Networks.” ArXiv abs/2010.03633 (2020): n. pag.
[Simplicial neural networks*Ebli Stefania,Defferrard Michaël,Spreemann Gard**arXiv*（2020）](https://pattern.swarma.org/paper/c431c906-cc52-11ec-b4fe-0242ac170006)
这篇文章利用单纯复形网络的拉普拉斯矩阵，将简单图的 GNN 架构首次引入单纯复形网络。

1. 图嵌入：

a. Saebi, Mandana et al. “HONEM: Learning Embedding for Higher Order Networks.” Big data 8 4 (2020): 255-269 .
[HONEM: learning embedding for higher order networks*Saebi Mandana*（2020）](https://pattern.swarma.org/paper/268fffc8-cc53-11ec-a978-0242ac170006)

本文利用基于“依赖”的高阶结构，定义了高阶网络上的随机游走，从而得到高阶网络的相似性矩阵。最后，用 SVD 分解该相似性矩阵得到高阶网络各个节点的网络嵌入表示。

b. Huang, Jie et al. “Hyper2vec: Biased Random Walk for Hyper-network Embedding.” DASFAA (2019).
[Hyper2vec: Biased random walk for hyper-network embedding*Huang Jie*（2019）](https://pattern.swarma.org/paper/df45ce62-cc53-11ec-bbb0-0242ac170006)

本文将简单图上的随机游走扩展到高阶图，通过定义点到超边、超边到点的随机游走策略得到节点序列，并结合 DeepWalk 嵌入算法，得到了超图网络的节点嵌入。

c. Zhang, Ruochi et al. “Hyper-SAGNN: a self-attention based graph neural network for hypergraphs.” ICLR (2020): n. pag.
[Hyper-SAGNN: a self-attention based graph neural network for hypergraphs*Zhang Ruochi,Zou Yuesong,Ma Jian**arXiv*（2019）](https://pattern.swarma.org/paper/945a7b54-cc54-11ec-92bf-0242ac170006)

该工作的任务是做超边的链路预测，相比于传统的链路预测方法，该模型能够预测任意大小的超边是否存在。对于一个节点集合，为了判断两个节点是否属于同一超边，该工作提出两种方法来嵌入集合中的节点：1）node-wise FFN用于得到节点的“静态”嵌入；2）self-attention用于得到节点的“动态”嵌入。作者认为，若节点集合属于同一超边，则两种嵌入应该相似，否则不相似，以此来预测超边。

### 主题八：高阶交互网络中的传播

简介：在复杂网络研究中，基于二元交互（pairwise interaction）模拟传播过程有着广泛而深入的研究。但是在许多场景下，真实系统中的传播可能需要通过多元交互才能实现，而高阶传播表示的正是需要多元交互，且发生在高阶结构上的传播过程。关于高阶传播的研究，能够从新的角度去解释传播现象，发现在二元交互视角下缺失的动力学性质。

主要参考文献：

1. Iacopini, Iacopo, Giovanni Petri, Alain Barrat, and Vito Latora. 2019NC "Simplicial models of social contagion."
   [Simplicial models of social contagion*Iacopini Iacopo*（2019）](https://pattern.swarma.org/paper/03c784be-cc55-11ec-a47a-0242ac170006)

该文章定义了一种发生在三角形（2-simplex）上的高阶传播行为，并在SIS传播模型下使用实证数据进行了研究，结果表明高阶传播的引入，会导致非连续相变的产生。

1. Matamalas, Joan T., Sergio Gómez, and Alex Arenas. "Abrupt phase transition of epidemic spreading in simplicial complexes." Physical Review Research 2.1 (2020): 012049.
   [Abrupt phase transition of epidemic spreading in simplicial complexes*Joan T. Matamalas,Sergio Gómez,Alex Arenas**arXiv*（2020）](https://pattern.swarma.org/paper/8dc93868-44c8-11ea-89fc-0242ac1a0007)

论文分析了基于2-simplex的SIS模型传播动力学问题，通过求解与分析模型的不动点，发现考虑高阶传播时，疾病的传播规模随感染概率的改变而产生突变。

1. Barrat, Alain, Guilherme Ferraz de Arruda, Iacopo Iacopini, and Yamir Moreno. "Social contagion on higher-order structures." arXiv preprint arXiv:2103.03709 (2021).
   [Social contagion on higher-order structures*Alain Barrat,Guilherme Ferraz de Arruda,Iacopo Iacopini.et al.**arXiv*（2021）](https://pattern.swarma.org/paper/c3da7a90-7fc6-11eb-baf3-0242ac170009)

论文研究了超图上的传播过程，并推广到几种平均场和异质平均场方法，从高阶传播中观察到了连续和非连续的相变，并出现了临界质量效应。最后在真实的社会网络中进行了模拟。

1. Chowdhary, S., Kumar, A., Cencetti, G., Iacopini, I. and Battiston, F., 2021. "Simplicial contagion in temporal higher-order networks. Journal of Physics: Complexity.", 2(3), p.035019.
   [Simplicial contagion in temporal higher-order networks*Sandeep Chowdhary,Aanjaneya Kumar,Giulia Cencetti.et al.**arXiv*（2021）](https://pattern.swarma.org/paper/8668dc64-b2da-11eb-908e-0242ac17000d)

论文提出了一种时序网络的单纯形传播模型，通过微观马尔科夫链方法，发现网络的时间性质将限制高阶传播的影响，指出了传播动力学中的时间特性对高阶网络的重要影响。

1. Li, Z., Deng, Z., Han, Z., Alfaro-Bittner, K., Barzel, B. and Boccaletti, S., 2021. "Contagion in simplicial complexes". Chaos, Solitons & Fractals, 152, p.111307.
   [Contagion in simplicial complexes*Z. Li,Z. Deng,Z. Han.et al.**arXiv*（2021）](https://pattern.swarma.org/paper/300eef7c-e073-11eb-84a1-0242ac17000d)

文章实现了单纯复形上的SIS传播模型，发现高阶相互作用从根本上改变了传播模式。尽管两两相互作用在早期传播中发挥了关键作用，当有足够的高阶结构被激活后，高阶结构的作用将在传播动力学中占主导地位，且动力学过程显示出非连续的相变。

1. Jhun, Bukyoung. "Effective epidemic containment strategy in hypergraphs." Physical Review Research 3.3 (2021): 033282.
   [Effective epidemic containment strategy in hypergraphs*Bukyoung Jhun**arXiv*（2021）](https://pattern.swarma.org/paper/4c1e7b18-fa5b-11eb-85be-0242ac17000a)

论文提出了一种超图中的免疫策略，对那些在超图中具有高瞬时感染概率的超边进行免疫，作者发现在均匀的超图中，使用免疫策略选择出来的那些特征值很大的超边都包含在传播过程中。作者也发现高瞬时感染概率可以作为中心性指标衡量超边在高阶交互传播过程中的重要性。

1. St-Onge, Guillaume, et al. "Universal nonlinear infection kernel from heterogeneous exposure on higher-order networks." Physical Review Letters 127.15 (2021): 158301.
   [Universal Nonlinear Infection Kernel from Heterogeneous Exposure on Higher-Order Networks*Guillaume St-Onge,Hanlin Sun,Antoine Allard.et al.**physical review letters*（2021）](https://pattern.swarma.org/paper/f7ca7354-2706-11ec-af8a-0242ac17000a)

作者将传播过程中环境的异质性以及个体的异质性整合到超图模型中，发现若同时引入异质感染概率和最小感染数量将会导致感染的个体数量以及感染风险之间出现普遍的非线性关系。在考虑非线性的感染概率的情况下，传统的动力学过程将会出现非连续相变，超指数传播以及迟滞现象。

1. Landry, Nicholas W., and Juan G. Restrepo. "The effect of heterogeneity on hypergraph contagion models." Chaos: An Interdisciplinary Journal of Nonlinear Science 30.10 (2020): 103117.
   [The effect of heterogeneity on hypergraph contagion models*Nicholas Landry,Juan G. Restrepo**arXiv*（2020）](https://pattern.swarma.org/paper/7506d6c8-ba84-11ea-87e9-0242ac1a000b)

论文提出了基于超度的平均场方法来描述超图中上SIS模型动力学过程，作者发现当网络中连边或者三角形是独立选择的或者正相关情况下，爆炸相变会因超度的异质性而被压缩，同时也发现超图上的高阶结构对于动力学过程有着非常重要的影响。

1. Wang, Dong, et al. "Simplicial SIRS epidemic models with nonlinear incidence rates." Chaos: An Interdisciplinary Journal of Nonlinear Science 31.5 (2021): 053112.
   [Simplicial SIRS epidemic models with nonlinear incidence rates*Wang Dong*（2021）](https://pattern.swarma.org/paper/0a5d4dee-cc56-11ec-8843-0242ac170006)

该论文提出了一种同时考虑网络高阶结构以及非线性感染概率的SIRS模型，所提出的模型不仅具有非连续相变、双稳态等动力学性质，同时也能观察到传播周期性爆发的现象，作者也分析了所提出的模型在平衡点的稳定性，并得到了双稳态存在的条件。

1. de Arruda, Guilherme Ferraz, Giovanni Petri, and Yamir Moreno. "Social contagion models on hypergraphs." Physical Review Research 2.2 (2020): 023032.
   [Social contagion models on hypergraphs*de Arruda,Ferraz Guilherme,Petri Giovanni.et al.*（2020）](https://pattern.swarma.org/paper/3daa5d72-cc56-11ec-871a-0242ac170006)

该论文提出了一种用于研究超图上的高阶传播理论分析框架，通过在多种超网络上的数值分析发现，所提出的模型的参数空间范围很大，适用范围广，具有一阶、二阶相变、双稳态、以及迟滞等动力学性质。

### 主题九：高阶交互网络中的博弈

简介：生物体之间的互动，从微生物到人类社会，本质上比粒子和非微生物物质之间的简单直接互动更为复杂多样，其中一个典型例子便是网络科学中最新的研究热点——高阶交互网络。在此，我们将介绍在高阶网络上的演化博弈研究的最新进展。在高阶网络上的博弈得益于多学科的协同作用，比如统计物理学，网络科学和进化博弈论。它更关注个体们在群体中的互相作用，研究一些重要的平衡和非平衡动态过程。

主要参考文献：

1. Alvarez-Rodriguez, Unai, Federico Battiston, Guilherme Ferraz de Arruda, Yamir Moreno, Matjaž Perc, and Vito Latora. "Evolutionary dynamics of higher-order interactions in social networks." Nature Human Behaviour 5, no. 5 (2021): 586-595.
   [Evolutionary dynamics of higher-order interactions in social networks*Unai Alvarez-Rodriguez,Federico Battiston,Guilherme Ferraz de Arruda.et al.**arXiv*（2021）](https://pattern.swarma.org/paper/3775aa88-44e0-11ea-89fc-0242ac1a0007)

   本文研究了具有高阶互动的社会系统中公共物品博弈的进化动态。该工作表明均匀超图上的博弈与良好混合群体中的复制者动态相呼应，为研究网络群体中的合作提供了理论基础，本文揭示枢纽的存在和不同规模群体中互动的共存是如何影响合作的演变的。

2. Guo, H., D. Jia, I. Sendiña-Nadal, M. Zhang, Z. Wang, X. Li, K. Alfaro-Bittner, Y. Moreno, and S. Boccaletti. "Evolutionary games on simplicial complexes." Chaos, Solitons & Fractals 150 (2021): 111103.
   [Evolutionary games on simplicial complexes*H. Guo,D. Jia,I. Sendiña-Nadal.et al.**arXiv*（2021）](https://pattern.swarma.org/paper/c20816dc-7fc6-11eb-baf3-0242ac170009)

该工作研究了通过邻居间接相互作用的博弈，主要考虑双体和三体相互作用的简化图，提出了一种新的博弈框架。其优点有：支持高阶博弈，允许非主导策略出现并与主导策略共存；能描述从主导背叛到主导合作的新过渡；证明2-simplex互动是策略多样性的来源。

1. Civilini, Andrea, Nejat Anbarci, and Vito Latora. "Evolutionary Game Model of Group Choice Dilemmas on Hypergraphs." Physical review letters 127.26 (2021): 268301.
   [Evolutionary game model of group choice dilemmas on hypergraphs*Andrea Civilini,Nejat Anbarci,Vito Latora**physical review letters*（2021）](https://pattern.swarma.org/paper/b65822b8-4df3-11ec-b97f-0242ac170004)

本文将进化博弈引入超图，揭示了个别决策者的偏好和群体一致选择之间的差异。并且，当动态发生在异质超图上时，会出现纳什均衡向风险策略的偏离。

1. Kumar, Aanjaneya, et al. "Evolution of honesty in higher-order social networks." Physical Review E 104.5 (2021): 054308.
   [Evolution of honesty in higher-order social networks*Aanjaneya Kumar,Sandeep Chowdhary,Valerio Capraro.et al.**arXiv*（2021）](https://pattern.swarma.org/paper/4ee4a73e-50cb-11ec-9bf6-0242ac17000f)

发送者-接收者博弈是信息传输的简单模型，以此研究发送者和接收者之间诚实和欺骗的演变。本文引入了接收者之间的群体互动，并研究他们在高阶社会网络中的相互联系如何影响谎言的演变。

### 主题十：高阶交互网络中的同步

简介：同步现象广泛存在于物理、生物和社会系统中，如摆钟的同步运动、观众的同频率鼓掌和萤火虫的集体闪烁等。一定条件下，复杂网络中的节点运动状态会达到同步。已有的研究多是基于节点对交互的，而实际网络中不仅有成对交互，还有多个实体的交互，即高阶交互。高阶交互不能简单地看作成对交互的组合。该方向上有众多关键问题待深入讨论，比如：如何判定高阶网络同步？如何衡量高阶网络的同步能力？传统网络中判别同步的方法是否依旧适用于高阶网络？高阶交互的存在对网络的同步是促进，还是抑制？高阶网络中的同步与传统网络有哪些异同？

主要参考文献：

1. Tanaka, Takuma, and Toshio Aoyagi. "Multistable attractors in a network of phase oscillators with three-body interactions." Physical Review Letters 106.22 (2011): 224101.
   [Multistable attractors in a network of phase oscillators with three-body interactions*Tanaka Takuma,Aoyagi Toshio*（2011）](https://pattern.swarma.org/paper/bb3318c4-cc56-11ec-be79-0242ac170006)

这篇文献研究了三个实体交互对动力系统的影响.研究结果发现，在临界耦合强度上存在无穷多个多稳同步态会出现,而任意耦合强度下均存在一个稳定的不相干态。

1. Skardal, Per Sebastian, and Alex Arenas. "Abrupt desynchronization and extensive multistability in globally coupled oscillator simplexes." Physical review letters 122.24 (2019): 248301.
   [Abrupt Desynchronization and Extensive Multistability in Globally Coupled Oscillator Simplexes*Per Sebastian Skardal,Alex Arenas**physical review letters*（2019）](https://pattern.swarma.org/paper/3a14c14c-8889-11ea-9f07-0242ac1a0005)

这篇文献发现高阶耦合振子的集群动力学会引发一种新的现象,同时出现多稳定性,即存在无穷多个稳定的部分同步态。

1. Lucas, Maxime, Giulia Cencetti, and Federico Battiston. "Multiorder Laplacian for synchronization in higher-order networks." Physical Review Research 2.3 (2020): 033410.
   [Multiorder Laplacian for synchronization in higher-order networks*Maxime Lucas,Giulia Cencetti,Federico Battiston**physical review research*（2020）](https://pattern.swarma.org/paper/d9ad3ad6-1d9d-11ec-915c-0242ac170008)

这篇文献给出了高阶相位振子的一般框架及各阶Laplacian矩阵,通过Laypunov指数分析了吸引交互和排斥交互对同步能力的影响。

1. Millán, Ana P., Joaquín J. Torres, and Ginestra Bianconi. "Explosive higher-order Kuramoto dynamics on simplicial complexes." Physical Review Letters 124.21 (2020): 218301.
   [Explosive higher-order Kuramoto dynamics on simplicial complexes*Ana P. Millán,Joaquín J. Torres,Ginestra Bianconi**arXiv*（2020）](https://pattern.swarma.org/paper/910b7d7c-88ae-11ea-b132-0242ac1a000b)

关于Kuramoto模型的研究多集中在节点上,本篇文献提出了一个与高维单形（边，三角形等）耦合振子相关的 Kuramoto模型.主要考虑两种高阶 Kuramoto动力学，即简单 Kuramoto动力学和爆炸 Kuramoto动力学.基于Hodge分解,可将动力学投影到单形的上下两个面.简单高阶 Kuramoto 在其相邻面的投影呈连续相变,而爆炸 Kuramoto呈爆炸同步跃迁.这表明定义在n维单形上的高阶同步动力学,在其投影动力学上可同时诱导不连续的跃迁。

1. Gambuzza, Lucia Valentina, et al. "Stability of synchronization in simplicial complexes." Nature communications 12.1 (2021): 1-13.
   [Stability of synchronization in simplicial complexes*L. V. Gambuzza,F. Di Patti,L. Gallo.et al.**nature communications*（2021）](https://pattern.swarma.org/paper/13e2a9d4-7641-11eb-8604-0242ac17000a)

这篇文献基于耦合动力系统的一般框架,证明了完全同步是存在的,并给出了同步稳定的必要条件及主稳定函数的高阶形式。

1. Skardal, Per Sebastian, et al. "Higher-order interactions can better optimize network synchronization." Physical Review Research 3.4 (2021): 043193.
   [Higher-order interactions can better optimize network synchronization*Skardal Per Sebastian*（2021）](https://pattern.swarma.org/paper/160faf8c-cc57-11ec-a1d8-0242ac170006)

这篇文献提出一种编码高阶交互的组合Laplacian矩阵。总的耦合强度是常量时,增强高阶耦合,网络同步能力相应地提高。这一现象源于组合Laplacian矩阵特征值谱变宽。

1. Tang, Ying, Dinghua Shi, and Linyuan Lü. "Optimizing higher-order network topology for synchronization of coupled phase oscillators." Communications Physics 5.1 (2022): 1-12.
   [Optimizing higher-order network topology for synchronization of coupled phase oscillators*Ying Tang,Dinghua Shi,Linyuan Lü**arXiv*（2021）](https://pattern.swarma.org/paper/b3b8f6ca-0624-11ec-bedd-0242ac17000a)

调整网络的拓扑结构可以优化同步.成对交互的传统网络中,同质无向网络更容易同步,结构上不对称的有向网络也更易同步。 这篇文献主要研究高阶交互的同步优化控制.对于无向交互来说,容易同步的网络其节点度分布趋于一致；而有向交互中,优化的可同步高阶网络结构也可以是对称的。

1. Chen, Guanrong. "Searching for Best Network Topologies with Optimal Synchronizability: A Brief Review." IEEE/CAA Journal of Automatica Sinica 9.4 (2022): 573-577.
   [Searching for Best Network Topologies with Optimal Synchronizability: A Brief Review*Chen Guanrong*（2022）](https://pattern.swarma.org/paper/1df612ee-cc58-11ec-9623-0242ac170006)

这篇文献综述网络同步的准则和拓扑优化方面的研究进展,并探讨高阶拓扑在大规模复杂网络最优同步方面的作用。

1. Zhang, Yuanzhao, Maxime Lucas, and Federico Battiston. "Do higher-order interactions promote synchronization?." arXiv preprint arXiv:2203.03060 (2022).
   [Do higher-order interactions promote synchronization?*Yuanzhao Zhang,Maxime Lucas,Federico Battiston**arXiv*（2022）](https://pattern.swarma.org/paper/1cfe525a-9e97-11ec-8347-0242ac170004)

这篇文献主要从度异质性角度解释为什么高阶交互在超图网络中促进同步,而在单复形网络中抑制同步。

### 主题十一：应用：科学学中的高阶交互结构

简介：科学学以科学领域的相关主体为基本研究对象（科研人员及其团体、科研成果及其载体），旨在量化科学研究的客观规律，探求科学研究的内在机制，预测科学研究的影响与发展，以期找到科学研究的一般范式，进而促进科学发展。传统复杂网络的方法通过关注科学家或科学知识的二元交互发现了科学创新的部分机制，但由于科学家或科学知识的关系更像是一场高维的象棋游戏，需要从不同的视角观察发展规律并理解内在机制。因此，一些学者开始关注科学家及科学知识之间的高阶关系，并试图从高阶结构的视角发现科学研究的客观规律，从而预测科学研究的发展及创新的发生。

主要参考文献：

1. Patania, Alice, Giovanni Petri, and Francesco Vaccarino. "The shape of collaborations." EPJ Data Science 6 (2017): 1-16.
   [The shape of collaborations*Patania Alice,Petri Giovanni,Vaccarino Francesco*（2017）](https://pattern.swarma.org/paper/95ba02cc-cc58-11ec-a416-0242ac170006)

这篇文章以arXiv数据为实证数据，研究了不同科学团体合作的拓扑结构。从高阶（simplex）的角度研究了arXiv类别的属性。研究表明：不同的机制在构建科学合作的高阶连通性特征中发挥作用。

1. Gebhart, Thomas, and Russell J. Funk. "The emergence of higher-order structure in scientific and technological knowledge networks." arXiv preprint arXiv:2009.13620 (2020).
   [The Emergence of Higher-Order Structure in Scientific and Technological Knowledge Networks*Thomas Gebhart,Russell J. Funk**arXiv*（2020）](https://pattern.swarma.org/paper/b765a730-02d5-11eb-8616-0242ac1a000c)

这篇文章通过识别科学技术知识的高阶结构，观察到知识高阶结构的快速增长，是传统网络方法无法观察到的。对科学知识高阶结构的研究发现，科学技术知识的增长越来越多地发生在更高的维度上，这种更丰富的拓扑结构可能使科学和技术迄今未知的全新发现和发明得以发展。

1. Benson, Austin R., Rediet Abebe, Michael T. Schaub, Ali Jadbabaie, and Jon Kleinberg. "Simplicial closure and higher-order link prediction." Proceedings of the National Academy of Sciences 115, no. 48 (2018): E11221-E11230.
   [Simplicial closure and higher-order link prediction*Benson Austin R.*（2018）](https://pattern.swarma.org/paper/2b5dd71e-cc3a-11ec-93bf-0242ac170006)

这篇文章研究了来自生物学、医学、社交网络等19个数据集，描述了高阶结构如何出现和不同领域的差异，并提出了一个链路预测模型的一般框架用于预测具有高阶结构的网络。

### 主题十二：应用：脑网络中的高阶交互结构

简介：人脑是最复杂、最令人着迷的系统，我们研究人脑的目标是了解人类行为的神经基础，从而为深刻理解人类智慧、提高人脑效率、准确诊断和治疗各种神经系统疾病和精神疾病提供理论依据。随着生物医疗手段的进步和复杂系统研究的蓬勃发展，利用图论和网络科学，构建复杂脑网络拓扑结构，通过高阶网络分析方法，将大脑错综复杂的内部运作映射为固有的网络化现象，为大脑研究提供了更进阶的方向。

主要参考文献：

1. Giusti, Chad, Robert Ghrist, and Danielle S. Bassett. "Two’s company, three (or more) is a simplex." Journal of computational neuroscience 41.1 (2016): 1-14.
   [Two’s company, three (or more) is a simplex Algebraic-topological tools for understanding higher-order structure in neural data*Giusti, Chad, Robert Ghrist.et al.*（2016）](https://pattern.swarma.org/paper/35c77bd2-c79f-11ec-885d-0242ac170006)

本文利用单纯复形，克服了在脑网络中节点对和连边构建神经结构和功能拓扑结构的限制，在建模和测量神经现象方面提供了广泛的新可能性。文中回顾了基本的单纯复形的数学形式，以及将单纯复形应用于神经数据的新兴文献，如从动物模型的电生理记录到人类的血流动力学波动。

1. Sizemore, Ann E., Chad Giusti, Ari Kahn, Jean M. Vettel, Richard F. Betzel, and Danielle S. Bassett. "Cliques and cavities in the human connectome." Journal of computational neuroscience 44, no. 1 (2018): 115-145.
   [Cliques and cavities in the human connectome*Ann E. Sizemore, Chad Giusti, Ari Kahn.et al.**springer*（2017）](https://pattern.swarma.org/paper/e41bd3ec-e60c-11eb-85c5-0242ac170008)

将大脑区域及其连接编码为节点和边缘网络，可以捕捉到许多可能的路径，在人类处理和执行复杂行为时，这些路径可以传递信息。本文利用捕捉高阶关系，研究了可以进行局部计算的密集连接的节点组，以及可以进行并行处理的较大的互动模式。发现在通过接线最小化构建的空网络中存在比预期更多的大团，提供了大脑网络可以进行快速、局部处理的架构。

1. Lynn, Christopher W., and Danielle S. Bassett. "The physics of brain network structure, function and control." Nature Reviews Physics 1, no. 5 (2019): 318-332.
   [The physics of brain network structure, function and control*Lynn, Christopher W.,Bassett.et al.**nature reviews physics*（2019）](https://pattern.swarma.org/paper/d31a0d56-034f-11ec-a859-0242ac170008)

大脑的特点是结构连接的异质性模式，支持无与伦比的认知能力和广泛的行为。本文描述了在空间嵌入和能量最小化的约束下，在结构布线中实例化的大脑网络架构的组织原则；调查了规定神经活动如何沿结构连接传播的脑网络功能模型；讨论了脑网络控制的微扰实验和模型；这些实验利用信号沿结构连接传播的物理学原理来推断支持目标导向行为的内在控制过程，并为基于刺激的神经和精神疾病的治疗提供信息。

### 其他

高阶网络资料整理： https://ian2qfj7gh.feishu.cn/docs/doccnhAsj9CTS1EG8HhgpjQPWVf

### 致谢

本路径先由徐舒琪、刘波、范天龙、周方、管炜、刘波、殷飞宇、贾芳弟、高飞、孟凡圆、杨荣湄、陈依珺、李博、王重阳、段月然、高爽等同学精心梳理，后由读书会发起人吕琳媛、任晓龙、管青老师审校完成，再次感谢各位老师同学的辛勤付出！

希望能对各位想要探索高阶交互网络的同学一些指导与帮助，欢迎在下方留言~
