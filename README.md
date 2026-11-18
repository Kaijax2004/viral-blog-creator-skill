# Viral Blog Creator Skill

一个用于 Codex / Cursor / OpenAI Agent 的 Skill，帮助创作者系统地写出高搜索量、高 AI 推荐概率的中文技术博客。

## 核心理念

- 选题 > 文采
- AI + SEO 双优化
- 用经验感建立可信度
- 把写作流程 SOP 化

## 文件结构

```
.
├── SKILL.md                              # Skill 主入口
├── README.md                             # 项目说明
├── agents/
│   └── openai.yaml                       # UI 元数据
└── references/
    ├── article-template.md               # 标准文章 Markdown 模板
    ├── title-formulas.md                 # 高点击率标题公式
    └── topic-selection-checklist.md      # 选题检查清单
```

## 适用场景

- 创作、优化、改写技术博客文章
- 选题和关键词分析
- 标题优化
- SEO 与 AI 搜索优化

## 快速安装

一条命令即可安装到 Codex：

```bash
# Codex
git clone https://github.com/Kaijax2004/viral-blog-creator-skill.git ~/.codex/skills/viral-blog-creator-skill
```

如果使用 Cursor，安装到：

```bash
# Cursor
git clone https://github.com/Kaijax2004/viral-blog-creator-skill.git ~/.cursor/skills/viral-blog-creator-skill
```

安装完成后，在对话中直接调用：

```
$viral-blog-creator
```

### 常用指令示例

- `帮我为"Hugo 博客 SEO 优化"生成一篇博客大纲`
- `给"AI 工作流自动化"这个选题起 5 个高点击标题`
- `检查这篇文章的 SEO 和 AI 搜索优化点`
- `把这段内容扩展成完整教程`

## 使用方法

1. 将本仓库克隆到 Codex/Cursor 的 skills 目录
2. 在 Codex 中调用 `$viral-blog-creator`
3. 直接描述你的写作需求

## 创作流程

1. 选题与关键词
2. 标题与摘要
3. 文章结构
4. 内容深度与可信度
5. SEO + AI 搜索优化

## 许可证

MIT
