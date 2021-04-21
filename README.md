# The-first-C-language-program-in-Ubantu

1、下载vmware
2、在ubantu官网下载ios镜像
3、安装时手动修改设定（按照默认安装，会给之后换软件源造成困扰），修改软件源（国内）
4、ctrl+alt+t打开客户终端 
   sudo apt-get update/upgrade(更新列表/软件)
   sudo apt install gcc(编译器)
   sudo apt install vim(编辑器)
5、vim helloworld.c
6、helloworld程序编写
#include <stdio.h>

int main()
{
  printf("hello,world! \n");
  return 0;

}
//i进入编写；esc退出编写；shift+：“输入指令”w（保存）q（退出）；

7、gcc -o helloworld helloworld.c
8、./helloworld 输出
