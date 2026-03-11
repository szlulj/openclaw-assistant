# TOOLS.md - Local Notes

Skills define _how_ tools work. This file is for _your_ specifics — the stuff that's unique to your setup.

## Cron 定时任务

| 时间 | 任务 | 说明 |
|------|------|------|
| 9:00 | HEARTBEAT | 每日任务检查 + 喝水提醒 |
| 10:00 | 💧 喝水 | 站起来活动一下 |
| 11:00 | 💧 喝水 | 站起来活动一下 |
| 15:00 | 💧 喝水 | 站起来活动一下 |
| 16:00 | HEARTBEAT | 每日任务检查 + 喝水提醒 |
| 18:00 | 💧 喝水 | 工作快结束了 |

时区：Asia/Shanghai

## TTS

- 飞书渠道已测试，支持语音消息
- 默认用文字沟通（效率更高）

## Git 远程仓库

- GitHub: https://github.com/szlulj/openclaw-assistant
- 私有仓库，仅自己可见

## Tavily Search

- API Key: 已配置 (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)
- 技能位置：~/.openclaw/skills/tavily-search/
- 使用方式：`TAVILY_API_KEY="xxx" node ~/.openclaw/skills/tavily-search/scripts/search.mjs "查询内容"`

---

Add whatever helps you do your job. This is your cheat sheet.
