### linux2.6源码编译  

1. gcc版本需要小于4.6  
  gcc4.5源码: `https://ftp.gnu.org/gnu/gcc/gcc-4.5.4/`  
  (gcc4.5编译不过可尝试4.4)  

2. 编译步骤  
  获取源码  
  解压  
  进入源码目录  
  make i386_defconfig  
  make -j4  
    编译是可能会出现错误，有可能是perl版本过高导致的  
    参考: `https://blog.csdn.net/think_ycx/article/details/80740028`  
