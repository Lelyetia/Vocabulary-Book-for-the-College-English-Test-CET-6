# 来源、署名与发布口径

## 成书与发布

- 书名：《六级词汇关系记忆宝典》。
- 项目发起与学习需求：Lelyetia。
- 内容生成与整理：GPT-Astra，结合下列公开资源与工具；LaTeX 排版。
- 发布版本：2026 年 10 月定稿，400 页。
- 发布文件：`CET6_Final.pdf`，3,065,385 字节。
- SHA-256：`2a1127600ee6693626ebc0f265ad2a8d973dd4cfba4c5c12ada01a6966461e6d`。
- 本次恢复来源：原 ChatGPT 对话“生成六级词汇笔记”所附最终 PDF。发布文件与恢复的附件字节一致。

## 词表和内容资源

| 资源 | 在书中的用途 | 来源与许可 |
| --- | --- | --- |
| 教育部教育考试院《全国大学英语四、六级考试大纲（2016 年修订版）》 | 词表范围、原表词族、显式变体与六级星号 | [官网目录](https://cet.neea.cn/html1/folder/16113/1588-1.htm)、[官方 PDF](https://cet.neea.cn/res/Home/1704/55b02330ac17274664f06d9d3db8249d.pdf)；来源权利归原权利人 |
| skywind3000/ECDICT | 中英文释义底稿，经摘要、筛选与修订 | [项目](https://github.com/skywind3000/ECDICT)、[MIT 许可原文](https://github.com/skywind3000/ECDICT/blob/master/LICENSE)，本仓库保留[许可副本](../licenses/ECDICT-MIT.txt) |
| exam-data/CETVocabulary | 5,278 条独立词表交叉检查及常用义短释参考，经修订、重排并补充辨析 | [项目与署名](https://github.com/exam-data/CETVocabulary)、[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) |
| BAAI/bge-small-en-v1.5 | 前期语义候选检索；书内记载使用 384 维表示 | [模型卡](https://huggingface.co/BAAI/bge-small-en-v1.5)，模型权重未随本仓库分发 |
| Princeton WordNet | 前期义项关系核验 | [项目官网](https://wordnet.princeton.edu/)，数据库未随本仓库分发 |
| Noto Serif CJK、Noto Sans CJK | 成书中文字体 | [Noto CJK](https://github.com/notofonts/noto-cjk)，SIL Open Font License |
| Latin Modern | 成书英文字体 | [CTAN 项目与许可](https://ctan.org/pkg/lm) |

以上工具流程和资源用途依据 PDF 末尾“方法、来源与复核”记录。本次为 PDF 成书发布，原始词表、字体文件、模型权重及 LaTeX 源文件由各自来源提供；此仓库交付成书与配套说明。

## 收录数字怎样理解

本书的 8,013 指合并重复拼写后的单词、短语和显式拼写形式，包含四级基础词、六级标星词及原表派生与变体。正文中的 114 指核心形近辨析组；227 指核心义项与用法组，涵盖近义、相关及对照；81 指全词语义主题。

书前说明同时保留了官方主词目数 5,418 与可见主词排版行 5,377 的两种口径，以及展开、归一与覆盖说明。引用统计时请连同其计数对象一起引用。

## 学习设计参考

1. Mikolov, T., Chen, K., Corrado, G., & Dean, J. (2013). [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/abs/1301.3781). 词向量与词汇关系的计算表示，为本项目的组织思路提供启发。
2. Karpicke, J. D., & Roediger, H. L., III. (2008). [The Critical Importance of Retrieval for Learning](https://doi.org/10.1126/science.1152408). *Science*, 319(5865), 966–968. 主动检索与外语词汇延迟回忆的实验依据。
3. Nakata, T., & Suzuki, Y. (2019; online 2018). [Effects of Massing and Spacing on the Learning of Semantically Related and Unrelated Words](https://doi.org/10.1017/S0272263118000219). *Studies in Second Language Acquisition*, 41(2), 287–311. 为分阶段辨析及间隔复习的设计提供参考。

## 分享时的署名建议

> 《六级词汇关系记忆宝典》，项目发起：Lelyetia；内容由 GPT-Astra 按需求生成、整理；词表依据教育部教育考试院公开大纲，释义参考 skywind3000/ECDICT 与 exam-data/CETVocabulary 并有修改。数据改编部分遵循 CC BY-NC-SA 4.0，ECDICT 来源保留 MIT 声明。项目：https://github.com/Lelyetia/Vocabulary-Book-for-the-College-English-Test-CET-6

具体适用范围见 [PDF 许可与第三方权利说明](../LICENSE-PDF.md)。
