# 💬 AI Chat Tools

AI聊天工具，支持聊天机器人、对话系统、客服。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 🤖 聊天机器人设计
- 🎯 意图识别
- 💬 对话流程设计
- 📚 知识库生成
- 📊 对话分析
- 🌐 多语言支持

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_chat_tools import create_tools

tools = create_tools()

# 聊天机器人设计
chatbot = tools.design_chatbot("客服", ["Web", "微信"])

# 意图识别
intent = tools.generate_intent_recognition(intents)

# 对话流程
dialogue = tools.design_dialogue_flow("订单查询")

# 知识库
kb = tools.generate_knowledge_base("电商", documents)

# 对话分析
analysis = tools.analyze_conversation(conversation)

# 多语言
multilingual = tools.generate_multilingual_bot("中文", ["英语", "日语"])
```

## 📁 项目结构

```
ai-chat-tools/
├── tools.py       # 聊天工具核心
└── README.md
```

## 📄 许可证

MIT License
