[toc]
 
# 1.在哪学习Git?
 
- https://www.runoob.com/git/git-tutorial.html (菜鸟教程)
- https://git-scm.com/book/zh/v2 （Git入门教程）
- https://blog.csdn.net/tichimi3375/article/details/79844514 （CSDN笔记）
- b站收藏
 
# 2.什么是版本控制
 
```
关于版本控制
什么是“版本控制”？我为什么要关心它呢？ 版本控制是一种记录一个或若干文件内容变化，以便将来查阅特定版本修订情况的系统。 在本书所展示的例子中，我们对保存着软件源代码的文件作版本控制，但实际上，你可以对任何类型的文件进行版本控制。
 
如果你是位图形或网页设计师，可能会需要保存某一幅图片或页面布局文件的所有修订版本（这或许是你非常渴望拥有的功能），采用版本控制系统（VCS）是个明智的选择。 有了它你就可以将选定的文件回溯到之前的状态，甚至将整个项目都回退到过去某个时间点的状态，你可以比较文件的变化细节，查出最后是谁修改了哪个地方，从而找出导致怪异问题出现的原因，又是谁在何时报告了某个功能缺陷等等。 使用版本控制系统通常还意味着，就算你乱来一气把整个项目中的文件改的改删的删，你也照样可以轻松恢复到原先的样子。 但额外增加的工作量却微乎其微。
```
 
# 3.下载安装git
 
- https://git-scm.com/downloads
 
# 4.查看git的配置信息
 
```
git config --list
 
shining star@DESKTOP-6KBTUG2 MINGW64 ~/Desktop/新建文件夹
$ git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=D:/Develop/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
user.name=aliizzwell 这个用户名配置在git中配置一次就记住了
user.email=aliizzwell@163.com 这样邮箱也是配置一次就记住了
```
 
# 5.github搭建项目主页
 
- https://blog.csdn.net/qq_43382853/article/details/104263536
 
![](https://cdn.jsdelivr.net/gh/aliizzwell/pic/img/20200809123337.png)
 
# 6.github搭建个人主页
 
- https://blog.csdn.net/hohaizx/article/details/85066248?utm_medium=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromMachineLearnPai2-1.channel_param&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-BlogCommendFromMachineLearnPai2-1.channel_param
- /index-en.md其实是https://aliizzwell.github.io/index-en.html，要改为 https://aliizzwell.github.io/bdhehohai.github.io/index-en.html
 
## 第一步.Fork别人的项目到我的仓库
 
![](https://cdn.jsdelivr.net/gh/aliizzwell/pic/img/20200809141031.png)
 
## 第二步.选择主题
 
- 参考上面链接有
- 因为他的项目选择了主题也有index.md，所以我么这里直接选择master，点击save就行了。不需要change theme
 
![](https://cdn.jsdelivr.net/gh/aliizzwell/pic/img/20200809141821.png)
 
## 第三步.对图片和跳转进行修改
 
- 因为你Fork之后要搭建主页的话路径是在aliizzwell.github.io下的，和最开始的创建人不一样。所以要进行修改
- ![](https://cdn.jsdelivr.net/gh/aliizzwell/pic/img/20200809142759.png)
- 根目录/指的是https://aliizzwell.github.io/就是你的主页目录
- 图片绝对路径默认为：https://aliizzwell.github.io/zhengjianzhao.jpg
 
- 修改为https://aliizzwell.github.io/bdhehohai.github.io/zhengjianzhao.jpg
- 或者把相对地址/zhengjianzhao.jpg改为/bdhehohai.github.io/zhengjianzhao.jpg
- 静态网页链接也是一样的。
 
## 第四步.修改描述和项目名
 
![](https://cdn.jsdelivr.net/gh/aliizzwell/pic/img/20200809152119.png)
 
- 注意修改了项目名的话图片链接和跳转链接如果有绝对路径必须修改。否则无法访问，所以最好用相对路径。
- 如果绝对路径包含了项目名的话也要修改哦！
