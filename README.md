# MinecraftBotsAPI

[![Python Version](https://img.shields.io/badge/python-3.10%2B-blue)](https://www.python.org/)
[![Node.js Version](https://img.shields.io/badge/node.js-18%2B-green)](https://nodejs.org/)
[![License](https://img.shields.io/badge/license-Unlicence-lightgrey)](LICENSE)

---

**MinecraftBotsAPI** — это Python-фреймворк для создания и управления Minecraft-ботами через Node.js и библиотеку [mineflayer](https://github.com/PrismarineJS/mineflayer).  

Python выступает как управляющий слой (логика, AI, реакции), а Node.js — как Minecraft-клиент.

---

## 🔹 Возможности

- Подключение бота к Minecraft-серверу
- Отправка сообщений в чат
- Подписка на события: чат, кик, ошибка, статус
- Follow / StopFollow игрока
- Приветственные сообщения
- Безопасное завершение процесса бота

---

## ⚙️ Требования

- Python 3.10+
- Node.js 18+
- npm-пакет [mineflayer](https://www.npmjs.com/package/mineflayer)

```bash
npm install mineflayer
