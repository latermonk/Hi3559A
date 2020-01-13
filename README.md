# Hi3559A
海思3559A开发


#  Compiler DIR
**aarch64-himix100-linux-gcc**   

/opt/hisi-linux/x86-arm/aarch64-himix100-linux/bin/aarch64-himix100-linux-gcc


##  compile the first hisi3559A program
```
#include <stdio.h>

int main()
{
	printf("Hello , 123 !");
	return  0;
}


```



/opt/hisi-linux/x86-arm/aarch64-himix100-linux/bin/aarch64-himix100-linux-gcc  hi.c


```
ls 

a.out

```

exec the binary file though nfs,
```
./a.out 

```


---------------------



##  reference  

###  海思Hi3559AV100/Hi3519AV100 NNIE深度学习模块开发与调试记录 
https://blog.csdn.net/zh8706/article/details/94554337     


###  display rate 
```
vim  /mpp/sample/svp/multi-core/common/sample_comm_ive.c

change 1080P30  --->>>>   ***1080P60***

```








