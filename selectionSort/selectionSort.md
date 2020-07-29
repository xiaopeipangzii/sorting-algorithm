# 选择排序
选择排序原理非常简单, 每次遍历序列都在未排序的序列中找到最小的值,放到已排序序列的队尾, 重复这个直到全部排序

## 复杂度
1. 最好最坏平均时间复杂度都为O(n²)
2. 空间复杂度为O(1)

## 稳定性
1. 不稳定, 当前元素有相同值的元素时, 如果相同值元素的后面出现了小于当前元素的值,就破坏了当前元素和和当前值相同元素的顺序