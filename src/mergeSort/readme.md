归并排序的时间复杂度为O(N*logN)
该算法的核心在于"分治"与有效比较
即：将需要排序的内容不断分割，并通过merge方法实现内部有序，外部无序
这样做的优点在于进行了有效的比较，且利用二分的方法降低了时间复杂度

由于归并排序的每次比较都是有效的，因此归并排序常用于解决"小和"问题
即：当一个数据需要与其他数据作比较而产生计算结果