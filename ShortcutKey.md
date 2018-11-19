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

1. 书签

		创建书签		ctrl+k, ctrl+k
		上一书签		ctrl+k，ctrl+P
		下一书签		ctrl+k, ctrl+N
		下一书签		ctrl+k, ctrl+L

1. 快速查找

		下一个		ctrl+F3
		上一个		shift+F3

1. 剪切复制粘贴
	
		复制整行代码：光标停在该行，CTRL+C，再粘贴CTRL+V

		剪切整行代码：光标停在该行，CTRL+X
		
		删除整行代码：光标停在该行，CTRL+L
			

1. 滚动条

		使用滚动条预览整个文件：工具—>选项—>文本编辑器—>所有语言—>滚动条—>使用垂直滚动条的缩略图模式—>宽		

1. 插入

		在光标所在行的上面插入一行：CTRL+Enter

		在光标所在行的下面插入一行：CTRL+Shift+Enter

1. 选择

	　　1)选中从光标起到行首间的代码：使用组合键“Shift + Home”;
	　　2)选中从光标起到行尾间的代码：使用组合键“Shift + End”。

1. 快速切换窗口

		使用组合键“Ctrl+Tab”(此时可以打开IDE的导航，获得鸟瞰视图)。

1. 快速隐藏或显示当前代码段

		使用组合键“Ctrl+M,M”(记住：要按两次M哦)。

1. 跳转到指定的某一行
 
	　　1)方法1：组合键“Ctrl+G”;
	　　2)方法2：单击状态栏中的行号。


1. 全屏显示/退出全屏显示
　　
		使用组合键“ SHIFT + ALT + ENTER ”。


1. 书签






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