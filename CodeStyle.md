# 代码风格
<h2>Python</h2>

[代码规范参考](https://www.python.org/dev/peps/pep-0008/)

### 1.缩进
   - 缩进四个空格

### 2.变量命名
   - 驼峰小写的形式
 
### 3.每行最多字符数
   - 每行最多不超过四十个字符
  
### 4.函数的最大行数
   - 函数一般不超过300行

### 5.函数、类命名
   - 类命名每个单词大写，中间用下划线隔开，例如：
```class InfectStatistic```
    
   - 函数命名采用驼峰命名法
```def Get_Country(citys):```

### 6.常量
   - 常量名一般用大写
  
### 7.空行规则
   - 模块级函数和类定义之间空两行
   - 类成员函数之间空一行

### 8.注释规则
   - 单行使用 # 号
   - 多行使用 """ "" 号
  
### 9.空格
   - 给变量赋值时，变量后空1个格，运算符或逗号后空1个格，作为参数时符号前后不空格
   - 使用必要的空行可以增加代码的可读性，通常在顶级定义（如函数或类的定义）之间空两行，而方法定义之间空一行，另外在用于分隔某些功能的位置也可以空一行。

### 10.模块
   - 一般使用小写
   - from . import . 的格式
   - 每个 import 语句只导入一个模块，尽量避免一次导入多个模块
 
### 11.引号
   - 绝大多数情况下都使用 ' '
  
### 12. 编码
   - 若无特殊情况, 文件一律使用 UTF-8 编码
  
### 13.try
   - 代码中要尽量少的出现 异常捕获 的代码，有些临界值或极值你是可以预见的，如果没有预见，那就让代码报错，重新修改代码，这是一个好的方式，加多了异常捕获，反而会导致问题难以定位，劳心劳力，劳民伤财，编码的好心情就没了。

