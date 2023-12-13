## Markdown文档使用

本文档旨在记录一些Markdown格式文档的使用技巧，便于后期查询

### 图片迁移方法、

应该尽可能使用相对路劲进行图片的插入

e.g

第一张图片使用相对路径插入，插入的格式如下：

```
![](../Markdown/Picture/2003308.jpg)
```

![](../Markdown/Picture/2003308.jpg)

第二张图片使用绝对路径插入，其插入格式如下所示

```
![](C:\Users\15338\Desktop\Markdown\Picture\2003308.jpg)
```

![](C:\Users\15338\Desktop\Markdown\Picture\2003308.jpg)

使用相对路径的方法，在markdown文档所在文件夹下，创建任意命名的文件夹用于存放图片，在插入图片时使用 ../文件夹名/图片名，以此形式插入图片，可以使markdown文档迁移时图片仍然可以显示。
