# 新闻来源规范

最后更新：2026-10-23 10:20 Asia/Shanghai

## 来源优先级

1. `T1`：官方机构原文，可直接作为政策和数据的正式依据。
2. `T2`：官方 RSS、官方发布会和官方统计数据库，用于提高更新时效。
3. `T3`：权威通讯社或主流媒体，仅用于发现线索和补充背景；重大结论仍需官方确认。
4. `T4`：其他公开来源，不单独支撑重大结论。

## 双轨职责

- **媒体发现层**：每次运行必须扫描国内和国际权威媒体，用于发现热点、突发事件和市场情绪。
- **官方核验层**：对媒体线索寻找官方原文；官方未发布的保留为 `媒体先导` 或 `媒体交叉`。
- **报告隔离**：媒体热点单独写入“媒体热点扫描”，不得混入“已确认事实”。
- **基线说明**：首份 30 天基线刻意以官方政策、数据和大事件为主，不能代表后续日报的媒体热点覆盖程度。

## 国内官方

| ID | 来源 | 入口 | 级别 | 首轮状态 | 备注 |
|---|---|---|---|---|---|
| CN-GOV | 中国政府网 | https://www.gov.cn/zhengce/zuixin/ | T1 | 正常 | 政策原文优先 |
| CN-PBOC | 中国人民银行 | https://www.pbc.gov.cn/goutongjiaoliu/113456/113469/index.html | T1 | 正常 | 新闻索引和演讲正文可读；部分数据文章正文可能不完整 |
| CN-NBS | 国家统计局 | https://www.stats.gov.cn/sj/zxfb/ | T1 | 正常 | 数据发布日期和正文通常完整 |
| CN-NDRC | 国家发展改革委 | https://www.ndrc.gov.cn/xwdt/xwfb/ | T1 | 正常 | 部分当日发布会更新可能晚于媒体 |
| CN-MOF | 财政部 | https://www.mof.gov.cn/zhengwuxinxi/caizhengxinwen/ | T1 | 首轮未测 | 使用前检查发布时间和附件 |
| CN-CSRC | 中国证监会 | https://www.csrc.gov.cn/csrc/index.shtml | T1 | 正常，需规避旧列表 | `c100028/common_list.shtml` 曾显示 2021 年旧内容；优先官网首页和直接文章 |
| CN-SSE | 上海证券交易所 | https://www.sse.com.cn/aboutus/mediacenter/hotandd/ | T1 | 正常 | 直接文章正文可读 |
| CN-SZSE | 深圳证券交易所 | https://www.szse.cn/aboutus/trends/news/ | T1 | 首轮未测 | 使用前检查页面结构与时间 |

## 国际官方

| ID | 来源 | 入口 | 级别 | 首轮状态 | 备注 |
|---|---|---|---|---|---|
| US-FED | 美联储 | https://www.federalreserve.gov/feeds/press_all.xml | T1/T2 | 正常 | RSS 比新闻列表稳定，直接文章可读 |
| US-BLS | 美国劳工统计局 | https://www.bls.gov/bls/newsrels.htm | T1 | 正常 | 发布日历：https://www.bls.gov/schedule/news_release/ |
| US-TREASURY | 美国财政部 | https://home.treasury.gov/news/press-releases | T1 | 正常 | 新闻索引可读 |
| EU-ECB | 欧洲央行 | https://www.ecb.europa.eu/rss/press.html | T1/T2 | RSS 正常 | 普通新闻页本轮主要读到 Cookie 提示，优先 RSS |
| IMF | 国际货币基金组织 | https://www.imf.org/en/News | T1 | 正常 | 声明和新闻稿正文可读 |
| WORLD-BANK | 世界银行 | https://www.worldbank.org/en/news | T1 | 首轮未测 | 仅在需要时检查 |
| US-WHITEHOUSE | 白宫 | https://www.whitehouse.gov/briefing-room/ | T1 | 首轮未测 | 用于政策、制裁和行政令 |
| UN | 联合国 | https://news.un.org/en/ | T1 | 未获取 | 本轮页面读取失败；优先改用具体机构官方稿 |

## 权威媒体

