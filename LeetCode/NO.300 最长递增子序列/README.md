DP板子，对于数组中的每一个数，都去找前面比他小的，找到了就把他接在后面，然后此时dp[i]就是他前面的那个数的dp[j]+1，最终找到最大的dp就行了
