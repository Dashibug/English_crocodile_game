# 🐊 English Crocodile Game

## 🎯 Описание

**English Crocodile** — интерактивное голосовое приложение, созданное в рамках курсового проекта для платформы **SmartMarket**.

🔗 [Открыть приложение в SmartMarket](https://apps.sber.ru/salute-apps/45f102ab-d2b2-4f39-8be3-b59ffe0803dc/)

---

## 🛠️ Технологии

- **Frontend:** JavaScript, TypeScript, [Svelte](https://svelte.dev)
- **Backend:** [Dialute](https://github.com/sberdevices/dialute), TypeScript
- **Взаимодействие с голосовым помощником:** @sberdevices/assistant-client

---
  

## 🚀 Установка и локальный запуск

1. Клонируйте репозиторий:
   git clone https://github.com/Dashibug/English_crocodile_game.git
   cd English_crocodile_game
   
2. Установите глобально фреймворк Dialute:
   npm install -g dialute
   
3. Установите зависимости:
   npm install @sberdevices/assistant-client
   
4. Установите и запустите ngrok на 8000 порту:
   
  ./ngrok http 8000

5. Запустите фронтенд:
  cd app
  npm install
  npm run dev

6. Запустите сервер:
  cd ../hook
  npm install
  npm run dev
