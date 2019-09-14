# Week 2 Walkthrough

## 第一步 找到作业

* 在 [edX Week 2](https://courses.edx.org/courses/course-v1:HarvardX+CS50+X/courseware/6f10d1f2fb0548ada175ba2ed508f50c/ad2ce21f33474bed96e87005fe3eba6d/1?activate_block_id=block-v1%3AHarvardX%2BCS50%2BX%2Btype%40vertical%2Bblock%4059c51356dbad4659bc36e061211313e7) 页面点击[Problem Set 2](https://docs.cs50.net/2019/x/psets/2/index.html)


## 第二步 做作业

* 建议阅读 [Lecture 2 相关内容](https://cs50.harvard.edu/college/2018/fall/weeks/2/) (本课有笔记、排序的视频，问题不能从这里登入)

* 任意做两个即可，不一定必须要做那个比较难的_Crack_

### Caesar

* More background in [Caesar Cipher](http://practicalcryptography.com/ciphers/caesar-cipher/)

* 注意设置大小写的上下限
	* 可以直接用字母转为数字，不必刻意背记ASCII表

* 善用Week 1的 %

### Vigenère

* More background in [Vigenère Cipher](https://en.wikipedia.org/wiki/Vigenère_cipher)

* 注意事项与Caesar同

* 注意，加密的那个字符串，要记得跳过标点符号和空格等不加密的位置，

### Crack

* 这个题确实是难度更高的阅读理解。大意就是暴力破解加密的信息内容。

* man crypt中的解释了encrypt()的具体操作。(By Leo: 可以直接Google)

* 用这个sandbox看man crypt那个文档有点费劲，可以在Mac terminal上输入man crypt看。 大致关键信息如下：
	*char *crypt(const char *key, const char *salt)*
		* 需要注意 这里的key的语义和前两题中的key不同。我理解，salt更像前两题的key。
	* 介绍了两种crypt，根据长度<=5可以得知，我们看Traditional crypt就可以了。由此可得：
		* “The salt is a 2-character array of the ASCII-encoded salt.”
	* 继续往下看Algorithm, 她的意思就是，一个字符串，头两个字母是salt。 

* 注意salt其实要用三个byte，因为要用'\0'结尾

* 一位一位对比char[]其实很麻烦，善用memcpy()  (需要#include <string.h>)

* C里面求一个array的长度比较麻烦，要用sizeof 整个数组/sizeof 数组第0位

* 一篇非常好的文章可供参考 [CS50 Week 1 Continued: Walkthroughs by Johnny](https://johnyzaguirre.com/2018/03/04/cs50-week-1-continued-walkthroughs/)



## 第三步 提交作业

可以通过提交作业后的报错信息，得到解决问题的方法
