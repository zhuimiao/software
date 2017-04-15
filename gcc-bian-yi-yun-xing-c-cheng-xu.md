# gitbook
## 本小节知识点：
1. 为什么要用 gcc 编译运行 ？
2. gcc 编译运行 c 程序 的步骤

###1.为什么要用 gcc 编译运行 ？

编译器不同，会导致输出结果不同。 比如用 xcode8.3 运行 c 程序 
```
print("hello world")
```
不会打印任何东西。
```
print("hello world\n")
```
才会打印出来: hello world
###2. gcc 编译运行 c 程序 的步骤
####1. 创建文件 main.c 添加如下代码

```
#include <stdio.h>
#import <string.h>

int main(int argc, const char * argv[]) {
char *str = "lnj";
for(int i = 0; i < strlen(str);i++)
{
printf("%c-", *(str+i));
}
return 0;
}

```

####2. 编译
```
gcc -o main main.c
```
注意：-o 后面紧跟着可执行文件名
####3. 运行
```
./main
```
