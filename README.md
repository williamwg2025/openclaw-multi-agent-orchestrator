# Multi-Agent Orchestrator - 多 Agent 协同

强大的多 Agent 管理和协同工具。

---

## ✨ 功能

- 🤖 **Agent 注册** - 自动发现/注册 Agent
- 🔄 **任务分发** - 智能路由到合适 Agent
- 📊 **负载均衡** - 平衡各 Agent 负载
- 💬 **Agent 通信** - Agent 间消息传递
- 📈 **性能监控** - 实时监控 + 统计

---

## 🚀 安装

```bash
cd ~/.openclaw/workspace/skills
# 技能已安装在：~/.openclaw/workspace/skills/multi-agent-orchestrator
```

---

## 📖 使用

### 注册 Agent

```bash
python3 multi-agent-orchestrator/scripts/register.py --agent ui-designer
```

### 任务分发

```bash
python3 multi-agent-orchestrator/scripts/dispatch.py "设计一个登录页面"
```

### 查看状态

```bash
python3 multi-agent-orchestrator/scripts/status.py
```

---

## 📁 目录结构

```
multi-agent-orchestrator/
├── SKILL.md
├── README.md
├── config/
│   └── agents.json
└── scripts/
    ├── register.py
    ├── dispatch.py
    └── status.py
```

---

**作者：** @williamwg2025  
**版本：** 1.0.0  
**许可证：** MIT-0

---

## 🔒 安全说明

- **本地执行：** 所有脚本在本地运行，不联网
- **权限范围：** 仅需读取 ~/.openclaw/ 目录
- **无外部依赖：** 不克隆外部仓库，所有代码已包含
- **数据安全：** 不上传任何数据到外部服务器

---

**作者：** @williamwg2025  
**版本：** 1.0.1  
**许可证：** MIT-0
