
如下,分布式(大规模)三维重建的流程如下:
1. Feature Extraction.
2. Images Matching and View Graph Creation.
3. View Graph Clustering.
4. Cluster Reconstruction(These part can be implemented distributed).
5. Fusion.

![avatar](./imgs/Pipeline.png)



## 可能会用到的第三方库

#### Normalized cut
https://github.com/iromu/Graclus

http://www.cs.utexas.edu/users/dml/Software/README_Graclus


#### libvot
A C++11 multithread library for image retrieval http://hlzz.github.io/libvot


#### GraphSfM
https://github.com/AIBluefisher/GraphSfM

#### Tianwei Shen

https://home.cse.ust.hk/~tshenaa/#code
