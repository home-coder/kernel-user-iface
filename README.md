# kernel-user-iface
多个单元文件分别列举内核与用户空间交互常用措施，并以实际开发中的使用为示例
ioctl ：可以是gpio或者fake_mem的处理
sys :drivers/misc/rk_info.c芯片的chipid即serialno的读取
proc：链表形式给出设备信息
