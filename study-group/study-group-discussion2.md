# L1 翻译经验分享

_郝亚南 Cris([Cr1s1](https://www.github.com/Cr1s1)) 主讲_

_郝亚南 Cris 供稿_

_Leo([LeoTsui](https://www.github.com/LeoTsui))整理_

_精灵兔、Yuehua Veronica 和 AthenaX([athena-xcy](https://github.com/athena-xcy))参与讨论，对本文亦有贡献_

- [例句讨论](#%e4%be%8b%e5%8f%a5%e8%ae%a8%e8%ae%ba)
  - [L0 1:01:45 复制粘贴](#l0-10145-%e5%a4%8d%e5%88%b6%e7%b2%98%e8%b4%b4)
  - [L0 01:04:16 硬编码](#l0-010416-%e7%a1%ac%e7%bc%96%e7%a0%81)
  - [L1 1:16:19 恼人的浮点数](#l1-11619-%e6%81%bc%e4%ba%ba%e7%9a%84%e6%b5%ae%e7%82%b9%e6%95%b0)
- [参考译文](#%e5%8f%82%e8%80%83%e8%af%91%e6%96%87)

## 例句讨论

### L0 1:01:45 复制粘贴

I'm going to go ahead and copy paste, as I did before. This is one of those do as I say, not as I do... to implement this program here.

`do as I say, not as I do` 依我所言，勿仿我行。在本语境中，教授在告诫学生不要复制粘贴代码，这并不符合代码复用的原则。

### L0 01:04:16 硬编码

So now, I can actually move this repeat block into cough itself, but rather than hard code 3, notice this.

`hard code` 硬编码，在本语境中，教授的意思就是他的**代码**和**数据**没有分离。

### L1 1:16:19 恼人的浮点数

We've only seen thus far how to get a string, but you can get integers and characters and funky things, like floats and doubles which actually open a can of worms as to problems that can happen in a computer.

`funky` 本意是（气味）恶心的。现在常见到的引申义是“古怪的”、“时髦的”，比如 funk art、funk music。`funk` `n.` 一词的本意指抑郁、消沉、恶臭的气味。在本语境中，教授所指的是浮点数处理起来很麻烦。软件工程中也有 “this code smell...” 的说法。

> In computer programming, a code smell is any characteristic in the source code of a program that possibly indicates a deeper problem.

`open a can of worms` 英文俗语，自找麻烦。

## 参考译文

我们目前只看到了如何取字符串,但是你可以取整数、字符和其他讨厌的东西,像是 单精度浮点数和双精度浮点数，这种用在在计算机里解决问题时，实际会自找麻烦的东西。

然后我接着会像之前那样复制粘贴。这属于一种我真这样说，但不该真这样做的方法...去在此实现这段程序。
