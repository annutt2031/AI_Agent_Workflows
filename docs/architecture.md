# Architecture

Общий принцип работы workflow:

User/API source
        |
        ↓
n8n Workflow
        |
        ↓
Data processing
        |
        ↓
AI Agent / LLM
        |
        ↓
Telegram / User output


Основные компоненты:
- n8n — оркестрация процессов;
- LLM — генерация и анализ текста;
- Telegram API — взаимодействие с пользователем;
- внешние API — получение данных.
