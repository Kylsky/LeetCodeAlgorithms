##题目：
给定两个有序列表，将其合并后返回
##举例：
Input: 1->2->4, 1->3->4
Output: 1->1->2->3->4->4
##思路：
1. 遍历两个队列，两两比较，小的放入新队列中,考虑时间复杂度为O(n^2)，空间复杂度为O(n)，
我没写出来，我真蠢，淦！
2. 通过方法递归调用,我怎么想不到呢，淦！
3.将所有数据放入list中，利用Collections的sort方法排序，排序完成后依次放入ListNode中