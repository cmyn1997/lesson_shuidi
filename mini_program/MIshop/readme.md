- display: flex;    弹性布局 可以用于容器 也可以用于行内元素
  flex-direction:row; 沿水平主轴让元素从左向右排列
  flex-direction:column; 让元素沿垂直主轴从上到下垂直排
- 知晓了小程序从一个页面拉取数据,这样数据就可以存放在一个页面里,方面后面的使用.详细请见app.js
- 两个页面的数据传输可以用数据缓存和全局app来写
  但是里面有个巨坑，数据多次传输时会覆盖原来的值，用数组的入栈操作也不行，无奈只好又一次使用了数据缓存。把之前的值和现在需要的值一起进行存储。这样可以解决问题，费脑筋啊
  

        
