# CS50 L4 L5 L7 翻译分享

_佛系闲鱼 主讲_

_佛系闲鱼、 blue hydrangea、 Leo 参与讨论_

_Leo([LeoTsui](https://www.github.com/LeoTsui))整理_

- [补充省略内容](#%e8%a1%a5%e5%85%85%e7%9c%81%e7%95%a5%e5%86%85%e5%ae%b9)
  - [用户体验](#%e7%94%a8%e6%88%b7%e4%bd%93%e9%aa%8c)
  - [有人知道吗](#%e6%9c%89%e4%ba%ba%e7%9f%a5%e9%81%93%e5%90%97)
  - [设计欠佳](#%e8%ae%be%e8%ae%a1%e6%ac%a0%e4%bd%b3)
- [用词习惯](#%e7%94%a8%e8%af%8d%e4%b9%a0%e6%83%af)
- [押头韵](#%e6%8a%bc%e5%a4%b4%e9%9f%b5)

## 补充省略内容

联系上下文、内容的补充和省略。比较常见的就是代词指代内容的补充和省略 比如it

### 用户体验

```
01:17:22,620 --> 01:17:26,210
所以我们需要询问 用户什么时候输入停止
So we do need to ask a question, when is the human done inputting.

01:17:26,210 --> 01:17:28,010
但这很难说
And it turns out-- and this is not obvious.

01:17:28,010 --> 01:17:31,310
直接询问也会影响用户体验
And it's not the best user experience on a keyboard for the human.
```

对于代词，一般代词离指代的内容相隔较远或者有指代不清的可能时会把代词翻译出来。最后一句中，把什么影响用户体验再重复一次比较好，因为前两句说的有点长，隔了一句观众可能会有点懵。

然后Not obvious 也不一定要直译过来“不是很明显”，放在视频里理解这句是说要判断用户停止输入是有些困难的，所以我翻成了比较口语一点的“很难说”

### 有人知道吗

```
01:50:32,410 --> 01:50:37,390
屏幕上这个数据结构里的这些数都具有一定特点
Notice here, there's something curious about all the numbers in this data structure.

01:50:38,800 --> 01:50:41,520
有人知道吗
What is noteworthy about them?

01:50:44,630 --> 01:50:45,430
有人知道吗
What is noteworthy?
```

这段字幕是讲树时教授让学生观察数据特点的几句话，noteworthy其实指的就是关注的数据特点，这句和前两句比较紧凑，如果再翻一遍“有人发现上图的数据特点了吗”就有点冗余了，所以noteworthy不一定要翻出来，翻成“有人注意到了吗”这个意思就足够了

### 设计欠佳

```
01:12:35,310 --> 01:12:38,340
在文件顶端中不断添加各种格式
Is it not bad design to just keep adding more stuff to the top

01:12:38,340 --> 01:12:40,410
不断把真正的程序内容推后
and pushing your actual content down and down and down

01:12:40,410 --> 01:12:42,090
甚至出现代码膨胀 这算不算设计欠佳
and just bloating the file?
```

第一句中 more stuff是上文说的添加的格式，这里翻译出来和上文连贯易于理解。

然后想插一句调整语序的问题 我把第一句的“is it not bad design...”进行了语序调整放到了后面，这样读起来比较通顺，不过会发现最后一句翻译比原文长了些一定程度上会影响观看，但我没想到怎么在不调整语序的基础上让原文更通顺，所以这里我就没再调整。

## 用词习惯

多想下平时说话的用词习惯，因为有的时候看到原文脑子会拧巴

```
Honestly, we could avoid this problem slightly…

```

如果翻成“我们可以稍微避免这个问题”，就slightly奇怪。不必，看到slightly就想把“稍微”的意思翻出来。其实可以想想平时的表达方法，比如翻成“其实我们多少能够避免这个问题”，就顺畅许多，而且和原文想表达的意思出入也不大。翻译为“试图避免”也可以。

## 押头韵

```
00:00:58,060 --> 00:01:02,340
这次 我们要挖掘Python潜力 实现强大目的
but this time using Python for even more powerful purposes,

00:01:02,340 --> 00:01:04,980
没想到我不经意间还压了个韵
an alliteration I didn't intend until I just said it there.
```
“alliteration”是头韵，英语中指在一句话中，对于相邻或相近的两个词，首字母或发首字母音相同，比如saints and sinners，还有这里的powerful purpose。

因为中文中头韵不常见，想直接翻译过来比较困难。为了照顾押韵，丢了一些信息。比如，more想表达在前几课的基础上再深入学习的意思就没了。
