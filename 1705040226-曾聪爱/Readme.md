1、开发工具：Dreamwear
   开发语言：HTML+CSS+JavaScript
2、运行环境：谷歌浏览器
3、功能描述：
   此项开发是通过form输入表单，并用onkeyup对input的数据进行实时更新，通过在输入框中输入年份Y，可求出在这一年份中对计算机存储容量的需求；通过输入年份，字长，可求出对应年份存储器的价格；通过输入一名程序员每天可开发出的指令数以及其月薪、所处年份、字长，可求出使存储器装满程序所需要的成本。
其中：
    onkeyup：键盘按下的时候会触发onkeydown，松开键盘时会出发onkeyup，从而实现实时响应
    parseInt：parseInt() 函数可解析一个字符串，并返回一个整数。
教材解答：
   第一问：存储容量需求M=4080*e^(0.28*(1985-1960)=4474263（字）
                 存储器价格P=0.048*0.72^(1985-1974)*4474263=5789（美元）
   第二问：使存储器装满程序所需要的成本：（4474263/（10*30））*4000=59656843（美元）
   第三问：存储容量需求M=4080*e^(0.28*(1995-1960)=73577679（字）
                 存储器价格P=0.003*0.72^(1995-1974)*73577679*32=7127（美元）
                 使存储器装满程序所需要的成本：（73577679/（30*30））*6000=490517862（美元）
4、源代码文件说明
   26.html：代码运行文件，可用谷歌等浏览器运行。
   26.txt:源代码
   Readme.xml:对程序进行的说明。


