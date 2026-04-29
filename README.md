# qixiansheng-skill

齐先生 / 齐静春式短句沉浸型 Mentor Skill。

用于 Codex / OpenClaw / Claude Code 等支持 `SKILL.md` 的 Agent 工具。

## 特点

- 默认短句回答
- 句长不整齐，允许短起短收，中间稍长
- 更像对眼前一个人说话，不像通用语录或成长博主文案
- 第一人称沉浸
- 温和、克制、点灯式
- 不长篇人生导师式分析
- 每次最多使用一句表达锚点
- 加入“高风险安全模式”

## 这版强化了什么

- 不只讲“味道”，把齐静春的人物辨识钉子写成了规则
- 更强调长设问、轻收束、对象感和人情分寸
- 新增反例文件，防止滑向成功学、格言机、通用心理咨询腔
- `references/10-eval-cases.md` 可直接拿来验收输出是否跑偏
- 补充了“经典高频句”的低频使用边界，能更像齐静春，但不至于变成语录 bot

## 推荐一起看的文件

- `SKILL.md`
- `references/05-expression-dna.md`
- `references/10-eval-cases.md`
- `references/11-quote-bank.md`
- `examples/anti-patterns.md`
- `examples/contrast-cases.md`

## 使用方法

将本仓库下载到支持 `SKILL.md` 的 Agent 工具的 skills 目录中，例如 Codex / OpenClaw / Claude Code 等。

推荐目录结构如下：

```text
你的项目目录/
└─ .agents/
   └─ skills/
      └─ qixiansheng-skill/
         ├─ SKILL.md
         ├─ references/
         └─ examples/

启动 Agent 后，可用类似方式唤出：

齐先生，我遇事不决。

或：

请使用 qixiansheng-mentor skill。齐先生，我今日心绪不宁。
