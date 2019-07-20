# 字幕翻译教程 v3.0

翻译计划：[字幕译者招募帖](https://www.douban.com/group/topic/144969173/)

最新更新：07/20/2019

## 翻译原则
**严禁盲翻**：只有结合场景剧情才能翻译的准确出彩。
> 反例：即不看视频直接拿文本翻译。  

**全文理解**：翻译之前要完整看一遍视频，结合上下文才能理解透。  

**简练准确**：和文稿翻译不同，观众需要一眼就能看懂中文字幕。  
> 反例：有些翻译要回过头看三四遍甚至读出声才理得清意思，这就不算是成功的字幕，毕竟字幕也就出现一秒。  

**翻译腔**：当觉得一话别扭的时候，就自己读出来，想想自己平时会不会这么说。  
> 反例：教授讲话还是比较轻松的，~~“老伙计”~~ 这样的翻译不要出现哈。  

**灵活变通**：由于每条字幕的长度限制，很多长句都会被断开分成多条字幕。所以，有时不该一字一句对照翻译，而是需要改变一下语序。  
> 说明：此处改动仅指中文字幕，英文字幕请一定保持原样。  

**专业术语**：勤查字典材料很重要，找不到随时讨论。  
> 反例：~~严禁机翻~~。应该先查找英文翻译，理解之后，再找相应的中文翻译。慎用英中网络字典，较为推荐的有 bing 和有道。  

**遵守格式**：翻译格式见下文，翻译中请 **不要改动英文字幕及时间轴** 。有任何疑问，标注出来即可。  
 
## 翻译软件 Aegisub
[软件下载](http://www.aegisub.org/)

[软件说明](http://docs.aegisub.org/3.2/Main_Page/)

#### 软件界面

#### 文件格式
字幕文件格式为 srt。先确认字幕文件的编码是unicode，然后用ae打开后，点击【文件】再【配置】按照设置。

srt 文件也可以用记事本, Notepad++, Sublime Text 等其他文本编辑器打开。

#### 文本格式
第一行为字幕条序号，第二行为时间轴，第三行为中文翻译，第四行为英文翻译。

黄色方框的时间轴部分请勿改动。如有需要改动的断句，标注出来即可，后期校对会修改。红色方框中，把中文字幕四个字替换为中文翻译即可。

> 举例：  
> 1  
> 00:00:50,190 --> 00:00:53,565  
> [中文字幕]  
> This is CS50   

#### 文本导出
在 ae 里选择【导出】再【存储】成 srt 文件，文件命名格式：Lecture[i]part[j]-[译者姓名]。
> 比如 Lecture0part1-莉莉安。

## 翻译指南

#### 翻译内容
-	字幕中若出现旁白/解释/说明的部分不用翻译，应直接删掉；如果此行只有这种说明性文字，则连带整个时间轴全部删掉。
> 比如：[Applause]，完全可以删除。  
> 再比如：英文字幕中偶尔会有 David: xxxx，这种情况下 David: 也可以删除。  

-	对话类：不同两人的对白开头都要加英文半角的短横 “–” 引导，后一句和前一句对白内容之间为 2 个空格。
> 比如：-你吃了吗  -我吃了  
> 译为：-AAAAA  -BBBBB

#### 翻译格式
**标点符号**
-	逗号句号：以一个空格代替。
-	英文半角下引号： ”” 仅用在引用或说话处，从英文字幕中直接复制。
-	音乐符号： ♪ 歌词 ♪ 音乐符号直接从英文字幕中直接复制。
-	省略号： ... 这三个点中文字幕中务必保留。
- 感叹号问号：/* TODO */

**数字**
- 统一用阿拉伯数字，字幕追求一目了然。
> 反例如，Week 0 应译成 “第 0 周”，而不是 ~~“第零周”~~。

 
## 常见问题 

##### 问: 教授在课上讲软件界面上的按钮保留英文可以么？
答：可以。
##### 问：[Meow] 此处中文也要加方括号么？
答：不用。
##### 问：中文字幕和英文字幕是上下排版，还是左右排版？
答1：用记事本的话，请手动换行，用 ae 的，在中文字幕后加上 \N 就行，不要空格。这个情况大概是合轴的时候软件把代码去掉了，麻烦手动换下行吧。  
答2：如果后期确实发现需要大量调整排版的话，我们可以用字符串处理程序去调整。
##### 问：Mac 上可以在 ae 中先进行翻译操作，再保存修改，不需要导出。这样可以么？
答：这是来自 Mac 的自动保存功能，这个做法容易造成数据丢失，不够安全，建议大家还是选择 ae 中的导出功能。



