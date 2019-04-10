
如下,分布式(大规模)三维重建的流程如下:
1. Feature Extraction.
2. Images Matching and View Graph Creation.
3. View Graph Clustering.
4. Cluster Reconstruction(These part can be implemented distributed).
5. Fusion.

![avatar](./imgs/Pipeline.png)



## 可能会用到的第三方库

### DBoW2
https://github.com/dorian3d/DBoW2

### DBoW3
https://github.com/rmsalinas/DBow3

#### libvot
A C++11 multithread library for image retrieval http://hlzz.github.io/libvot



#### Normalized cut
https://github.com/iromu/Graclus

http://www.cs.utexas.edu/users/dml/Software/README_Graclus




#### GraphSfM
https://github.com/AIBluefisher/GraphSfM




## 论文
#### Tianwei Shen

https://home.cse.ust.hk/~tshenaa/#code


#### Normalized Cuts
https://blog.csdn.net/Amy\_H/article/details/1907699

https://repository.upenn.edu/cgi/viewcontent.cgi?article=1101&context=cis\_papers

http://www.sci.utah.edu/~gerig/CS7960-S2010/handouts/Normalized%20Graph%20cuts.pdf


#### 网络流--最大流最小割
https://www.cnblogs.com/fzl194/p/8855101.html


https://blog.csdn.net/zitian246/article/details/76218020


https://blog.csdn.net/juncoder/article/details/38894217

#### 瑞利商与极值计算
https://seanwangjs.github.io/2017/11/27/rayleigh-quotient-maximum.html

####
拉普拉斯矩阵（Laplace Matrix）与瑞利熵（Rayleigh quotient）


#### Graclus
https://github.com/iromu/Graclus

http://www.cs.utexas.edu/users/dml/Software/graclus.html

https://www.pcquest.com/graclus-a-fast-graph-clustering-tool/

### Paper about Graclus
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=4302760

#### 深蓝学院--大规模三维重建
http://www.shenlanxueyuan.com/open/course/18/lesson/14/live/replay/223/entry?refererUrl=http%3A//www.shenlanxueyuan.com/open/course/explore



