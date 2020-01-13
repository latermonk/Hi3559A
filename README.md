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

#  yolov3 demo

```
./sample_nnie_main  8   /mnt/nfs/src/mpp/sample/svp/multi-core/nnie/data/nnie_image/rgb_planar/dog_bike_car.jpg


```



##  reference  

###  海思Hi3559AV100/Hi3519AV100 NNIE深度学习模块开发与调试记录 
https://blog.csdn.net/zh8706/article/details/94554337     


###  display rate issue
```
vim  /mpp/sample/svp/multi-core/common/sample_comm_ive.c

change 1080P30  --->>>>   ***1080P60***

```


###   ltshan139's techg blog 

https://me.csdn.net/ltshan139  

###  海思AI芯片(Hi3519A/3559A)方案学习（一）资料以及术语介绍
https://blog.csdn.net/avideointerfaces/article/details/88585654    


###  HiSI3559A   YOLOV3   开发板上运行yolo3模型的代码分析


https://blog.csdn.net/avideointerfaces/article/details/93891881



 #   a better yolov3   Gaussian_YOLOv3
 
 https://github.com/jwchoi384/Gaussian_YOLOv3
