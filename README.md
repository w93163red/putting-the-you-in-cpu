<picture>
  <source media='(prefers-color-scheme: dark)' srcset='./public/github-images/banner-dark.png'>
  <img src='./public/github-images/banner-light.png' alt=''>
</picture>

<h1 align='center'>Putting the "You" in CPU</h1>
<p align='center'>A technical explainer of how your computer runs programs, from start to finish.</p>
<p align='center'>by <a href='https://github.com/kognise'>@kognise</a> and <a href='https://github.com/hackclub'>@hackclub</a></p>
<br>

## 已将正文进行中文翻译

## 引子

我在计算机领域做过[许多事情](https://github.com/kognise),但我的知识中一直存在一个空白:当你在电脑上运行一个程序时,究竟发生了什么?我思考这个问题时发现 - 我掌握了大部分必要的底层知识,但难以将所有碎片拼凑起来。程序真的是直接在CPU上执行的吗,还是另有玄机?我使用过系统调用,但它们究竟是如何*工作*的?它们本质上是什么?多个程序是如何同时运行的?

<img src='/images/writing-this-article.png' loading='eager' style='margin: 40px 0;' alt='A scrawled digital drawing. Someone with long hair is confused as they peer down at a computer ingesting binary. Suddenly, they have an idea! They start researching on a desktop computer with bad posture.' width='1708' height='536' />

我终于忍不住开始尽可能地弄清楚这些问题。如果你不上大学,就很难找到全面的系统资源,所以我不得不翻阅大量质量参差不齐、有时甚至相互矛盾的资料。经过几周的研究和近40页笔记后,我认为我对计算机从启动到程序执行的工作原理有了更深入的理解。如果当时有一篇扼要解释我所学内容的文章就好了,所以我决定写下这篇我曾渴望拥有的文章。

你知道人们常说的那句话吗..."只有当你能向别人解释清楚时,你才是真正理解了某样东西。"

> 赶时间?觉得自己已经了解这些内容了?
>
> [阅读第三章](/how-to-run-a-program),我保证你会学到新东西。除非你是 Linus Torvalds 本人。

<br>

<p align='center'><a href='https://cpu.land/the-basics'><strong>Continue to Chapter 1: The "Basics" &raquo;</strong><br>(cpu.land)</a></p>
