# Привет! Меня зовут Дмитрий 👋
**Python-разработчик | ИИ-ассистенты и RAG | Сетевые технологии | Промпт-инжиниринг**

🚀 Создаю практические решения на Python: от десктоп-утилит для Windows до RAG-ассистентов с интеграцией российских нейросетей (YandexGPT, GigaChat). Фокус на воспроизводимой архитектуре, чистом коде и документировании с соблюдением академических стандартов.

---

## 🛠 Технический стек

| Категория | Инструменты и технологии |
|-----------|-------------------------|
| **Языки** | Python 3.8–3.11+, Bash, SQL, YAML |
| **Фреймворки** | FastAPI, aiogram-стиль архитектуры, Pydantic, SQLAlchemy |
| **ИИ и нейросети** | YandexGPT / Yandex Embeddings API, GigaChat-2 (Сбер), OpenAI API, LangChain, Ollama |
| **Векторные БД и RAG** | ChromaDB (cosine/L2), семантический поиск, chunking с перекрытием, кэширование ответов |
| **Сети и инфраструктура** | REST API, WebSockets, Docker, Nginx, GitHub Actions, Selenium, BeautifulSoup |
| **Инструменты** | Git, Poetry / pip, pre-commit, Ruff, pytest, uvicorn, .env-конфигурация |

---

## 📂 Избранные проекты

### 🤖 [RAG-ассистент: Yandex Embeddings + GigaChat](https://github.com/Dimitriy1204/rag-yandex-gigachat)
Консолидированный RAG-ассистент с векторным хранилищем ChromaDB и фильтрацией по источнику.
- **Задача:** Контекстные ответы на вопросы по внутренней базе знаний учебного центра.
- **Стек:** `Yandex Embeddings API`, `GigaChat-2`, `ChromaDB`, `langchain-gigachat`, `RAGAS`
- **Особенности:** авто-определение темы через LLM, приоритет фильтров, замер времени, оценка качества (Faithfulness, Context Precision)
- **Роль:** Полный цикл: архитектура, промпт-дизайн, тестирование, документация.

### 🔍 [Мониторинг конкурентов — AI Ассистент](https://github.com/Dimitriy1204/competitor-monitor)
MVP для анализа конкурентной среды с мультимодальной поддержкой (текст + изображения).
- **Задача:** Автоматизированный сбор и структурирование данных о конкурентах.
- **Стек:** `FastAPI`, `Yandex AI Studio` (yandexgpt-5-lite + gemma-3-27b-it), `Selenium`, `BeautifulSoup`, `Pydantic`
- **Функции:** анализ текста/изображений/PDF, парсинг сайтов, пакетный сбор, история запросов, Swagger-документация.

### 📊 [Yandex Wordstat API Agent](https://github.com/Dimitriy1204/yandex-wordstat-agent)
Автоматизированный сбор и анализ поискового спроса через Yandex Search API v2.
- **Задача:** Генерация аналитических отчётов по динамике спроса в формате Excel.
- **Стек:** `Yandex Search API v2`, `pandas`, `openpyxl`, `python-dotenv`
- **Результат:** Файл `yandex_analysis.xlsx` с листами: Данные, Сводка, График, «Голубые океаны», Растущие рынки.

### 👁️ [Eyesaver — Мониторинг здоровья глаз](https://github.com/Dimitriy1204/eyesaver)
Лёгкое Windows-приложение для защиты зрения при длительной работе за компьютером.
- **Задача:** Напоминания о перерывах с полноэкранной заставкой.
- **Стек:** `Python`, `pystray`, `pyinstaller` (единый .exe), Windows API
- **Особенности:** поддержка Windows XP+, работа в трее, автозагрузка, настраиваемые интервалы, нулевые внешние зависимости.

### 🎓 [RAG-ассистент с ChromaDB и кэшированием (учебный)](https://github.com/Dimitriy1204/rag-chroma-cache)
Минимальный, но полностью рабочий пример архитектуры RAG для обучения.
- **Задача:** Демонстрация принципов Retrieval-Augmented Generation с кэшированием.
- **Стек:** `OpenAI API`, `ChromaDB`, `text-embedding-3-small`, JSON-кеш
- **Особенности:** два режима работы (интерактивный/демо), подробные комментарии, модульная архитектура, оценка стоимости API.

---

## 📊 Статус проектов

| Проект | Статус | Примечание |
|--------|--------|------------|
| 👁️ Eyesaver | 🟢 Завершён | Стабильная версия, без планов обновлений |
| 🤖 RAG-ассистент (Yandex + GigaChat) | 🟢 Завершён | Готов к использованию, полная документация |
| 🔍 Мониторинг конкурентов | 🟡 В разработке | MVP работает, идёт оптимизация парсера и UI |
| 📊 Yandex-Wordstat-API-analysis  | 🟢 Завершён | Готов к использованию, полная документация |
| 🎓 RAG-ассистент (учебный) | 🟢 Завершён | Образовательный шаблон, не для продакшена |

---

## 📈 Активность и статистика
<!-- Динамические бейджи через публичные API (не собирают приватные данные) -->
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Dimitriy1204&show_icons=true&theme=radical&hide_border=true" alt="GitHub Stats" width="49%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Dimitriy1204&theme=radical&hide_border=true" alt="Streak Stats" width="49%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/YandexCloud-API-orange?logo=yandex" alt="Yandex Cloud" />
  <img src="https://img.shields.io/badge/GigaChat-Sber-green?logo=sberbank" alt="GigaChat" />
  <img src="https://img.shields.io/badge/RAG-Architecture-purple" alt="RAG" />
</p>

---

## 📚 Академическая практика и документирование

В учебных и исследовательских проектах придерживаюсь принципов академической честности:

✅ Все сторонние библиотеки, API и научные источники явно указаны в `README` и `REFERENCES.md`  
✅ Цитирование оформляется по стандартам **APA 7** или **MLA 9**  
✅ Код сопровождается комментариями, тестами и фиксированными зависимостями  
✅ Архитектура воспроизводима: `.env.example`, `requirements.txt` / `pyproject.toml`, инструкции по запуску

📌 *Пример оформления ссылки на документацию API (APA 7):*  
Яндекс. (2026). *YandexGPT API Documentation*. https://yandex.cloud/ru/docs/foundation-models/

📌 *Пример оформления (MLA 9):*  
SberDevices. "GigaChat API Documentation." *SberCloud*, 2026, https://developers.sbercloud.ru/docs/gigachat.

---

## 📬 Контакты и ресурсы

- 📧 **Email:** mitrich_zlat@disroot.org
- 💬 **Telegram:** @promt_DmitryiZlat
- 🌐 **Портфолио / Блог:** https://marketplace.zerocoder.ru/zerocoder/21644
- 🐙 **GitHub:** [github.com/Dimitriy1204](https://github.com/Dimitriy1204)

> 💡 *Открыт к сотрудничеству по проектам в области ИИ-ассистентов, RAG-архитектур, автоматизации и сетевых решений. Предпочитаю инструменты, работающие в локальной сети без обязательного доступа в интернет.*

---
*Последнее обновление: Май 2026 | Сгенерировано с учётом реальных проектов портфолио*
