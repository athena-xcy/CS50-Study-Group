# CS50学习组第二次招募试译分析

_AthenaX([athena-xcy](https://github.com/athena-xcy))、伊然 主讲_

_伊然 供稿_

_Scarlett([ScarlettSun9](https://github.com/ScarlettSun9)) 整理_

_Leo([LeoTsui](https://github.com/LeoTsui))、 M、 Jenny Z([Meijuan Zeng](https://github.com/tomato018))、 stronger、 刀刀参与讨论，对本文亦有贡献_

* 翻译原则
    * 【翻译原则零】信达雅
    * 【翻译原则一】严禁盲翻
    * 【翻译原则二】全文理解
    * 【翻译原则三】简练准确
    * 【翻译原则四】避免翻译腔
    * 【翻译原则五】灵活变通
    * 【翻译原则六】注意专业术语
    * 【翻译原则七】遵守格式
* 试译例句一
    * 短句一分析
    * 短句二分析
    * 短句三分析
    * 短句四分析
    * 试译例句一的参考译文
* 试译例句二

## 翻译原则

详细讲解见：[字幕翻译原则](https://github.com/athena-xcy/CS50-Study-Group/blob/master/translation-group/principles-of-subtitle-translation.md)。除此之外，可参考学习组翻译讨论分享文稿，结合具体的课程视频中的例句，更好理解翻译原则在实际翻译中的应用。

【翻译原则零】信达雅：力求准确，适度意译，润色表达

【翻译原则一】严禁盲翻：只有结合场景剧情才能翻译的准确出彩

【翻译原则二】全文理解：开展翻译工作前，应看完对应视频、文件

【翻译原则三】简练准确：译文单句不宜过长，观众需要一眼就能看懂中文字幕

【翻译原则四】避免翻译腔：说人话，说中国话

【翻译原则五】灵活变通：根据需要调整语序

【翻译原则六】注意专业术语：查找资料搞懂术语含义

* 可参考翻译组[术语表](https://github.com/athena-xcy/CS50-Study-Group/blob/master/translation-group/Glossary.md)和供查询的[计算机翻译字典](https://github.com/athena-xcy/CS50-Study-Group/blob/master/translation-group/cs-dictionary.textile)。

【翻译原则七】遵守格式：遵守字幕文件格式和翻译格式

## 试译例句一

> All right, so just to recap then, three tools to have in the proverbial toolbox

> now are help50 anytime you see an error message that you don't understand, whether it's with make or Clang or, perhaps, something else.

> Printf-- when you've got a logical program -- a bug in your program, and it's just not working the way it's supposed to or the way the problem set tells you it should, 

> and then style50, when you want to make sure that, does my code look right in terms of style, and is it as readable as possible?

### 短句一分析

> All right, so just to recap then, three tools to have in the proverbial toolbox

句中主语被省略了，更好的翻译方式是把主语回避掉 而不是自己填上主语。
类似这样：

> 好，那么回顾一下

原文没有主语，在不影响理解的情况下，就不需要加。如果原文是代词，如果指代较远，那尽量重现一下具体指代。

在下半句

> three tools to have in the proverbial toolbox

其中，proverbial toolbox这里翻译的五花八门。试译答案里的几种译法有: 
> 1.“谚语的工具箱”

> 2.“众所周知的工具箱”

> 3.“常见的工具箱”

第一种可能是来自机器翻译或者没有联系上下文，不太可取。大多数人翻译成了 “众所周知”。“众所周知”虽然是proverbial最准确的中文释义，但是代到文中和“工具箱”搭配就很怪，中文一般不会这么说。在没有很好的直译的情况下 “常见工具”这个翻译比较直白，信息量也很充分。还有另外一个译本，“熟知的工具”，也是通顺易懂。所以对于这半句来讲，最佳翻译版本是“在大家熟知的工具箱中有三个工具”。

当然，“工具箱”在这个语境下不好理解，所以翻译成“常见工具”也可以。由于教授个人语言习惯很官方正式，所以还是官方文件的翻译风格比较贴这门课程的翻译。

综上所述，在翻译时还是要符合翻译原则，结合语境，尽量直译，适度意译。

### 短句二分析

> now are help50 anytime you see an error message that you don't understand, whether it's with make or Clang or, perhaps, something else.

首先是开头这个now, 它连着短句一的 `three tools`，是说我们现在总共有三个了，“加起来现在有” 的意思。

然后从整句结构来看，接下来该分别讲三个工具。这里可以适当意译，加上“第一”“第二”“第三”，让语句更连贯。如果看视频翻译的话，教授在屏幕上有列出这三个工具，所以“【翻译原则一】不盲翻”是很重要的。

当然没加的话 只要把这句话翻译通顺也可以。句意准确最重要，然后尽量直译，可以考虑意译来 “雅”。 

后半句

> whether it's with make or Clang or, perhaps, something else.

这里涉及到一点专业知识，有关cs50 sandbox中的编译方式。在CS50 sandbox中 make+文件名是编译，Clang也是一种编译工具，所以以此类推，这里的 “something else”可以按照“适量意译”“让句子更加通顺”的原则来讲。

好多翻译译本写的是“无论是用 make，clang，还是其他编译的”，把something else补充引申了一下，这是完全可以的，而且更有助于理解。

### 短句三分析

> Printf-- when you've got a logical program -- a bug in your program, and it's just not working the way it's supposed to or the way the problem set tells you it should,

从整体上看，这半句破折号后面的三个短句有着递进关系。用简单并列来翻译，不符合计算机的逻辑。“先报错，不报错再查运行结果，最后再查代码风格”，整体上是类似这样的一种递进关系。

这句中第一个要注意的细节是

> logical program

这里有两种争议：一种是认为这个是David的口误，因为在视频中有着明显的停顿和表情语气，而且这个说法确实不太符合日常的说话讲解习惯，所以这么理解是可以的，可能是想说 logical problem 但是口误了。在译本中，可以跳过 logical 直接翻译成程序中有bug；另外还有一种翻译版本，是说“逻辑上有问题的程序”，也就是说，虽然没有报错，但是没有跑出来我们想要的结果，这样也可以解释得通。

第二个细节是

> problem set

这个是作业集的意思。

### 短句四分析

> and then style50, when you want to make sure that, does my code look right in terms of style, and is it as readable as possible?

这个是第三个工具。从句子结构上看，这个是两个从句组成的，这两个从句相互之间可保持并列关系。

这里细节上

> code style

翻译成代码风格比较流畅; 而国内老师用“代码格式”较多，也可以这样翻译。

> as readable as possible

翻译成“是否尽可能可读”比较流畅。readable 是计算机里的概念，意为可读性，就是自己写的代码，别人能看懂。有些程序虽然在计算机那里执行都是一样的，但是别的程序员很难看懂。这就不利于程序员之间合作和未来代码的维护。

这个短句一个较好的译本为：

> 当你想要确保你的代码风格良好 
并且具备极高可读性

### 试译例句一的参考译文

> 好，我们现在来复习一下，常用工具箱里的三种工具：1. help50, 用于你不理解的错误讯息，可以是Make,Clang或其他编译器产生的；2. Printf，用于处理程序中出现bug、程序无法正常运行时；3. Style50，用于确保所写代码是否风格一致以及是否可读。
