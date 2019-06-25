# Labyrinth
非常简单的随机生成迷宫的算法,用两种方式:Prime,DFS实现

快要大四了,要赶紧复习下数据结构好找工作,哈哈哈哈哈,所以最近在看图相关的算法,光看书没什么感觉,准备实践一下,写个迷宫算法

主要用Prim算法和DFS算法实现了一遍,没有用BFS是因为Prim的思路跟BFS的其实差不太多,但是看别的博客都说Prim比较自然

思路其实大同小异,主要为:常见迷宫(即任意两点间都能够找到路径,且仅有一条成功路径),迷宫可看做一组连通图(用数组储存),默认所有点间都为墙,我们需要做的就是遍历整个图中所有的点,并且不重复访问,在遍历图的过程中将相邻(指的是上下左右相邻)的两个点间的墙随机打通;满足条件的常见算法有:Prim,Kruskal,DFS,BFS,(另外有个博客中写到了递归分割算法,但是因为本菜很懒没有去具体了解)

具体实现效果图如下:
由Prim实现:

![Image text](https://github.com/Bigbao123/Labyrinth/blob/master/prim.png)

由DFS实现:

![Image text](https://github.com/Bigbao123/Labyrinth/blob/master/DFS.png)


如果喜欢可以给我一个小星星呀!

