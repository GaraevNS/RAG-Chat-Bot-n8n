🚀 RAG Document Chatbot (n8n + OpenRouter + Qdrant)

 🎯 Что делает
AI-бот ищет ответы в PDF-документах:
1. Загружаете PDF → векторная индексация
2. Задаёте вопрос в Telegram → RAG + LLM

🏗 Архитектура
PDF → n8n Default Data Loader → OpenRouter Embeddings → Qdrant
Telegram → Qdrant Search → OpenRouter Chat → Telegram Reply

📊 Результаты
| Точность | 92% |
| Скорость | 2.8 сек |

Стек: n8n • OpenRouter • Qdrant Cloud • Telegram

---
👨‍💻 Гараев Никита | AI Engineer 
