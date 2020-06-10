# Webpage-links
Ass2-task2


数据集简介：


        这个数据集包含大约4800个网页及其超链接。带有“n”标志的记录包含网页的(唯一的)id和url。带“e”标志的网页表示网页之间的超链接。
        本质上，这个数据集模拟了一个迷你万维网。


任务简介：

        这个任务的目标是实现一个PageRank算法来对数据集中的网页进行排名。
  
要求：

        (i)对网络图中的死角应用概率为1.0的随机传送。
        (ii)将web图的转换矩阵表示为4×4的分块矩阵，(进化)秩向量表示为4×1的分块矩阵，其中本任务中的分块矩阵参考pyspark.mllib.                linalg.distribud.blockmatrix的数据结构。
        (iii)使用值为0.85的传送常量。
        (iv)将初始秩向量设置为统一向量。
        (v)的误差参数设置𝜀至0.005。
        (vi)迭代计算排序向量的20倍或直到秩向量收敛(错误参数𝜀),以先到期者作准。
        (vii)返回前20个网页(即，从ID 0到ID 19的网页)。
