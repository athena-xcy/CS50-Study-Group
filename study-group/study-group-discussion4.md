# CS50 学习组第二次招募试译分析

_伊然、郝亚南 Chris、AthenaX([athena-xcy](https://github.com/athena-xcy)) 主讲_

_伊然、郝亚南 Chris 供稿_

_Scarlett([ScarlettSun9](https://github.com/ScarlettSun9))、刀刀([k_huang](https://github.com/karen-huangxt))、Leo([LeoTsui](https://github.com/LeoTsui)) 整理_

_Ming、lyh、Alison、M、Jenny Z([Meijuan Zeng](https://github.com/tomato018))、stronger、AthenaX([athena-xcy](https://github.com/athena-xcy))、Leo([LeoTsui](https://github.com/LeoTsui))参与讨论，对本文亦有贡献_

- [试译例句一（CS50 工具箱）](#%e8%af%95%e8%af%91%e4%be%8b%e5%8f%a5%e4%b8%80cs50-%e5%b7%a5%e5%85%b7%e7%ae%b1)
  - [短句一分析（三个工具箱）](#%e7%9f%ad%e5%8f%a5%e4%b8%80%e5%88%86%e6%9e%90%e4%b8%89%e4%b8%aa%e5%b7%a5%e5%85%b7%e7%ae%b1)
  - [短句二分析（help50）](#%e7%9f%ad%e5%8f%a5%e4%ba%8c%e5%88%86%e6%9e%90help50)
  - [短句三分析（printf）](#%e7%9f%ad%e5%8f%a5%e4%b8%89%e5%88%86%e6%9e%90printf)
  - [短句四分析（style50）](#%e7%9f%ad%e5%8f%a5%e5%9b%9b%e5%88%86%e6%9e%90style50)
  - [试译例句一的参考译文](#%e8%af%95%e8%af%91%e4%be%8b%e5%8f%a5%e4%b8%80%e7%9a%84%e5%8f%82%e8%80%83%e8%af%91%e6%96%87)
- [试译例句二](#%e8%af%95%e8%af%91%e4%be%8b%e5%8f%a5%e4%ba%8c)
  - [短句一分析（it多重并列）](#%e7%9f%ad%e5%8f%a5%e4%b8%80%e5%88%86%e6%9e%90it%e5%a4%9a%e9%87%8d%e5%b9%b6%e5%88%97)
  - [短句二分析（so-and-so）](#%e7%9f%ad%e5%8f%a5%e4%ba%8c%e5%88%86%e6%9e%90so-and-so)
  - [短句三分析（green smiley face）](#%e7%9f%ad%e5%8f%a5%e4%b8%89%e5%88%86%e6%9e%90green-smiley-face)
  - [短句四分析（slug）](#%e7%9f%ad%e5%8f%a5%e5%9b%9b%e5%88%86%e6%9e%90slug)
  - [短句五分析（nothing's going to work）](#%e7%9f%ad%e5%8f%a5%e4%ba%94%e5%88%86%e6%9e%90nothings-going-to-work)
  - [试译例句二的参考译文](#%e8%af%95%e8%af%91%e4%be%8b%e5%8f%a5%e4%ba%8c%e7%9a%84%e5%8f%82%e8%80%83%e8%af%91%e6%96%87)

## 试译例句一（CS50 工具箱）

> All right, so just to recap then, three tools to have in the proverbial toolbox now are help50 anytime you see an error message that you don't understand, whether it's with make or Clang or, perhaps, something else. Printf-- when you've got a logical program -- a bug in your program, and it's just not working the way it's supposed to or the way the problem set tells you it should, and then style50, when you want to make sure that, does my code look right in terms of style, and is it as readable as possible?

### 短句一分析（三个工具箱）

> All right, so just to recap then, three tools to have in the proverbial toolbox now

句中主语被省略了，更好的翻译方式是把主语回避掉 而不是自己填上主语。
类似这样：

> 好，那么回顾一下

原文没有主语，在不影响理解的情况下，就不需要加。如果原文是代词，如果指代较远，那尽量重现一下具体指代。

在下半句

> three tools to have in the proverbial toolbox

其中，proverbial toolbox这里翻译的五花八门。试译答案里的几种译法有:

> 1.谚语的工具箱  
> 2.众所周知的工具箱  
> 3.常见的工具箱  

第一种可能是来自机器翻译或者没有联系上下文，不太可取。大多数人翻译成了 “众所周知”。“众所周知”虽然是 proverbial 最准确的中文释义，但是代到文中和“工具箱”搭配就很怪，中文一般不会这么说。在没有很好的直译的情况下 “常见工具”这个翻译比较直白，信息量也很充分。还有另外一个译本，“熟知的工具”，也是通顺易懂。所以对于这半句来讲，最佳翻译版本是“在大家熟知的工具箱中有三个工具”。

当然，“工具箱”在这个语境下不好理解，所以翻译成“常见工具”也可以。由于教授个人语言习惯很官方正式，所以还是官方文件的翻译风格比较贴这门课程的翻译。

综上所述，在翻译时还是要符合翻译原则，结合语境，尽量直译，适度意译。

### 短句二分析（help50）

> are help50 anytime you see an error message that you don't understand, whether it's with make or Clang or, perhaps, something else.

然后从整句结构来看，接下来该分别讲三个工具。这里可以适当意译，加上“第一”、“第二”、“第三”，让语句更连贯。如果看视频翻译的话，教授在屏幕上有列出这三个工具，所以[【翻译原则一】不盲翻](../translation-group/principles-of-subtitle-translation.md#【翻译原则一】严禁盲翻：只有结合场景剧情才能翻译的准确出彩)是很重要的。

当然没加的话 只要把这句话翻译通顺也可以。句意准确最重要，然后尽量直译，可以考虑意译来 “雅”。 

> whether it's with make or Clang or, perhaps, something else.

这里涉及到一点专业知识，有关cs50 sandbox中的编译方式。在CS50 sandbox中 make+文件名是编译，Clang也是一种编译工具，所以以此类推，这里的 “something else”可以按照“适量意译”“让句子更加通顺”的原则来讲。

好多翻译译本写的是“无论是用 make，clang，还是其他编译的”，把 something else 补充引申了一下，这是完全可以的，而且更有助于理解。

### 短句三分析（printf）

> Printf-- when you've got a logical program -- a bug in your program, and it's just not working the way it's supposed to or the way the problem set tells you it should,

从整体上看，这半句破折号后面的三个短句有着递进关系。用简单并列来翻译，不符合计算机的逻辑。“先报错，不报错再查运行结果，最后再查代码风格”，整体上是类似这样的一种递进关系。

这句中第一个要注意的细节是

> logical program

这里有两种争议：一种是认为这个是 David 的口误，因为在视频中有着明显的停顿和表情语气，而且这个说法确实不太符合日常的说话讲解习惯，所以这么理解是可以的，可能是想说 logical problem 但是口误了。在译本中，可以跳过 logical 直接翻译成程序中有 bug；另外还有一种翻译版本，是说“逻辑上有问题的程序”，也就是说，虽然没有报错，但是没有跑出来我们想要的结果，这样也可以解释得通。

第二个细节是

> problem set

这个是作业集的意思。

### 短句四分析（style50）

> and then style50, when you want to make sure that, does my code look right in terms of style, and is it as readable as possible?

这个是第三个工具。从句子结构上看，这个是两个从句组成的，这两个从句相互之间可保持并列关系。

这里细节上

> code style

翻译成代码风格比较流畅; 而国内老师用“代码格式”较多，也可以这样翻译。

> as readable as possible

翻译成“是否尽可能可读”比较流畅。readable 是计算机里的概念，意为可读性，就是自己写的代码，别人能看懂。有些程序虽然在计算机那里执行都是一样的，但是别的程序员很难看懂。这就不利于程序员之间合作和未来代码的维护。

这个短句一个较好的译本为：

> 当你想要确保你的代码风格良好 并且具备极高可读性

### 试译例句一的参考译文

> 好，我们现在来复习一下，常用工具箱里的三种工具：1. help50, 用于你不理解的错误讯息，可以是 Make, Clang 或其他编译器产生的；2. Printf，用于处理程序中出现 bug、程序无法正常运行时；3. Style50，用于确保所写代码是否风格一致以及是否可读。

## 试译例句二

> It's looking at my code, it's getting ready for submission, it's now uploading it to GitHub.com, and once it's on the servers, then it's going to tell CS50 server, here is so-and-so's submission,
go ahead and run a few automated tests on it, checking therefore its correctness, and hopefully we're about to see some green, happy smiley faces, and voila, yes,
it looks like this check50 command for this problem or slug, so to speak--checked that hello.c exists, because if I forgot to write the file
or if I misnamed it, nothing's going to work.

### 短句一分析（it多重并列）

> It's looking at my code, it's getting ready for submission, it's now uploading it to GitHub.com

重点：it的多重并列

首先结合视频，可以明白it指代的是屏幕上运行的画面

大家的常见译法是逐字翻译

> 它正在查看我的代码 它正在准备提交……

由于David说话飞速，字幕闪现的时间不会超过2秒，所以推荐适当意译，省去部分的主语“它”：

> 它正在查看我的代码 之后准备上传 现在代码正在上传到Github

tips: 这一句话中，短句多，主语相同，省略主语不影响理解，因此可以省略

### 短句二分析（so-and-so）

> and once it's on the servers, then it's going to tell CS50 server, here is so-and-so's submission

重点：so-and-so

首先它的英文释义是：

> _noun._ a person or thing whose name the speaker does not need to specify or does not know or remember.

所以翻译成

> 某/某某/某某某/谁/谁谁/谁谁谁

都是可以的

但是译成“这样这样”“如此的”不太合适

tips: 翻译时遇到陌生的短语，推荐查看英文释义与前后文做对比

### 短句三分析（green smiley face）

> go ahead and run a few automated tests on it, checking therefore its correctness, and hopefully we're about to see some green, happy smiley faces, and voila, yes

重点：green smiley face

这个如果直译的话，就是“绿色快乐的笑脸”

其实这一段后面David还讲了一段，其中有

> green, happy smiley faces  
> red unhappy face  
> yellow flat face

为了使字幕简洁，也为了符合中文习惯，可以直接译为

> 绿色笑脸  
> 红色怒脸  
> 黄色平脸

![image](https://t3.ftcdn.net/jpg/02/02/82/40/240_F_202824017_c0tmyNaowtZT0nJbKSjeH7McGzj5UMFx.jpg)

也可以给它们起外号

> 高兴绿  
> 悲伤红  
> 平静黄

### 短句四分析（slug）

> it looks like this check50 command for this problem or slug, so to speak

重点：slug

slug本义为"鼻涕虫"，当然我们并不能这样直接翻译。

在本语境中，slug 的含义应该这样理解：

比如，你想让你的网站域名叫做：`www.example.com/article/The 46 Year Old Virgin`。但是，由于URL规则需要用`%20`替代空格。就变成了：`www.example.com/article/The%2046%20Year%20Old%20Virgin`。

这样看起来就十分不美观，也不好用。因此，`-`连接单词，将链接写为：`www.example.com/article/the-46-year-old-virgin`。在URL中唯一确定的一串字符串，就叫做slug。

比如链接：[`https://stackoverflow.com/questions/427102/what-is-a-slug-in-django`](https://stackoverflow.com/questions/427102/what-is-a-slug-in-django)。

其中的`what-is-a-slug-in-django`结构，就是slug。而且该链接也解释了slug的含义。

但是，在中文中没有特定词语对应本语境的slug的含义。所以，翻译的时候建议保留英文。

### 短句五分析（nothing's going to work）

> checked that hello.c exists, because if I forgot to write the file or if I misnamed it, nothing's going to work.

重点：nothing's going to work

很多同学翻译为

> 一切都白费  
> 什么都不会发生

直译看上去没有问题，但是结合前后文的话，可能会有点“太大了”

它的实际含义是：屏幕上加载的这种情况不会发生

所以更准确的译法为

> 它就不会这样运行

tips: 这是照顾语境，结合前后文的翻译原则

### 试译例句二的参考译文

> （连接GitHub服务器) 我的代码正在被确认，之后准备上传…现在代码正在上传到GitHub.com。当代码传到服务器上的时候，它就会告诉CS50服务器，这是什么-什么的代码，并自动运行一些测试，以测试代码是否正确。理想的话，我们会看到绿色的笑脸，然后好啦，这就是Check50对这个代码做的一些操作-也可以叫页面记录（slug）。（第一行）检查了hello.c是否存在，因为如果我忘了写这个文件或者我把文件名搞错了，那什么操作都执行不了的。——林雪勤

> (check50)在检查所写的代码，它在做提交准备，它在上传至GitHub.com. 等它上传至服务器后，会告诉CS50服务器这是提交的代码，让服务器对代码运行自动检测，检查其正确性。希望我们能看见绿色的笑脸，那么太好了，是的，check50程序检验到hello.c已经建立了，因为如果我忘记写这个文件或者我写错了文件名，它不会这样运行。——钟鸣
