## 字符串和数子转化
std::to_string , c++11引入

## 左值右值
首先左值右值都是针对表达式而言，
- 左值：可以在=左侧的表达式  表达式结束之后依然存在的持久对象  对于对象的引用必须是左值（常量引用除外）
- 右值：只能在=右侧的表达式  表达式结束之后不存在的临时对象