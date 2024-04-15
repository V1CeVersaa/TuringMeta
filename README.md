# Turing Meta

> 图灵人都要掌握的计算机知识与技能

## 为什么会有这个仓库

当今大学计算机专业课程体系中，往往缺乏对计算机技能的培养，这引起的问题不仅体现在互评与合作中，当学生尝试进行一些实际的项目时，往往处处碰壁。更进一步来说，你是否也发现过这样的问题：

- 几乎没有深入了解过像 Make 与 CMake 的自动化构建工具，只会敲一个 `make` 命令；
- 对 Git 的使用仅限于 `git add`、`git commit` 与 `git push`，上 Github 只会点点点；
- 排版不规范不优雅，对 Markdown 与 LaTeX 的使用仅限于简单的文本编辑（不会有人还在用 Word 吧）；
- Windows 就是我的妈，对 Linux 的使用仅限于 `ls`、`cd` 与 `rm`，勉勉强强配置环境变量与安装软件，更不用提编译内核与配置网络了；
- C 和 C++ 是我会的最好的语言，别的语言？不了解。

尽管 MIT 与 UCB 分别推出了著名的 Missing-Semester 与 Sysadmin Decal 等课程，但是也仅仅解决了一部分问题，并且课程设计也不一定完全符合图灵宝宝的体质。所以我们决定推出 Turing Meta 系列课程，从基础知识到进阶技能，高屋建瓴构建计算机知识技能体系。

<!-- Meta，取元意 -->

## 文档结构

```
├─ README.md
├─ schedule.md          ＃ 课程安排
├─ resource             ＃ 相关资源
│   ├─ ...  
└─ series               ＃ 存储课件与讲义
    ├─ exampleLecture   ＃ 课程示例
    │   ├─ handout.pdf
    │   ├─ slides.pdf
    │   └─ supplement
    └─ ...   
```