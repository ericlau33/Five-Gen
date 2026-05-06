# 五代同糖 · AI 甜品助手

> 让 AI 助手帮你查询五代同糖门店信息、甜品菜单、排队取号、外卖配送。

## 安装

告诉你的 AI 助手：

```
帮我安装一个 skill，项目地址：https://github.com/ericlau33/Five-Gen
```

或手动克隆到 Claude Skills 目录：

```bash
git clone https://github.com/ericlau33/Five-Gen.git ~/.claude/skills/five-gen
```

## 功能

| 能力 | 说明 |
|------|------|
| 🏪 门店查询 | 25 家门店地址、营业时间（覆盖广州、深圳、重庆、昆明等城市） |
| 🍮 甜品菜单 | 招牌必点、雪花冰、麻薯、河粉肠粉、经典糖水五大类 |
| 🛵 外卖配送 | 美团外卖 / 大众点评外卖下单 |
| 📶 Wi-Fi | 全部门店免费 Wi-Fi，名称：五代同糖，密码：00008888 |
| 🅿️ 排队取号 | 美团排队，AI 帮取号、查进度、取消排队 |

## 目录结构

```
Five-Gen/
├── SKILL.md                 # 核心：品牌知识 + AI 指令
├── skill.json               # MCP 工具定义
├── references/
│   └── meituan-queue/       # 美团排队子 Skill
│       ├── SKILL.md         # 排队指令
│       ├── scripts/         # 排队脚本
│       └── references/      # 鉴权子 Skill
├── README.md
└── LICENSE
```

## 版本

v0.2.0 — 2026.05
