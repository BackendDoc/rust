# 切片

Rust的另一种不持有所有权的数据类型：切片（slice）


我们先思考一个问题，编写一个函数，让它实现下列功能：

- 它能接收字符串作为参数
- 返回它在这个字符串里找到的第一个单词
- 如果函数没有找到任何空格，那么整个字符串就返回