<br/>
<p align="center">
  <a href="https://github.com/Sav1taRG/iChatGPT">
    <img src="https://github.com/Sav1taRG/iChatGPT/blob/master/ChatGPT/Assets.xcassets/AppIcon.appiconset/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">iChatGPT</h3>

  <p align="center">
    Tiny ChatGPT client for your iPhone
    <br/>
    <br/>
  </p>
</p>




# 🤖 iChatGPT

SwiftUI-приложение для iOS, iPadOS и macOS, реализующее клиент ChatGPT через неофициальный SessionToken от OpenAI.

---

## 📌 Описание

**iChatGPT** позволяет пользователям общаться с ChatGPT прямо из приложения, сохраняя контекст между сообщениями, копировать сообщения, повторять запросы, а также работать на iPhone, iPad и Mac. Для работы необходимо ввести `__Secure-next-auth.session-token`, полученный из браузера при авторизации на сайте OpenAI citeturn0search0.

---

## 🛠 Технологии и архитектура

- Язык: Swift  
- UI: SwiftUI  
- Архитектура: MVVM / reactive (`@State`, `@StateObject`, `ObservableObject`)  
- Сеть: работа с неофициальным API ChatGPT через `backend-api/conversation`, поддержка стриминга ответов и синхронизация истории citeturn0search8.

---

## 🎱 Особенности

- Ввод SessionToken для доступа к ChatGPT  
- Потоковая передача ответа (streaming) с автопрокруткой  
- Сохранение истории диалога  
- Копирование и повтор запросов  
- Кроссплатформенность: iOS 14+, iPadOS 14+, macOS 11+ citeturn0search1

---

## 🚀 Установка и запуск

1. Клонируйте репозиторий:  
   ```bash
   git clone https://github.com/Sav1taRG/iChatGPT.git
   cd iChatGPT
   ```
2. Откройте проект в Xcode:  
   ```bash
   open iChatGPT.xcodeproj
   ```
3. Запустите приложение и введите SessionToken (полученный из cookies браузера).  
4. Выберите устройство (iPhone/iPad/Mac), соберите и запустите приложение.

---

## 📚 Использование

1. Введите SessionToken для аутентификации.  
2. Начните новый диалог — отправляйте вопросы и просматривайте ответы в реальном времени.  
3. Сохраняйте историю, копируйте или повторяйте предыдущие запросы.  
4. Открывайте предыдущие диалоги из списка сохранённых.

---

## 🔧 Дорожная карта

- ✅ Поддержка стриминга вывода  
- ✅ История разговоров + автопрокрутка  
- ❌ Подсветка кода и вставка фрагментов  
- ❌ Голосовой ввод  
- ❌ Экспорт диалога (PDF, изображение)  
- ❌ Тёмная тема и кастомизация интерфейса  
- ❌ Поддержка альтернативных способов аутентификации  
- И многое другое…

---

## 🎯 Цели проекта

- Изучение SwiftUI и MVVM на реальном примере  
- Практика работы с потоковыми сетевыми ответами  
- Реализация полноценного клиента ChatGPT  
- Получение обратной связи и участие сообщества через PR и issues

---

## 👤 Автор

**Sav1taRG** — pull‑requests, баг‑репорты и ⭐ приветствуются!

---

## 📄 Лицензия

GPL-3.0 © Sav1taRG
