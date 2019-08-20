# CS50 学习组第3次分享讨论

_Elvarez 主讲_

_Elvarez 供稿_

_精灵兔 整理_

_blue hydrangea、 Leo([LeoTsui](https://www.github.com/LeoTsui)) 和 AthenaX([athena-xcy](https://github.com/athena-xcy))参与讨论，对本文亦有贡献_

## 代词还原

由于字幕的短时性，还原指代内容会对学习者的理解有很大的帮助

### 例一（代词指代）

<pre><code><div>486
00:22:32,490 --> 00:22:35,369
就像小时候大家玩过的那种<nobr style="color:red;">动画书</nobr>
It's like as a kid, if you ever had one of those <nobr style="color:red;">paper flip books</nobr>

487
00:22:35,370 --> 00:22:37,042
一本<nobr style="color:red;">书</nobr>就是一叠图画
where there's tons of drawings in <nobr style="color:red;">them</nobr>,
</div></code></pre>

在上例中，them 被译为“一本书”

### 例二（代词指代）

<pre><code><div>72
00:43:37,230 --&gt; 00:43:40,400
也就是说 在<nobr style="color:red;">这个循环</nobr>第1次迭代时
So what this effectively means is on the first iteration of the <nobr style="color:red;">loop</nobr>, when

73
00:43:40,403 --&gt; 00:43:44,427
i等于0 就像这样
i equals 0, this looks like this, effectively.

74
00:43:44,427 --&gt; 00:43:48,431
再次迭代时i等于1 就变成了这样
When i then becomes 1 on the next iteration, then you're doing this.

75
00:43:48,434 --&gt; 00:43:51,982
最后一次迭代时 i等于2 就是这样
When i becomes 2 on the final iteration, it looks like this.

76
00:43:51,982 --&gt; 00:43:55,269
而当i等于3时 由于3不小于3
When i becomes 3, well, 3 is not less than 3,

77
00:43:55,266 --&gt; 00:43:57,328
<nobr style="color:red;">这个循环</nobr>就停止执行了
and so <nobr style="color:red;">it</nobr> doesn't execute again.
</div></code></pre>

上例中，某个循环（loop）第一次出现是在 72 行，然后教授进行了一连串的说明，直到第 77 行才再次出现代词 it，这时为了表意更清晰，译为“这个循环”

### 例三（从句指代）

```
461
00:21:20,601 --> 00:21:23,404
如果我继续拉近 最终你能看到的
And if I go an even further, you can actually see

462
00:21:23,405 --> 00:21:25,835
就是组成这个表情的像素小方块
the tiny little squares that compose this image,

463
00:21:25,836 --> 00:21:28,395
在这个范围中 大部分像素点都是黄色的
most of which at the zoom level are yellow,
```

上例中 which 指代的是像素小方块（the tiny little squares），故 most of which 译为“大部分像素点”

长的定语从句在翻译时，经常在中文中被分成两句，和英文的习惯不同，中文习惯在名词前放过长的修饰，而英文会分成两句，用代词来指代重复的名词

### 例四（代词还原）

```
81
01:35:02,410 --> 01:35:06,160
简单来说 在科学或金融
So long story short, any time you have scientific or financial

82
01:35:06,160 --> 01:35:10,270
还有其他涉及大量数据的领域
or any sort of large data sets that involve big numbers and lots of them

83
01:35:10,270 --> 01:35:12,640
时间一长 精确度不足就会暴露出问题
and lots of time, this is a problem.
```

语境是在这几句之前教授举了火箭和金融领域的例子，花了比较长的篇幅解释计算机的精确度在实践中的重要性，81-83 句属于总结部分，这部分的核心问题“精确度不足”需要还原出来


1. 【补充解释】

简单来说就是把字幕中没讲出来但教授实际有传达的意思翻出来，在合理范围内进行补充，包括手势、时间、空间等，便于观众理解。
例一：
40 01:33:10,990 --> 01:33:13,660 要不是我刚才一时好奇 嫌小数点后7位不够精确 I mean, we would never have known this if I hadn't gotten greedy
41 01:33:13,660 --> 01:33:18,570 求出了后50位数 也不会知道后面的数字不全是0 and looked at 50 decimal places instead of 7, which was already pretty precise.
这里讲的是2/10并不正好等于0.2，随着小数点后位数的增多，2/10实际上会稍大于0.2，“后面的数字不全是0”就是结合教授的演示对“this”的解释。在视频里这个部分就是 显示屏上有0.20000000XXXX 一连串0之后在XXX的位置出现了非0的数
例二：
61 01:43:29,080 --> 01:43:33,610 大家注意 我之前的代码都是这么排版的 And notice stylistically, I've been doing this instinctively for some time.
62 01:43:33,610 --> 01:43:36,760 适当缩进 读起来会更加方便 Everything's nicely indented just to make it more readable,
63 01:43:36,760 --> 01:43:39,760 就跟Scratch里的功能块差不多 虽然排版上的留空 quite like the Scratch blocks, even though again a lot of white space
这个也是结合了教授在显示屏上演示的界面，把“white space（空白，留白）”补充解释为了“排版上的留空”。

3. 【反译】

由于中英文用词/表达习惯不同，有时候直译就会显得翻译腔很重，所以在处理的时候可以考虑“正话反说”“反话正说”，让字幕看起来更符合中文的表达习惯。
例一：
127 01:37:06,410 --> 01:37:09,030 计算机科学离不开权衡利弊 and computer science more generally there's always a trade-off.
128 01:37:09,030 --> 01:37:13,160 使用双精度浮点数 在精确度上的确更占优势 And yes, if you use a double, you will avoid this problem a bit more,
129 01:37:13,160 --> 01:37:15,880但代价是什么呢 but what price will you pay, so to speak?
“you will avoid this problem a bit more”直译为“你就能更好地避免这个问题”多少会有点别扭，此处“避免问题”反译成了“占优势”。
例二：
3 01:40:40,080 --> 01:40:42,350 有时你需要的不是一整段 一整句 If you don't want a whole string, like a whole word
4 01:40:42,350 --> 01:40:45,320 也不是一个完整词 而只是一个字母 or a paragraph or sentence or whatever, you just want one character.
5 01:40:45,320 --> 01:40:48,230 这时字符类型就派上用场了 You can actually use what's called a char or character.
上例中“don't want”翻成“你并不想要…”感觉也并不那么通顺，此处结合上下两行，把否定后移，“不想要”反译成“需要”。
例三：
65 01:43:41,750 --> 01:43:43,840 我先试运行看看 So if I go ahead and run this-
66 01:43:43,840 --> 01:43:46,150 有点看不见我把终端窗口拉上来 let me pull up the terminal window so I can see it.
上例中“so I can see it”略过不合适，翻成“这样我就看得见了”也不合适，索性正话反说
*常见的可能就是 否定词/表示否定意思的词
