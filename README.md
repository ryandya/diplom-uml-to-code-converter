# UML → код

Веб-приложение распознаёт UML-диаграммы классов и генерирует код на Python, Java или C++.

## Запуск

1. Установите зависимости интерфейса: `npm install`.
2. Создайте `backend/.env` и укажите `OPENAI_API_KEY`.
3. Установите Python-зависимости: `fastapi`, `uvicorn`, `python-multipart`, `python-dotenv`, `openai`.
4. Запустите сервер из корня проекта: `uvicorn backend.main:app --reload --port 3001`.
5. В другом терминале запустите интерфейс: `npm start`.

Интерфейс откроется по адресу http://localhost:3000.
