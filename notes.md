1. 二分搜索
注意当前搜索区间的左右边界值是否包含，然后确定更新后的搜索区间是否应该包括mid
判断条件要确定是否有等号
计算mid时要注意边界相加溢出的问题，不应该（left + right) / 2，应该left + (right - left) / 2
