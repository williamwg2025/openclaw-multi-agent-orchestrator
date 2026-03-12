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
cd /root/.openclaw/workspace/skills
git clone https://github.com/williamwg2025/openclaw-multi-agent-orchestrator.git multi-agent-orchestrator
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