| ID | 来源 | 入口 | 级别 | 首轮状态 | 备注 |
|---|---|---|---|---|---|
| CN-XINHUA | 新华社 | https://www.news.cn/politics/ | T3 | 正常 | 可补政策背景 |
| CN-CCTV | 央视新闻 | https://news.cctv.com/ | T3 | 正常 | 可补国内热点 |
| CN-CLS | 财联社 | https://www.cls.cn/ | T3 | 正常 | 时效快；行情和日历栏目可能动态加载 |
| INTL-REUTERS | 路透社 | https://www.reuters.com/world/ | T3 | 未获取 | 本轮正文为空，不能据此确认新闻 |
| INTL-AP | 美联社 | https://apnews.com/hub/world-news | T3 | 正常 | 可作国际事件先导 |
| INTL-BBC | BBC | https://www.bbc.com/news/world | T3 | 正常 | 可作国际事件先导 |
| JP-NHK | NHK World | https://www3.nhk.or.jp/nhkworld/en/news/ | T3 | 待复核 | 日本及东亚安全事件发现层，重大结论回查日本防卫省 |
| JP-KYODO | 共同社 | https://english.kyodonews.net/ | T3 | 待复核 | 日本防务和区域安全报道发现层 |

## 区域安全官方来源

| ID | 来源 | 入口 | 级别 | 当前状态 | 备注 |
|---|---|---|---|---|---|
| US-INDOPACOM | 美国印太司令部 | https://www.pacom.mil/Media/News/ | T1 | 正常 | 东亚、台海、南海、朝鲜半岛和美日演习 |
| JP-MOD | 日本防卫省 | https://www.mod.go.jp/ | T1 | 正常 | 日本及西南诸岛防务、联合演习和部署 |
| US-CENTCOM | 美国中央司令部 | https://www.centcom.mil/MEDIA/NEWS-RELEASES/ | T1 | 正常 | 中东、海湾、红海、伊朗和海上封锁相关公告 |
| US-EUCOM | 美国欧洲司令部 | https://www.eucom.mil/pressroom | T1 | 正常 | 俄乌、欧洲防务和北约东翼 |
| NATO | 北大西洋公约组织 | https://www.nato.int/cps/en/natohq/news.htm | T1 | 正常 | 欧洲安全、东翼部署和成员国联合行动 |
| UA-MOD | 乌克兰国防部 | https://www.mil.gov.ua/ | T1 | 页面结构待复核 | 俄乌战场通报；页面改版时改用官方社交账号和权威媒体 |
| CN-MND | 中国国防部英文站 | https://eng.mod.gov.cn/ | T1 | 证书异常 | 页面不可用时改用中国国防部中文站、新华社和央视 |
| KR-MND | 韩国国防部英文站 | https://www.mnd.go.kr/mbshome/mbs/mndEN/index.do | T1 | 访问待复核 | 朝鲜半岛安全事件；不可用时改用韩联社和美军印太司令部 |

## 地缘安全与重大演习

- 每轮简报至少检查美国印太司令部、日本防卫省、美国中央司令部、美国欧洲司令部和北约的最新公告。
- 区域快扫必须覆盖中东与红海、俄乌与欧洲、台海与南海、朝鲜半岛、南亚；其他地区有活跃冲突时一并检查。
- 对 `events/active.md` 中的军演、部署和冲突事件逐轮检查，即使滚动窗口内没有新的媒体热点。
- 已排期演习进入执行阶段、出现规模或地点变化、发生新部署、或临近结束节点时，均视为实质更新。
- 官方未给出规模或部署细节时，不采用二手标题中的“史上最大”“全面战争预演”等定性，只保留可核实数字并注明媒体说法。
- 交战方公告只能证明“其公开声称了什么”，不能自动证明战场事实；袭击、战损和停火进展需保留归因与核验状态。

## 抓取规则

- 优先官方 RSS 或结构化页面，其次官方新闻索引，再使用权威媒体搜索。
- 每次日报至少阅读新华社、央视、财联社、美联社和 BBC 的公开首页或栏目页，路透社可访问时同时阅读。
- 媒体热点按时间和市场影响筛选，保留 3—8 条候选，重复或纯娱乐新闻不进入。
- 记录页面标题、发布时间、抓取时间和正文是否完整。
- 页面展示旧日期时立即标记“疑似旧页/缓存页”，不得当作当日新闻。
- 媒体正文为空、付费墙或登录墙时标记 `未获取`。
- 重大事件只引用可公开访问的原文，不用搜索摘要替代正文。
- 同一事件优先引用最早官方来源；后续更新保留原记录。

## 首轮可用性结果

- 核心官方来源实测：10/12 正常，约 83.3%。
- 国内官方：5/6 正常；证监会旧列表失效，但官网首页替代可用。
- 国际官方：5/6 正常；联合国新闻页失败。
- 权威媒体：5/6 正常；路透社正文为空。

该结果仅代表 2026-10-20 本轮公开页面可读状态，不代表后续永久可用。
