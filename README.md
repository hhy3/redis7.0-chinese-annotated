# redis7.0 中文注释
## 项目介绍：
大家在学习一个热门开源项目的源码的时候，是不是经常会感到不解？或许你是英语不好导致的，也可能是没有注释又无法理解代码意思导致的。这是否令你常常想要放弃通过阅读源码去学习一个项目呢？从今天开始答应我不要再放弃了，好吗？因为redis7.0中文注释它来了！🎆🎇✨🎉<br>
本项目旨在帮助中文区的大家能够更容易的去阅读，学习redis源码🍭🍭<br>
在你学习redis源码的同时，如果你理解了一段源码，我们也希望你可以将你的理解做成中文注释并向本仓库发起pull request来和大家分享你的想法。因为让一个人来完成这么大的工程是极其困难的，所以本项目的开源目的也是想让大家一起来完善本仓库的源码注释。人多力量大！争取达成所有源码都有中文注释的目标！同时让大家都参与源码注释的修改工作，我们的注释也能够集百家之所长！🎉🎉<br>
### 本项目很可能会成为你第一个参与的开源项目！
你只需要翻译源码里某个有较详细英文注释的函数，你就可以发起PR并成为contributor！更好的是你还能带上你自己的理解。除此之外还有更简单的如：修改错别字、修改格式错误或者修改意思错误的注释，你也可以成为contributor。该项目目前仍处于初期，还有很多未完成注释的源码，希望大家能够一起合力把注释填满整个项目！✨✨<br>
本项目灵感来源于《Redis设计与实现》作者黄建宏的redis3.0注释仓库：https://github.com/huangz1990/redis-3.0-annotated<br>
redis仓库链接：https://github.com/redis/redis<br>
点击右上角的star⭐，可以持续关注我们仓库接下来的更新哦!🍭🍭
## 项目进度：
完成度标准介绍：
<li>完成：文件中的每个有必要注释的结构体定义和每个函数都有中文注释。
<li>过半：文件中有中文注释的结构体定义和函数比例过半。
<li>低于一半：文件中有中文注释的结构体定义和函数比例低于一半。<p>


| 文件 | 完成度 |
| - | :-: |
| t_string.c |完成| 
| t_hash.c | 完成 |
| t_list.c | 完成 | 
| t_set.c | 完成 | 
| t_zset.c | 完成 | 
| sds.h | 完成 | 
| quicklist.h | 完成 | 
| sds.c | 过半 | 
</p>
尚未有中文注释的文件不会出现在表格中。<br>
更新日期：2022/5/2

  
## 关于提交PR的方法：
### Step1:
首先你需要fork本仓库到你自己的github仓库，点击右上角的fork按钮🎉🎉<br>
### Step2:
使用git clone命令将本仓库拷贝到你的本地文件，git clone地址请点开项目上方的绿色"code"按钮查看😀😀<br>
### Step3:
在你的本地对代码进行一番精心修改吧！🍉🍉<br>
### Step4:
修改完后，是时候该上传你的改动到你fork来的远程仓库上了。你可以用git bash，也可以使用IDE里的git来操作。对于git不熟的用户建议使用IDE，IDE也更方便写commit信息，别忘了写commit信息哦！当然我们只是增删改中文注释，如果要直接在 github 上编辑也可以。🤔🤔<br>
### Step5:
上传之后，点进你的仓库主页，会出现一个"Contribute"，点击它，选择"Open pull request"，选择好你仓库的分支和你想要在这里合并的分支后，点击"Create pull request"，之后填写你的PR标题和正文内容，就成功提交一个PR啦！🍭🍭

