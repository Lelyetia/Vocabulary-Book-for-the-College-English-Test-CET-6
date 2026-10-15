# 六级词汇关系记忆宝典

**让 AI 成为新一代的学习搭子：一本由 GPT-Astra 按个人需求生成的单词书。**

已有一定词汇量，下一步就要把词之间的关系用起来：看清形近词的区别，辨明近义词的用法，在写作和翻译时准确调出需要的表达。本书围绕这条复习路径，将六级词汇组织成“形近辨认”和“近义辨析”两部分，以 LaTeX 排版，提供可直接阅读、检索和打印的 PDF。

**[下载完整 PDF](https://github.com/Lelyetia/Vocabulary-Book-for-the-College-English-Test-CET-6/raw/refs/heads/main/CET6_Final.pdf)** · [在线预览](CET6_Final.pdf) · [制作与学习原理](docs/METHOD.md) · [完整社交推文](docs/SOCIAL_POST.md) · [精简推文](docs/SOCIAL_SHORT.md)

## 一本书，两条复习路径

| 内容 | 本书安排 | 用来解决什么问题 |
| --- | --- | --- |
| 形近辨认 | 114 组核心辨析，配合词族、拼写变体、相似拼写训练和独立词形查漏 | 看准单词，分清词性，减少拼写混淆 |
| 语义辨析 | 227 组核心义项与用法，标明近义、相关和对照关系 | 结合义项、搭配和语境选择表达 |
| 全词语义地图 | 81 个主题 | 按主题查漏，积累写作与翻译素材 |
| A–Z 索引 | 每个收录形式均可定位词形页与词义页，电子版页码可点击 | 从一道题或一个生词进入整组复习 |

成书 **400 页**，收录 **8,013 个去重后的词汇形式**，口径包含基础词、六级标星词、派生形式、短语和显式拼写变体。词表范围依据教育部教育考试院公开的[《全国大学英语四、六级考试大纲（2016 年修订版）》](https://cet.neea.cn/res/Home/1704/55b02330ac17274664f06d9d3db8249d.pdf)；具体展开和计数见书前“范围、依据与完整性”。2026 年 10 月 15 日核对时，官网[考试大纲目录](https://cet.neea.cn/html1/folder/16113/1588-1.htm)仍列出该英语版本。

## 为什么这样背

我的需求很明确：让单词之间形成可供回忆和使用的联系。`adapt / adopt / adept` 放在一起看拼写；`increase / expand / enhance` 放到具体搭配里辨用法；遇到写作主题，再沿语义地图组织表达。

词嵌入提供了这一设计的启发：语言模型能从语料中学习词的向量表示，用空间关系刻画部分语义和句法关系。本书把这个启发转化为复习材料的组织方式——**用关系导航，用差异辨析，用回忆检验掌握。** [词向量研究](https://arxiv.org/abs/1301.3781)

练习的重点是主动提取。外语词汇实验发现，学会后继续进行检索练习能改善延迟回忆。因此，每次复习都先遮住答案，尝试回忆，再核对并纠正。 [检索练习研究](https://doi.org/10.1126/science.1152408)

## 每次复习的三个动作

1. **回忆**：遮住释义，说出词义；再遮住英文，根据中文或语境写出单词。
2. **辨析**：选一组易混词，说清拼写、义项或搭配上的关键差别。初次接触的生词先逐个建立词形和词义联系，熟悉后再集中比较。
3. **输出**：选两个词各写一句话，标记错误，在后续复习中优先重测。可从次日、一周后、一个月后开始安排回访，按自己的回忆表现调整。

例如：

> We need to **expand access to education** and **enhance the quality of teaching**.
>
> `expand` 突出范围的扩大；`enhance` 突出质量的提升。

## AI 在这里做什么

本项目由 Lelyetia 提出学习目标与组织要求，GPT-Astra 按这些需求生成、整理和修订内容，并借助词表、词典、检索与排版工具形成成书。

书内记录的前期语义候选检索使用 **BAAI/bge-small-en-v1.5 的 384 维向量**，最终正文围绕明确的义项、差异和搭配组织。模型负责把材料加工成可读的关系笔记，学习者通过回忆、辨析和使用把它变成自己的表达。详细方法见 [METHOD.md](docs/METHOD.md)。

## 文件与分享

| 文件 | 用途 |
| --- | --- |
| [CET6_Final.pdf](CET6_Final.pdf) | 完整单词书，PDF 为本次成书分发格式 |
| [docs/METHOD.md](docs/METHOD.md) | 设计原理与复习方法 |
| [docs/SOURCES.md](docs/SOURCES.md) | 词表、词典、模型、研究和署名 |
| [docs/SOCIAL_POST.md](docs/SOCIAL_POST.md) | 公众号、长文平台推文 |
| [docs/SOCIAL_SHORT.md](docs/SOCIAL_SHORT.md) | 小红书等平台精简推文 |
| [SHA256SUMS](SHA256SUMS) | PDF 文件校验值 |

欢迎通过 [Issues](https://github.com/Lelyetia/Vocabulary-Book-for-the-College-English-Test-CET-6/issues) 提交具体词条的修订建议，附上页码、词组和建议写法，方便后续版本更新。

PDF 中采用 CETVocabulary 的数据改编部分按 **CC BY-NC-SA 4.0** 分享；下载、转发和改编时请保留书内署名与来源，遵循相应许可。[PDF 许可说明](LICENSE-PDF.md) · [第三方来源](docs/SOURCES.md)。仓库原有 [MIT LICENSE](LICENSE) 的适用范围详见该说明。
