# Visual studio 2022创建Chapter 0 demo

## 创建Win32项目

<img src="C:\Users\jaycecai\AppData\Roaming\Typora\typora-user-images\image-20240825190045896.png" alt="image-20240825190045896" style="zoom:50%;" />

<img src="C:\Users\jaycecai\AppData\Roaming\Typora\typora-user-images\image-20240825190142592.png" alt="image-20240825190142592" style="zoom:50%;" />

<img src="C:\Users\jaycecai\AppData\Roaming\Typora\typora-user-images\image-20240825190212468.png" alt="image-20240825190212468" style="zoom: 50%;" />

## 创建文件

BoxApp.cpp使用Chapter 6的内容复制一份。还有相应的Shaders文件夹。

其他.h和.cpp文件添加Common下已有的内容。

![image-20240825190232950](C:\Users\jaycecai\AppData\Roaming\Typora\typora-user-images\image-20240825190232950.png)



## 编译报错

Visual Studio 2022的编译检查比 Visual studio 2015要更加严格。会出现以下编译错误。

<img src="C:\Users\jaycecai\AppData\Roaming\Typora\typora-user-images\image-20240825190448424.png" alt="image-20240825190448424" style="zoom:67%;" />

修改项目属性，符合模式选择 否。

![image-20240825190522790](C:\Users\jaycecai\AppData\Roaming\Typora\typora-user-images\image-20240825190522790.png)



## 结果

编译成功运行可以看到以下结果：

![image-20240825190707978](C:\Users\jaycecai\AppData\Roaming\Typora\typora-user-images\image-20240825190707978.png)

## Reference

[vs2022创建win32项目_vs2022 win32项目-CSDN博客](https://blog.csdn.net/weixin_49371944/article/details/126373075)

[《DirectX 12》龙书Chapter 0 踩坑_龙书项目配置要求左值-CSDN博客](https://blog.csdn.net/qq_34813925/article/details/112787898)

