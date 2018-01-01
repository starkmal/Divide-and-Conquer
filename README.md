# Partition 分治

## 点分治  

##### p3328 距离状态

模板

##### p3329 race 

转化为判定某个边数是否满足条件即可，处理方式同上  

##### p4367 开店 

动态点分治

构建点分治树，将每个点的子树按年龄排序，算出距离的前缀和

对于每个询问，从u节点开始往上讨论即可

时间复杂度$O(nlog^2n)$ ，空间复杂度$O(nlogn)$  