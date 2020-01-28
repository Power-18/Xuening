和为k的数组的个数
给定一个整数数组和一个整数 k，你需要找到该数组中和为 k 的连续的子数组的个数。

示例 1 :

输入:nums = [1,1,1], k = 2
输出: 2 , [1,1] 与 [1,1] 为两种不同的情况。

说明 :

    数组的长度为 [1, 20,000]。
    数组中元素的范围是 [-1000, 1000] ，且整数 k 的范围是 [-1e7, 1e7]。
思路：*本题首先需要的是数组中所有和为k的子数组，其次需要记录此类子数组的个数，用一个计数器来实现
     *要保证找到每一个和为k的子数组，我的方法是两次遍历数组，和冒泡排序有些相似

