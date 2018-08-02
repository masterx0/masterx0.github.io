# Java存储位置总结

1.寄存器：位于处理器内部，是最快的存储区根据需求进行存储空间分配，不受程序从外部控制

2.堆栈：位于RAM内存中，速度仅次于寄存器，存储对象引用

3.堆：同样位于RAM内存中，用于存储所有Java对象，是GC作用的主要区域

4.常量存储区：位于ROM中，通常直接存放在程序内部

5.非RAM存储：存储形式包括流对象和持久化对象等，数据完全存放在程序之外