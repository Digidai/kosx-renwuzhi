# KOSX 人物志 · 创造者黄页

基于 [impact.kosx.ai](https://impact.kosx.ai/) 的入口，把 KOSX 社群在 X 上的大 V 做成「他是谁 / 写什么 / 怎么合作」的人物档案站。

这不是 impact.kosx.ai 的仪表盘复刻。impact 已经做好粉丝、登阶、影响力指数与近 20 帖采集。本站补的是叙事档案与合作黄页。

数据快照：2026-09-25 16:00 UTC（impact 采集）+ 2026-09-26 X 公开主页复核。

## 社群快照

- 追踪成员 113–114（榜单可见 113）
- 万粉成员 18
- 社群累计粉丝 754,607
- 过万占比 7.7% · 认证 49.0% · 近 30 天 +61,770
- 赛道：AI工具 58 · 增长 33 · 开发者 23 · 财经 23 · 出海 5

## 万粉 18

| #  | 名字 | Handle | 粉丝 | 定位 |
| --- | --- | --- | ---: | --- |
| 1 | 魂蓝 | [@hunlan77](https://x.com/hunlan77) | 113.8k | SISSYSTARS 品牌，成人向需 18+ 标注 |
| 2 | Roland.W | [@rwayne](https://x.com/rwayne) | 61.3k | 澳洲 PhD，本地模型 / 知识库 / GEO |
| 3 | 黄小木 | [@ai_xiaomu](https://x.com/ai_xiaomu) | 50.8k | 前大厂 T11 → OPC，First Check |
| 4 | Jackywine | [@Jackywine](https://x.com/Jackywine) | 48.2k | Obsidian / Prompt / 模型拆解 |
| 5 | 蜗牛King | [@isnail](https://x.com/isnail) | 43.1k | 自媒体小项目实战 |
| 6 | Adrian Punk | [@AdrianPunk115](https://x.com/AdrianPunk115) | 37.5k | AI 视觉 Skills，AfterNoise |
| 7 | AI最严厉的父亲 | [@dashen_wang](https://x.com/dashen_wang) | 29.8k | AGI 叙事 / 态度帖 |
| 8 | 阿川 | [@AI_jacksaku](https://x.com/AI_jacksaku) | 27.7k | AI 产品商业化，3 天万粉 |
| 9 | 诺鸭船长3 | [@noahduck283](https://x.com/noahduck283) | 22.4k | AI 工作流 / 数字基建 |
| 10 | 得否 | [@wangdefou](https://x.com/wangdefou) | 17.8k | 文科生搞 AI，企业顾问，MarkX |
| 11 | Foe Ally | [@ally_foe](https://x.com/ally_foe) | 16.4k | 不接广告的生活流 |
| 12 | Serena 木瓜 | [@369Serena](https://x.com/369Serena) | 15.6k | AI 小白教程 / KOL 运营 |
| 13 | Chenxi | [@CMhOeNnExY](https://x.com/CMhOeNnExY) | 14.0k | 深圳 AI 公司 CEO，B 端 Agent |
| 14 | Yuvi | [@Li665508Li](https://x.com/Li665508Li) | 11.9k | 财经 / 增长 |
| 15 | Kimberly | [@king1818888](https://x.com/king1818888) | 11.4k | 澳洲 Builder，FlareMo / Video Script |
| 16 | YiLong Ma（模仿） | [@mayilong0](https://x.com/mayilong0) | 11.3k | 币圈模仿号，页面需标注 |
| 17 | 微尘印记 | [@weichen_ink](https://x.com/weichen_ink) | 10.8k | 创作者工具箱 + YouTube |
| 18 | Russell | [@Russell3402](https://x.com/Russell3402) | 10.6k | 05 大学生，Syntax Studio |

新锐补位：苏乐 [@ai_suxiaole](https://x.com/ai_suxiaole) · 可可鸭 [@KeKeYa88](https://x.com/KeKeYa88) · Chill [@Chilljccu](https://x.com/Chilljccu) · Edison [@Edison_aware](https://x.com/Edison_aware)

社群节点：Vegas Liu [@vegas_liu](https://x.com/vegas_liu) （KOSX 主理人）

## X 内容能不能「租」，能不能动态更新？

不能便宜租 X firehose。Enterprise 火推需官方合约，价格不是社群看板级预算。

合规三条路：

1. **展示层（免费、始终最新）**  
   官方 embed / oEmbed：`https://publish.x.com/oembed` + `https://platform.twitter.com/widgets.js`  
   单帖与 timeline widget 会自动跟随作者删帖、账号状态。

2. **指标层（小时级 cron）**  
   X API v2 Basic（约 $200/月）足够 100+ 账号：  
   `GET /2/users/by/username/:username`  
   `GET /2/users/:id/tweets`  
   与 impact.kosx.ai 现有小时采集对齐。

3. **复用 impact 管线**  
   他们已在拉公开粉丝与近 20 帖。本站可以只做人物志层，指标继续读他们。

禁止：大规模非官方爬取、转存付费内容、忽视 rate limit、不加年龄门展示成人账号。

### Embed 示例

```html
<blockquote class="twitter-tweet">
  <a href="https://x.com/Edison_aware/status/2103084919635509483"></a>
</blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
```

## 本仓状态

- `index.html`：单页人物志站（由团队写入）
- 本 README：产品定位与动态更新方案

源站：[impact.kosx.ai](https://impact.kosx.ai/) · [kosx.ai](https://kosx.ai/) · [@kosxai](https://x.com/kosxai)
