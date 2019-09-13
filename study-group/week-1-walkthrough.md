# Week 0 Walkthrough

_Scarlett([ScarlettSun9](https://github.com/ScarlettSun9))、Leo([LeoTsui](https://www.github.com/LeoTsui)) 供稿_

_Leo 整理_

_AthenaX([athena-xcy](https://github.com/athena-xcy))参与讨论，对本文亦有贡献_

本周的作业题目详情在 [Problem Set 1](https://docs.cs50.net/2019/x/psets/1/index.html)，建议做作业之前看完课程视频，以及课程[Notes](https://cs50.harvard.edu/college/2018/fall/weeks/1/notes/)

## Hello

* 参考授课提供的示例，完善作业
* 建议参考 [CS50 Programmer's Manual](https://man.cs50.io/) 中列出的函数用法
    * `cs50.h` 的相关函数说明也在其中

## Mario

* 使用'do-while'循环的到期望的目标数据
* 使用'for'循环得到想要的输出结果
* 'less comfortable' 和 'more comfortable' 两个版本的作业内容差别不大
    * 建议先完成 'less comfortable' 版的作业，再稍作修改完成 'more comfortable' 版作业

## Cash and Credit

* 这两道题目都是对整除 '/' 和求余 '%' 运算的练习，注意这两种运算作用于整型数据时的得到的结果，并加以灵活运用

### Cash

* 参考作业 [Mario](#Mario) 得到期望输入数据
* 依照题目要求使用两种除法求出累计的硬币数量

### Credit

* 参考作业 [Mario](#Mario) 得到期望输入数据
    * 注意数据长度，并用适合的数据类型接受数据
* 这道题目要求繁琐，需要仔细读题，要考虑到所有的数据要求情况
* 参考思路
    * 获得数据的位数
    * 依照题目要求把数据相加，注意判断是按“数值”相加还是按“数字”相加
    * 依照题目要求判断数据并分类
        * 按需合理使用'&&'、'||'运算符
        * 判断要求如下
            * 上一步结果是否合规
            * 起始数值
            * 数据位数
