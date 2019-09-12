## 为什么要学pr
现在哪个公司招聘上不写着有github开源经历的 **加分**, 如果你还不能自己独立完成一个开源项目, 但是还想凑个热闹慢慢学习, 你可以从帮助别人找代码或者**文档**的bug开始.

如果你发现了一个项目的bug, 你该如何改正并提交给作者呢? pr就是这样一个功能.

## 总共分4步
[1.fork目标项目](#1fork目标项目)

[2.clone项目到本地](#2clone项目到本地)

[3.修改代码然后commit](#3修改代码然后commit)

[4.pull request](#4pull-request)


## 1.fork目标项目

![](https://user-gold-cdn.xitu.io/2019/9/10/16d1a148da569419?w=1504&h=160&f=jpeg&s=85353)

**fork**就是在自己仓库生成一个目标项目的镜像.

## 2.clone项目到本地
```shell
git clone https://github.com/any86/any-touch.git
```

这里是指克隆"fork到自己仓库的项目"的代码到本地.

## 3.修改本地代码然后commit
比如我们修改**README.md**文件
```shell
git add README.md
git commit -m "docs: 修改标题"
git push
```

如果修改的文件比较多, `git add README.md`替换成`git add .`, 这样会把所有修改的文件移动到暂存区.

## 4.pull request
好了, 现在我们的线上仓库已经是最新的了, 接下来把我们的代码pull(推)到目标项目.


1. 首先在浏览器打开我们fork的项目, 比如: https://github.com/yourname/any-touch.git 
![](https://user-gold-cdn.xitu.io/2019/9/10/16d1a148da5eaca8?w=1195&h=195&f=jpeg&s=74671)
2. 切换到"Pull Request"页面.
3. 点击"New Pull Request"按钮, 然后看到如下界面:

![](https://user-gold-cdn.xitu.io/2019/9/10/16d1a148da25f2f8?w=1101&h=819&f=jpeg&s=397771)

4. 在下方可以进行代码对比, 确认无误后点击"Create pull request"按钮发起"代码合并请求", 然后会提示你写注释.

![](https://user-gold-cdn.xitu.io/2019/9/10/16d1a148da8e6ffd?w=880&h=617&f=jpeg&s=262969)

5. 写好注释后, 点击"Create pull request"按钮, 然后会自动跳转到"目标项目"的仓库下, 可以看你的 pr 记录, 到此 **pr流程** 结束 剩下的就等着作者审查代码后合并你的代码.

![](https://user-gold-cdn.xitu.io/2019/9/10/16d1a148da8b80b3?w=834&h=529&f=jpeg&s=219217)

## 总结
很简单的一个功能介绍, 感谢大家阅读, 如果需要做 pr 练习可以用我的 github 练习. 欢迎 pr.

https://github.com/any86/any-rule/pulls


## 微信群
有任何疑问可以加群(🚀一个可爱的前端群), 知无不言, 言无不尽.

![](https://user-gold-cdn.xitu.io/2019/9/10/16d1a1a8f655ba0f?w=1080&h=1590&f=jpeg&s=135040)