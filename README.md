# Viral Blog Creator Skill

一个用于 Codex / Cursor / OpenAI Agent 的 Skill，帮助创作者系统地写出高搜索量、高 AI 推荐概率、具备传播力的中文技术博客。

方法论融合了两套体系：
- **SEO + AI 搜索优化**：让文章被搜索引擎收录、被 AI 摘要直接引用；
- **公众号 0→10W+ 爆款方法论**：选题洞察、四大标题套路、爆文五段结构、素材库、情绪价值与信息增量。

## 核心理念

- 选题 > 文采（成败 70% 在选题）
- 信息价值 + 情绪价值双轮驱动（开头 3 秒决定完读率）
- 信息增量优先：多说"别人没有说的"
- AI + SEO 双优化
- 用经验感建立可信度（E-E-A-T）
- 先定风格再动笔，用差异化标签立人设
- 把写作流程 SOP 化，先写满 100 篇

## 文件结构

```
.
├── SKILL.md                              # Skill 主入口（六大系统 + 拆解工作流）
├── README.md                             # 项目说明
├── agents/
│   └── openai.yaml                       # UI 元数据
└── references/
    ├── title-formulas.md                 # 四大标题套路 + 高点击率标题公式
    ├── article-template.md               # 搜索型 / 传播型双结构 Markdown 模板
    ├── topic-selection-checklist.md      # 选题检查清单（含评论区洞察与小范围测试）
    ├── style-system.md                   # 品牌声线 + 风格解析法
    └── viral-deconstruction.md           # 爆文拆解三步法
```

## 适用场景

- 创作、优化、改写技术博客文章
- 选题和关键词分析
- 标题优化（A/B 起标题）
- SEO 与 AI 搜索优化检查
- 拆解对标爆文，提炼方法论
- 用固定品牌声线改写草稿

## 快速安装

一条命令即可安装到 Codex：

```bash
# Codex
git clone https://github.com/Kaijax2004/viral-blog-creator-skill.git ~/.codex/skills/viral-blog-creator
```

如果使用 Cursor，安装到：

```bash
# Cursor
git clone https://github.com/Kaijax2004/viral-blog-creator-skill.git ~/.cursor/skills/viral-blog-creator
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
- `拆解这篇爆文，总结它的方法论`
- `用易安记风格改写这篇草稿`

## 使用方法

1. 将本仓库克隆到 Codex/Cursor 的 skills 目录
2. 在 Codex 中调用 `$viral-blog-creator`
3. 直接描述你的写作需求

## 创作流程（六大系统）

1. **选题洞察**：评论区/问答区洞察 → 选题库 → 小范围测试 → 读者视角三问
2. **标题优化**：四大套路（制造反差 / 数字具象 / 直击痛点 / 利益承诺）× 关键词约束
3. **结构搭建**：搜索型（倒金字塔）或传播型（钩子→重要性→原因→方案→行动）
4. **素材积累**：名人案例 / 身边故事 / 数据金句 / 个人经历，分类建库
5. **风格系统**：易安记品牌声线卡片 + 风格解析法，先定风格再动笔
6. **SEO + AI 优化**：front matter / Schema / AI 摘要友好结构 / 内外链

外加一个**爆文拆解工作流**：拆标题开头 → 逐段标注 → 理逻辑，把别人的爆款变成自己的资产。

## 许可证

MIT
