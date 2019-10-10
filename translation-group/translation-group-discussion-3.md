# CS50学习组L3翻译经验分享

_Scarlett([ScarlettSun9](https://github.com/ScarlettSun9) 主讲_

_Scarlett 供稿_

_Leo([LeoTsui](https://www.github.com/LeoTsui))整理_

_Leo 参与讨论，对本文亦有贡献_

# 专有名词翻译

## 例（garbage value）

> 2101
01:39:29,450 --> 01:39:31,950
中文翻译
It's just because it can't be trusted, it's a garbage value.

> 2102
01:39:31,950 --> 01:39:35,760
中文翻译
If you just give yourself a temporary value, who knows what's in there?

> 2103
01:39:35,760 --> 01:39:38,250
中文翻译
We got lucky and Tara did not have anything in this cup,

> 2104
01:39:38,250 --> 01:39:41,370
中文翻译
but it could have had a garbage value, maybe it had some Pepsi,


* 第一句
Garbage value 作为专有名词，在这里中出现的时候一般都是严格地按照其中文释义来翻。我不是计算机专业的，所以一开始翻的是“无效值”，不敢相信它就叫“垃圾值”。。。
这里再次附上两个链接：[CS50术语表](https://github.com/athena-xcy/CS50-Study-Group/blob/master/translation-group/Glossary.md)和[计算机中英词典](https://github.com/athena-xcy/CS50-Study-Group/blob/master/translation-group/cs-dictionary.textile)。我们自己的术语表目前还极为简洁，计算机中英词典更全一些，但是还是有很多查不到。
关于专有名词翻译，李总给的建议是*机翻 + 人翻*。
当然还可以直接搜索不同的表达，看它们的结果有多少。比如这里的“无效值”和“垃圾值”。当然这种办法不一定准确。
（嗯其实最好的办法是自己拿本中文书学一遍）
* 第四句
这里的 garbage value 可以结合语境来翻译一下。这里是说课堂上的那个杯子是空的，可以倒牛奶橙汁，但它也许一开始里面有东西，比如有百事可乐。
因为要强调杯子/变量的最初状态，所以我们这里翻译成“初始值”更合适。
* 参考译文
> 因为这是个垃圾值 不要当真
如果你有一个临时变量 没人知道里面存了什么
我们很幸运 Tara的杯子里什么都没有
但它可能是有初始值的 比如杯子一开始有百事可乐

# 处理混乱与重复的语言

## 例一(因为个人原因表述重复)
> 2190
01:44:07,580 --> 01:44:10,670
...
And go ahead and store 1 in tmp.

> 2191
01:44:10,670 --> 01:44:13,490
...
Go ahead and go to that address and put whatever's

> 2192
01:44:13,490 --> 01:44:17,300
...
at b's address-- so get that address and put it over-- get that address,

> 2193
01:44:17,300 --> 01:44:20,840
...
get the value, and put it over at that address by dereferencing.

> 2194
01:44:20,840 --> 01:44:26,310
...
And then lastly, go to b in memory, like over there, put the tmp value there.

* 我们先来看一个broken version

> 接着 把1存到tmp里
再继续 到这里 把b处的都...
就是到这个地址处 把它的值放到...
就是到这个地址处 得到它的值 再通过解引用 把它放到这个地址处
然后最后 找到内存的b的地址 比如在这 把tmp的值放到这里

* 这样翻译属于纯粹的直译。没有错误，但是，考虑到学习者的话，这种翻译就非常尴尬了，而且很容易把人绕进去，各个地址也都之指代不明。

* 这里教授想表达的意思很简单，就是找地址、取值、把值放到另一个地址这样的过程。由于表述比较长，我们可以按照教授的原意，来参照他的用词给出自己的翻译版本。也就是说，我们在这里要给学习者解释清楚整个过程。

* 给出参考译文

> 接着 把1存到tmp里
再继续 到这个地址标记的地方
不管b表示的地址是哪 获取b表示的地址
按地址取值 把值传递到a表示的地址处
最后 走到b表示的内存地址 比如这里 把tmp的值放到这里

* 当然，这样子直接意译一般还是针对于比较长的文本，如果原文中只说了一两句然后立马 I'm sorry 改正过来的话，还是可以直译的。重点要关注学习者的感受。

## 例二（重复词语、短语）

> 126
02:01:07,822 --> 02:01:08,940
...
Now, let's do the right half.

> 127
02:01:08,940 --> 02:01:11,790
...
Again, we started by taking the whole problem, doing the left half,

> 128
02:01:11,790 --> 02:01:14,890
...
the left half of the left half, the left half of the left half of the left half.

> 129
02:01:14,890 --> 02:01:17,300
...
And now we're going back in time, if you will.

> 130
02:01:17,300 --> 02:01:20,733
...
So let's divide this into two halves, now the left half into two

> 131
02:01:20,730 --> 02:01:21,380
...
halves still.

* （此例有毒
* 这个例子来自L2中教授用8个数字在频幕上演示如何排序那一部分。其实如果不看字幕，纯粹听教授讲还有他不停地比划也能弄明白。但是这里的三层left half就很不友好了。
* 因为这里的不同的half是有层次的，第一个left half是一个4个值的列表，第二个是2个，第三个是1个。在翻译中我们也要尽量体现其中的层次关系。
* 这里的不同的half可以翻译成“半部分”、“半边”、“一半”、“边”等等，但要注意同一层次上的用同一类，或者说这里同一大小的列表用同一类。
* 参考译文

> 我们来排列右半部分
我们在处理整个问题时 先排列左半部分
然后是左半部分的左半边 然后是左半部分的左半边的左边
现在 如果可以 我们倒回去
我们把这一部分也分成两块 这是它的左半边
再分一次

## 例三（也许是口误）

> 2102
01:39:31,950 --> 01:39:35,760
...
If you just give yourself a temporary value, who knows what's in there?

* 这句是我们第一个例子里面的，还是和变量赋值有关。
* 很明显这个地方教授说的temporary value不太合适，我感觉应该是 temporary variable。
* 所以这句话翻译的时候我们还是译成`临时变量`
* 参考译文：

> 如果你有一个临时变量 没人知道里面存了什么
