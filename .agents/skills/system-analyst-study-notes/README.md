# system-analyst-study-notes

整理当前对话中的软考系统分析师内容，并在用户确认知识点归属和归档路径后保存为 Markdown 笔记。

## 流程

1. 提取当前对话中的知识点、题目解析、易错点和备考记录。
2. 读取 `references/textbook-toc.md`，按教材层级推导归档路径。
3. 展示知识点、教材归属、目标路径和文件操作，等待用户确认。
4. 用户确认后新建或追加笔记，并检查归档结果。

## 规则

- 普通问答且未要求保存时不激活。
- 只整理当前对话中可追溯的信息，不凭空补充结论。
- 路径不包含教材编号和页码，例如：
  `计算机系统/存储系统/主存.md`。
- 不确定或无法匹配的内容标记为“待验证”或“待确认”。
- 归档前必须确认知识点归属和归档路径。

## 使用方式

安装后，对 Agent 说以下类似的话即可激活：

- “整理这段系统分析师内容”
- “保存软考笔记”
- “归档系统分析师知识点”
- “整理这道软考题”
- `organize system analyst notes`
- `save exam notes`
- `archive system analyst knowledge`

## 文件结构

```text
skills/system-analyst-study-notes/
├── README.md
├── SKILL.md
└── references/
    ├── archive-template.md
    └── textbook-toc.md
```
