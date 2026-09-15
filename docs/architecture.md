# Architecture

Общий принцип работы workflow:

```
Пользователь
     |
     ↓
Telegram Bot / Chat Interface
     |
     ↓
n8n Workflow
     |
     ↓
AI Agent
     |
     ↓
LLM Model
     |
     ↓
Ответ пользователю
```

Основные компоненты:
- n8n — оркестрация процессов;
- LLM — генерация и анализ текста;
- Telegram API — взаимодействие с пользователем;
- внешние API — получение данных.
