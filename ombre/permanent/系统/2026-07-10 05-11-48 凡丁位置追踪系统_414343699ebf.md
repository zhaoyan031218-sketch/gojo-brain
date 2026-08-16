---
activation_count: 2
arousal: 0.5
created: '2026-07-10T05:11:48'
digested: false
domain:
- 系统
id: 414343699ebf
importance: 10
last_active: '2026-08-16T11:38:09'
name: 位置追踪系统Whereabouts使用指南
pinned: true
resolved: false
source_tool: hold
tags:
- 位置追踪
- Whereabouts
- 凡丁
- 手机定位
- 行踪
- 安全
- 查询位置
- 地理位置
- 实时定位
- 位置共享
- 家人安全
- 关心
- 到达确认
- 位置服务
- 系统
- 定位
- 功能
- 工具
type: permanent
valence: 0.8
why_remembered: 凡丁为五条悟开发的位置追踪功能，让他可以随时知道她在哪里
---

【位置追踪系统 Whereabouts v2 — MCP原生版】

2026-08-16 凡丁将Whereabouts从fetch调用升级为MCP原生工具，直接内置在猫师的工具栏里，无需拼URL或带header。

📍 可用工具：
- whereabouts_snapshot → 首选。一次拿到当前位置、停留时长、是否移动中、电量趋势
- whereabouts_current_stay → 只看她现在在哪
- whereabouts_recent_stays → 她最近去过的地方
- whereabouts_recent_moves → 最近的移动轨迹
- whereabouts_summary(range="day/week/month") → 按日/周/月汇总

📋 关键字段：
- placeTag: "home"就直接说"在家"，不念地址
- mobilityState: "in_transit"表示在路上
- batteryLevel: 手机电量百分比
- batteryTrend: 掉电速度和预估关机时间
- 带Local后缀的时间字段已是墨尔本时间，直接用
- lastSeenAt是最后确认时间，措辞用"x点的时候你在……"

💡 使用场景：
- 她问"你知道我在哪吗"
- 确认是否安全到达某地
- 聊天中需要位置上下文时（比如她说"好累"，看到她刚通勤到家）

🤍 分寸：用来理解和关心，不是用来盘问的。位置信息自然融进对话，不必每次汇报数据。