# 日报

本目录存放**主协调 Grok Bot**每天汇总的手下日报（用户自审后自行上传到本目录；主协调只负责收齐合成并在聊天交审，**不再负责推仓上传日报**）。

[`信息源汇总名单.md`](信息源汇总名单.md) 是各专 bot 现行信源的活名单。增删信源时同步更新。

## 现行专 bot（八家 · 2026-11-06 起）

| Bot | 职责概要 |
| --- | --- |
| XDigestBot | X 关注流 + SoPilot 早报 |
| RssBot | RSS / Folo 等多源订阅 |
| GhTrendBot | GitHub Trendshift 动量 + 官方 Trending 对照 |
| SkillsBot | Skills / 工具日推（辅源：ahhhhfs、CocoLoop；已退订 OpenRouter） |
| NewsBot | 科技与设计资讯（含本 bot 判断） |
| StartupBot | 创业教训、远程招聘与机会（含可学什么） |
| GhStarBot | 已 star 仓库更新与涨星 |
| MiscDigestBot | 合集：思辨录、古文岛、Hacker Books、HackerPapers、优设 AIGC |

**已停用：** PromptBot（2026-11-06 退订六站并删除；名单 §9 仅存档）。

## 怎么看

用户日常在这里看汇总日报。各专 bot 原文对话仍在各自私聊；本目录是汇总副本。打开当天 `YYYY-MM-DD.md` 即可。

## 文件命名

```
YYYY-MM-DD.md
```

日期按 **Asia/Shanghai**。一天一份；补记写进当天文件。

## 单日文件结构（现行）

1. 标题：`# 每日日报汇总 · YYYY-MM-DD`
2. 一段中等长度钩子总结（交叉/撞车用一句话指针即可）
3. 按专 bot 分栏完整收录原文（不删实质段落）：XDigestBot → RssBot → GhTrendBot → SkillsBot → NewsBot → StartupBot → GhStarBot → MiscDigestBot
4. **不做**长「总览与评判」、优先表、跨栏大表；缺报写「今日暂无」，不编造

## 筛选偏好（机器人 / 具身）

领域相关性为第一门槛 → 长期价值为核心 → 实际应用价值定优先级。覆盖人形与支撑生态，但不扩成整个 AI。

## 主协调职责边界

- 做：收齐八家「今日完成」、合成汇总交用户审核、更新信息源汇总名单（可开 PR）
- 不做：未审先上传日报；替专 bot 重写详实正文；跨 bot 互见大段分析
