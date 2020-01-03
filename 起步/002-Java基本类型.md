# Java基本类型

##### 啥是基本类型

##### 小学时数学入门，基本类型是由123这样的数字以及加减乘除这样的计算方式组成，
现在学习Java入门，那么也就不必纠结为啥是int，double之类的了，因为电脑就认这个，所以只能死记硬背下来


1.Java基本类型：

> | 类型       | 长度 | 默认值 |
> | ---------- | :--- | :--- | 
> | byte |8位|0|
> | short |16位|0|
> | char |16位的Unicode 字符|''|
> | int |32位|0|
> | float |32位|0.0f|
> | double |64位|0.0d|
> | long |64位|0L|
> | boolean |true/false|false|

2.包装类型：

粗浅的理解是因为单纯的基本类型不适应一些场景的使用，所以给这些基本类型包了一层外壳，可以适用更多的场景

> | 类型       | 包装类型 |
> | ---------- | :--- |
> | byte |Byte|
> | short |Short|
> | char |Character|
> | int |Integer|
> | float |Float|
> | double |Double|
> | long |Long|
> | boolean |Boolean|


源码随笔：

1.Byte类: extends Number implements Comparable<Byte>

equals方法：本质上还是对比被包装的byte的值，比较大小时推荐使用这个方法

2.Short类:

reverseBytes方法：进行数值转换，具体用途还未参透

3.Integer：

无符号和有符号：符号代表二进制最高位，0代表正数，1代表负数
补码就是负数在计算机中的二进制表示方法





