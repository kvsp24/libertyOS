# l. 尾声
将TTY纳入文件系统的工作暂时不进行了，但为了令TTY能工作，`kernel_main()`中为其指定和硬盘驱动、文件系统进程相同的优先级，使得键盘操作得到响应；另外，我在时钟中断例程内加入了读取CMOS RAM以显示系统时间的功能.

**现在的情况如下:**

![l](screenshot/l.png)
