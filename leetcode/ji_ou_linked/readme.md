# leetcode 328 奇偶链表
    - 这里的奇数节点和偶数节点指的是节点编号的奇偶性，而不是节点的值的奇偶性。

##  给链表设定一个下标index
  开始时设定两个链表，分别为奇偶链表，记住他们的初始节点。后面链接的时候要用。

  - 下标为奇数时(index % 2 != 0),则进入奇数链表
    否则进入偶数链表