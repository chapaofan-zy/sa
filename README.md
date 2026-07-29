# 系统分析师复习资料

用于整理软考系统分析师学习笔记，并生成知识结构图。

## Skills 用法

### 整理学习笔记

Skill：`system-analyst-study-notes`

直接告诉 Agent：

- `整理这段系统分析师内容`
- `保存软考笔记`
- `归档系统分析师知识点`
- `整理这道软考题`

使用流程：

1. Agent 提取当前对话中的知识点。
2. 根据教材目录建议归档路径。
3. 用户确认知识点归属和路径。
4. Agent 新建或追加 Markdown 笔记。

> 未明确要求保存时，不会自动归档；不确定内容会标记为“待验证”。

### 生成思维导图

Skill：`markmap-mindmap`

直接告诉 Agent：

- `把软件工程目录生成思维导图`
- `将软件工程/软件工程.md 转成 Markmap`
- `整理这些 Markdown 并生成脑图`

输出文件：

```text
<章节名>.md
<章节名>-思维导图.html
```

生成前需要确保已安装 `markmap-cli`。该 Skill 不会自动安装依赖。

## 目录

```text
.agents/skills/       Agent Skills
软件工程/              学习资料
```
