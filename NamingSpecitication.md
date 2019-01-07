#命名规范
--------
##变量
nState
commName


##函数内的自由变量
static int  \_data\_length = 0, \_count\_time = 0;


##结构体
OAFrame
ButtonState


##结构体定义
BTNSTA r\_openButton, r_closeButton, switchButton;


##函数
bool SetSerialPort(int portID, unsigned int baudRate)
void Close();

##头文件的顺序


##审核流程：
1. 得到代码
1. 和代码人审核
1. 发送excel审核初稿
1. 待回复 发送二稿
1. 开会 最终稿
1. 存在seafile