## 关于提交PR的内容：
### 修改内容：
(1) 给未有中文注释的函数添加中文注释。<br>
(2) 修改或删除意思不明确的，意思有误的，有错别字的中文注释。<br>
(3) 修改不标准的注释格式，修改比较严重的标点错误(中文字用英文逗号、句号、括号、引号实际上不需要修改）。<br>
(4) 给中文注释不足的函数添加注释。
### 注释格式：
(1) 只使用多行注释符号/* */，与redis英文注释统一。<br>
(2) 注释里的文字内容要与多行注释符号之间有一个空格。<br>
(3) 同一个多行注释内容中，每一行左端都要加上一个\*，并且对齐。<br>
(4) 英文和中文之间要有一个空格。<br>
(5) 请使用UTF-8编码进行注释。<br>
(6) 在遵守上面的格式前提下可以自由发挥<br>
### 注释建议：
(1) 不需要几乎每一句代码都加上注释，比如多次重复出现的同一句代码我们只需要在第一次出现的时候注释，有些意义显而易见的代码并不需要进行注释。如果你需要对一个函数进行大量的解释说明，可以在函数定义的上方空出多行来写注释。<br>
(2) 在代码上一行起的注释，若注释上一行有代码可以多空一行。<br>
  
### 注释要求：
(1) 若你要对没有中文注释的源码加上注释，请至少完成一个函数的注释工作，不要仅对一个函数的某一小部分进行注释，我们希望每个“勇闯无人区”的“勇士”至少负责一个函数。完成一个函数的注释工作，要在函数定义上方说明该函数的作用，在每个重要的部分和难以理解的部分进行代码注释；对于代码量很少的，且内容没有什么阅读难度的函数，请至少在函数定义上方注释说明该函数的作用。<br>
(2) 本仓库在源码基础上增加和修改中文注释，同时为了注释可以增加空格和空行。若你觉得英文注释存在会影响你的中文注释观感，你可以把英文注释删除，但你最好要在中文注释中保留原英文注释的意思。注意不要修改源代码，不要破坏源代码的结构！如果你真的对源代码有修改的想法，请到redis仓库发起pull request。还有如果你发现了英文注释有误，你想对英文注释进行修改，我们经过审核后可以在这边先进行合并，但同时你也别忘了到redis的仓库提一下pr告知官方哦！（但是我们的仓库是比较旧的，请先检查官方有没有已经修正了）🥇🥇<br>
(3) 对于commit信息，请写清楚你对哪个函数进行了注释的添加或修改。如：“添加setGenericCommand函数的注释”，“修正setGenericCommand函数注释的格式错误”。
## FAQ:
### Q: 该项目是定格在 redis7.0 版本了吗？还是会更新呢？
A: 我们希望项目能够持续更新下去，所以会在redis发行了一个新版本之后逐步与最新版本的代码合并。🍭🍭
### Q: 我发现了一个注释错误，但是我不会发起PR。
A: 如果你不会发起PR，建议上网找个详细的教程，PR并不难。如果你实在不会...你也可以提issue告诉我们哪里有错误来参与修改。
### Q: 我有redis相关的问题，可以在issue讨论吗？
A: 如果你有对redis源码出bug的问题，建议到redis仓库去提issue。如果你有其他的问题（如面试问题，使用问题），命令的相关用法可以到[redis官网](https://redis.io/)查找，网上实在找不到方法可以在这里提出issue。我也希望这里能给大家提供一个讨论redis的环境。
### Q: 我想注释并提交的代码已经被别人提交了。
A: 这是有可能的，我们不希望你每次都攒了一个很多注释的代码再发起PR，每次PR尽量范围小一些，比如做完两三个函数的注释就发起PR，减少和别人的冲突。
### Q: 如果我的PR和别人的PR注释的函数相同怎么办？
A: 我们会选取最好的注释来合并，我们希望把意思最清晰且观感最好的注释展现给大家看。如果你的注释没有被合并，请不要气馁，你可以学习一下被合并的注释对比你的注释优点在哪里，学习之后可以提升你写代码注释的水平哦！🍦🍦
### Q: 我贡献注释能得到什么？
A: 这是一个大家用爱发电的项目，包括我们"CN-Annotation-Team"组织的大家都是用爱发电的，金钱方面是没有利益啦...最重要的是以贡献注释的过程中，你阅读和理解源码之后，并能把它讲明白给大家听，这点对你是受益匪浅的，同时贡献注释给他人也许还能成为你阅读并注释源码的动力。<br>
  除此之外，要是你贡献累计达到50行注释以上，我们会邀请你成为"CN-Annotation-Team"组织的一员！身为"CN-Annotation-Team"组织的一员去完善现有项目的中文注释，或者推动其它热门开源项目的中文注释项目吧！🍭🍭（虽然目前组织还很小也没什么名气，但是这也是个好机会让你可以成为元老级的member啊~）
