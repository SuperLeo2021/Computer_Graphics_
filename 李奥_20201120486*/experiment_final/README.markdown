# 计算机图形学综合实验

##   20201120486 李奥
    是在之前实现交互式茶壶的基础上，对三维立体的茶壶进行光照，加入纹理，进行消隐等相关操作
           目的是为了对本学期的计算机图形学实验课有一个更好的总结。
>下面演示渐变纹理的代码
'''
 void makeTexture(void)
{
	int i;
	for (i = 0; i < TEXTUREWIDTH; i++)

	{

		Texture[3 * i] = 255;
		Texture[3 * i + 1] = 255 - 2 * i;
		Texture[3 * i + 2] = 255;

	}
}   

'''
### 演示实例：
>紫色演示  
![紫色纹理运行](./picture/%E7%B4%AB%E8%89%B2.png)
>绿色演示
![绿色纹理运行](./picture/%E7%BB%BF%E8%89%B2.png)
>紫绿色演示
![紫绿色演示](./picture/%E7%B4%AB%E7%BB%BF%E8%89%B2.png)

>  代码地址
>这是一个链接 [./work_final.cpp](https://github.com/SuperLeo2021/Computer_Graphics_/blob/main/%E6%9D%8E%E5%A5%A5_20201120486*/experiment_final/work_final.cpp)
