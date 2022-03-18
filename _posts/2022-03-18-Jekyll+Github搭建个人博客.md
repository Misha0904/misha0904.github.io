---
title: Jekyll + Github 搭建个人博客
categories: [杂记]
comments: true
---

# Jekyll + Github 搭建个人博客



>   今天教大家使用 Jekyll+Github 来搭建一个简易的 个人博客，不需要服务器，不需要域名，只需要5分钟！



### 1.注册Github 账号

注册一个Github账号 ， 大家应该都有，这个我就不多说了。。 



### 2. Fork jekyll-now 项目

>   使用jekyll-now 项目可以快速搭建一个简易的博客， 下面先上Github上去找到这个项目并且 Fork 一下



#### 2.1 fork jekyll-now 项目

![image-20220318132626093](https://cdn.askajohnny.com/image-20220318132626093.png)



**Fork 后如下**

![image-20220318132705033](https://cdn.askajohnny.com/image-20220318132705033.png)



#### 2.2 Settings 设置 Repository name 

**注意点**：

-   repository name 需要 .github.io 结尾
-   name 需要 和 你的 名称一致，最好小写，经过测试 随意的名称应该是不行的



![image-20220318142157287](https://cdn.askajohnny.com/image-20220318142157287.png)





### 3. clone 项目 添加一个md 文件



#### 3.1 clone 刚刚fork的项目

![image-20220318133130190](https://cdn.askajohnny.com/image-20220318133130190.png)



#### 3.2 进入_posts 文件夹下面添加一个 md文件

-   可以随便找一个 md文件 丢进去，注意格式要是 2022-03-18-XXX.md  ，就是  日期-标题.md
-   默认 需要在md 前面添加 --- 的格式 Input Yaml Front Matter，可以复制 Hello-World.md 的前缀

![image-20220318142719596](https://cdn.askajohnny.com/image-20220318142719596.png)







![image-20220318134445407](https://cdn.askajohnny.com/image-20220318134445407.png)



#### 3.3 git push 变更到 Github 

![image-20220318134531492](https://cdn.askajohnny.com/image-20220318134531492.png)





### 4.打开项目的 GitHub Pages 

进入项目—》Settings-》 Github Pages



![image-20220318134720694](/Users/johnny/Library/Application Support/typora-user-images/image-20220318134720694.png)

点击上面的Check it out here!   就可以看到路径了！ 

![image-20220318142405789](https://cdn.askajohnny.com/image-20220318142405789.png)





**直接访问 https://askajohnny.github.io/** ， 可以看到 效果就出来了，已经可以正常显示我上传的 md

![image-20220318142351113](https://cdn.askajohnny.com/image-20220318142351113.png)



### 5. 更换主题

>   可以看到 上面的 默认主题不是太美观， 那我们来尝试换一个主题！
>
>   [jekyll 主题连接](http://jekyllthemes.org/)



#### 5.1 选择一个 主题 如 Catbook

可以直接下载，也可以直接去clone github 地址 [catbook Github主题连接](https://github.com/starry99/catbook)



![image-20220318143152378](https://cdn.askajohnny.com/image-20220318143152378.png)





#### 5.2 上传catbook代码 并且覆盖 刚刚的 仓库

![image-20220318143659192](https://cdn.askajohnny.com/image-20220318143659192.png)



注意：catbook 规定 md 文件的头部 需要 指定 titile 和 categories 类别

title: NIO基本概念和使用
categories: [socket]
comments: true



#### 5.3 新建类别 categories  

类别可以在 categories 下面新建 index.html 可以直接copy 原本的 

![image-20220318143853660](https://cdn.askajohnny.com/image-20220318143853660.png)



#### 5.4 修改 **_config.yml** 

可以指定你自己的  头像， name 等 

![image-20220318144246866](https://cdn.askajohnny.com/image-20220318144246866.png)

#### 5.5 上传md 到 _posts 目录下



一样的把 md文件传到 _posts 目录下面





### 6.效果展示

>   我这里修改了一点 css 样式，加宽了md 展示区域 ，可以自行修改

![image-20220318144342245](https://cdn.askajohnny.com/image-20220318144342245.png)



![image-20220318144401093](https://cdn.askajohnny.com/image-20220318144401093.png)





### 总结

>   如果想拥有一个自己的博客 又不想花钱的。。可以试试 简单快速
