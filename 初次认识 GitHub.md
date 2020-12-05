### Guide for new github users
### 给Github新手的入门指导


1.写在前边的话，为什么要写CitHub?
跟朋友在交流的时候听到求职的时候发现有些公司要附Github帐号，一个优秀的 GitHub 账号当然能让你增色不少。自己之前听说过，但没有花时间研究，最后花了时间看了CitHub的文档，还有一些程序员写的的blog，就写下来了。

2.GitHub 是什么？
gitHub是一个面向开源及私有软件项目的托管平台，因为只支持git 作为唯一的版本库格式进行托管，故名gitHub。

GitHub Logo

全球顶级科技公司纷纷加入 GitHub ，并贡献他们自己的项目代码

Google: https://github.com/google
苹果: https://github.com/apple
Facebook: https://github.com/facebook
Twitter：https://github.com/twitter
微软：https://github.com/microsoft
Square：https://github.com/square
阿里：https://github.com/alibaba

全球顶级开源项目都优先选择在 GitHub 上开源

Linux：https://github.com/torvalds/linux
Rails：https://github.com/rails/rails
Nodejs：https://github.com/nodejs/node
Swift：https://github.com/apple/swift
CoffeeScript：https://github.com/jashkenas/coffeescript
Ruby：https://github.com/ruby/ruby

全球顶级编程大牛加入GitHub

Linux 发明者 Linus Torvalds：https://github.com/torvalds


Rails 创始人 DHH：https://github.com/dhh


被称为「Android之神」的 JakeWharton：https://github.com/JakeWharton， 你们用的很多开源库如 ButterKnife、OkHttp、 Retrofit、 Picasso、ViewPagerIndicator 等都是出自他之手！



3.注册 GitHub
1.先去 GitHub 官网「https://github.com」注册「Sign Up」个账号，注册页面如下：


这个应该没啥说的，需要填用户名、邮箱、密码，值得一提的用户名请不要那么随便，最好取的这个名字就是你以后常用的用户名了，也强烈建议你各大社交账号都用一样的用户名，这样识别度较高，比如我的博客域名、GitHub、知乎等其他社交账号 ID 都是 stormzhang ，微博是因为被占用了，无奈换了个id，而且这个用户名以后在 GitHub 搭建博客的时候默认给你生成的博客地址就是 username.github.io ，所以给自己取个好点的用户名吧。

填好用户名、邮箱、密码紧接着到这一步：


GitHub 有两种，一种是公开，这种是免费的，就是你创建的项目是开放的，所有人都能看得到；另一种是私有，这种是收费的，这种一般是很多企业在使用 GitHub 的私有仓库在托管自己的项目，这也是 GitHub 的一种盈利模式对于个人你就直接默认选择公开的就行了。

注册成功之后你会到 GitHub 的主页面来：

你如果是新注册的可能看到的跟我不一样，因为你们新用户，没有自己的项目，没有关注的人，所以只有一个导航栏。

导航栏，从左到右依次是 GitHub 主页按钮、搜索框、PR、Issues、Gist（这些概念后面会讲的）、消息提醒、创建项目按钮、我的账号相关。
我的 Timeline，这部分你可以理解成微博，就是你关注的一些人的活动会出现在这里，比如如果你们关注我了，那么以后我 star、fork 了某些项目就会出现在你的时间线里。
我的项目，这部分就不用说了，如果你创建了项目，就里就可以快捷访问。
点击下图的 Your profile 菜单进入到你的个人 GitHub 主页。


2.设置及完善你的 GitHub

到设置页面来设置一些基本信息：


3.一些 GitHub 的基本概念
Repository
仓库的意思，即你的项目，你想在 GitHub 上开源一个项目，那就必须要新建一个 Repository ，如果你开源的项目多了，你就拥有了多个 Repositories 。

Issue
问题的意思，举个例子，就是你开源了一个项目，别人发现你的项目中有bug，或者哪些地方做的不够好，他就可以给你提个 Issue ，即问题，提的问题多了，也就是 Issues ，然后你看到了这些问题就可以去逐个修复，修复ok了就可以一个个的 Close 掉。

Star
这个好理解，就是给项目点赞，但是在 GitHub 上的点赞远比微博、知乎点赞难的多，如果你有一个项目获得100个star都算很不容易了！

Fork
这个不好翻译，如果实在要翻译我把他翻译成分叉，什么意思呢？你开源了一个项目，别人想在你这个项目的基础上做些改进，然后应用到自己的项目中，这个时候他就可以 Fork 你的项目，这个时候他的 GitHub 主页上就多了一个项目，只不过这个项目是基于你的项目基础（本质上是在原有项目的基础上新建了一个分支，分支的概念后面会在讲解Git的时候说到），他就可以随心所欲的去改进，但是丝毫不会影响原有项目的代码与结构。

Pull Request
发起请求，这个其实是基于 Fork 的，还是上面那个例子，如果别人在你基础上做了改进，后来觉得改进的很不错，应该要把这些改进让更多的人收益，于是就想把自己的改进合并到原有项目里，这个时候他就可以发起一个 Pull Request（简称PR） ，原有项目创建人就可以收到这个请求，这个时候他会仔细review你的代码，并且测试觉得OK了，就会接受你的PR，这个时候你做的改进原有项目就会拥有了。

Watch
这个也好理解就是观察，如果你 Watch 了某个项目，那么以后只要这个项目有任何更新，你都会第一时间收到关于这个项目的通知提醒。

Gist
有些时候你没有项目可以开源，只是单纯的想分享一些代码片段，那这个时候 Gist 就派上用场了！

4.创建自己的项目
点击顶部导航栏的 + 可以快速创建一个项目，如下图：


创建一个项目需要填写如上的几部分：项目名、项目描述与简单的介绍，你不付费没法选择私有的，所以接着只能选择 public 的，之后勾选「Initialize this repository with a README」，这样你就拥有了你的第一个 GitHub 项目：



可以看到这个项目只包含了一个 README.md 文件，但是它已经是一个完整的 Git 仓库了，你可以通过对它进行一些操作，如watch、star、fork，还可以 clone 或者下载下来。

这里提一下 README.md ，GitHub 上所有关于项目的详细介绍以及 Wiki 都是基于 Markdown 的，甚至之后在 GitHub 上搭建博客，写博客也是如此，所以如果还不懂 Markdown 语法的，建议先去学习下。Markdown教程

