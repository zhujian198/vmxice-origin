这个是最原始的vmxice
这个是最原始的vmxice， 当其在3.5.4上运行的时候
要加入 #include<linux/salb.h> 对kmalloc进行支持
make 时，要修改makefie中的LINUX_KERNEL_PATH := /usr/src/linux-$(LINUX_KERNEL)
为当前的linux内核的源码的目录