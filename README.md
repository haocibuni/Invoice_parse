# 发票转化为Excel

介绍将pdf格式的发票转化为Excel和json，并为未征税和征税的发票单独整理

## 发票格式

![image-20220916015257578](http://nas.wulei.co:5543/2022/09/image-20220916015257578.png)

## 程序使用

安装依赖环境

```
pip install -r requirements.txt
```

运行程序后 输入命令：load 发票文件夹路径

![image-20220916015857934](http://nas.wulei.co:5543/2022/09/image-20220916015857934.png)

## 运行结果

excel结果如下所示：

![image-20220916020026380](http://nas.wulei.co:5543/2022/09/image-20220916020026380.png)

json结果如下所示：

![image-20220916020110238](http://nas.wulei.co:5543/2022/09/image-20220916020110238.png)

根据税率来判断征税和未征税，将征税和未征税的发票分别保存到以下两个文件夹

![image-20220916020301393](http://nas.wulei.co:5543/2022/09/image-20220916020301393.png)

