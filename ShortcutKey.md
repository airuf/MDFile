#VS2015
----------
1. 结构体定义的时候要赋值怎么办
	初始化赋值。

1. 各种类型的字节长度 bytes
	int:  4
	short:2
	char: 1
	long: 4
	long long : 8
	double:     8
	long double:8
	char *:     4
	ba[5]:     10
	struct BBB:24

1. strlen sizeof区别
	strlen计算字符串的长度  直到'\0'
	sizeof 计算整个的长度  如int a[100]  sizeof (a) =100;

1. strcpy返回值 
	实现链式表达式
	len = strlen ( strcpy ( s2 , s1+1 ) );

1. 对齐
	ctrl a
	ctrl k
	ctrl f








#PyCharm
-------
setting -> keymap

ctrl + alt + l		quick align
shift + enter		start new line

##other
import time 

time.sleep(3)

-----------------------
![](https://i.imgur.com/EBGuMXe.png)