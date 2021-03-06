# 编码：隐匿在计算机软硬件背后的语言

## 电报机与继电器

继电器最初作为电报机长距离通信的中继系统而发明，用于放大微弱信号。而在数字系统中，我们可以将它看做一个可用电控制的开关，用这种开关可以实现逻辑门。

## 我们的十个数字

大多数文明都是建立在以10为基数的数字系统上的，人们用自己的手指来计数。阿拉伯数字系统是和位置相关的，它没有专门表示数字10的符号，但有早期数字系统没有的0。位置计数系统对于非十进制仍然是易于实现计数的。

## 逻辑与开关

集合元素可以通过布尔测试，判断元素是否属于集合表达式表示的集合。属于为1，不属于为0。

## 门

1938年，香农发表了《继电器和开关电路的符号分析》。
在计算机术语中，开关是一种输入设备（input device），输入是控制电路如何工作的信息。
摩根定律：或的非等于非的与，与的非等于非的或。

## 二进制加法器

"*第一台数字计算机在20世纪30年代被建造完成，当时所使用的就是继电器，后来也使用过真空管。今天的计算机使用的是晶体管。*"

## 反馈与触发器

有两个稳定态的电路统称为触发器（Flip-Flop），它可以“记住”某些信息。

## 自动操作

能否控制重复操作或者循环是计算机（computer）和计算器（calculator）的区别。

## 从算盘到芯片

"*继电器、真空管以及晶体管最初都是为了开发放大器设计的，但是通过相似方式连接可以组成逻辑门，而计算机则是由这些部件构成的。*"

## 总线

"*在早期小型计算机中，为了能够长久保存程序和数据，通常在滚动的纸带上打孔，而在需要时，这些程序和数据可以从纸带加载到内存。*"

“*memory(内存)仅仅表示半导体随机访问存储器；storage(存储器)用来指任何的存储设备，通常包括软盘、硬盘和磁带。*”

"*微处理器不能直接从磁盘读取数据，需要将所需的数据从磁盘调入内存(随机访问存储器)，然后它才能对其访问，当然这需要额外的步骤。微处理器还需要执行一段小程序，这段程序会访问磁盘，并将数据从磁盘调入内存。*"

## 操作系统

”*掉电的时候，半导体存储器中的内容就会被全部清零；而首次给它上电的时候，它将处于随机且不可预测的状态。*“

"*软件中断，它与子程序调用很类似，只不过程序不必知道它所调用的子程序的确切地址。*"

"*虚拟内存是指，在磁盘上划出部分空间用作保存临时文件，程序把暂时不需要用的内存块放到临时文件里，待需要时再把它调入内存。*"

"*与汇编语言不同，高级语言通常不依赖于特定的处理器，因此它们通常具有良好的可移植性。因为这种特点，使用高级语言的程序员不再需要关心最终运行程序的计算机的底层结构。当然，如果要在不同类型的处理器上运行程序，则需要用处理器对应的编译器将程序转换成对应的机器码。因此，最后生成的可执行文件仍然只适用于特定的处理器。*"

## 读后感

关于内存和外存的个人理解：在冯·诺依曼结构中，内存对应存储器，外存对应输入输出设备。内存和CPU一样都是逻辑电路，以晶体管为基础，用高低电平表示0和1，断电易失。而外存不是用高低电平表示0和1的，磁盘是用磁极方向，SSD是用浮栅中电子有无，光盘是用反光性，纸带是用孔洞。所以外存中的程序都要先加载(复制)到内存中才能运行。

17章自动操作和23章定点数和浮点数非常精彩。
