# 知识点目录
工欲善其事，必先利其器
Git
Maven


markdown 文档知识点

标题：
```
# 一级标题 # 一级标题
## 二级标题 ## 二级标题
### 三级标题 ### 三级标题
```
# 一级标题 # 一级标题
## 二级标题 ## 二级标题
### 三级标题 ### 三级标题

引用：
```
> 引用内容 > 引用内容
```
> 引用内容 > 引用内容



列表：
使用* + - 
```
* 无序列表
* 无序列表

+ 父级列表
    + 恼人
+ 子级列表

1. 有序列表
2. 有序列表
```

* 无序列表
* 无序列表

+ 父级列表
    + 恼人
+ 子级列表

1. 有序列表
2. 有序列表


链接：
```
[这里是对百度的一个链接](https;//www.baidu.com)
https://www.baidu.com
<https://www.baidu.com>
```
[这里是对百度的一个链接](https;//www.baidu.com)
https://www.baidu.com
<https://www.baidu.com>

图片：
```
![图片名称](图片地址)
```
![图片名称](图片地址)








111
```
graph LR
Client-->|请求创建MRAM| RS
RS-->|在一台不忙的NM中创建| MRAM
MRAM-->|向RS申请Cotianer| RS
RS-->|返回C给MRAM| C
MRAM--> Task
Task--> C
C-->NM
```

```math
E = 

mc^2* 

\log 

\sum_a^3 

\times  

\frac{22}{33}
```




```
sequenceDiagram
Client->>RS: 请求创建AppMaster
RS->>MRAppMaster: 选择不忙的节点创建容器
MRAppMaster->>MRAppMaster:创建Task
MRAppMaster->>Client:打印报告
MRAppMaster->>RS:请求Task的容器
RS->>MRAppMaster:响应Task的容器
MRAppMaster->>NM:启动容器
NM->>RS:验证Token并心跳
```


```






```











































