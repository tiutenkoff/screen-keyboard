# Микросайт с экранной клавиатурой

## Описание проекта:

Реализация верстки экранов микросайта c использованием роутинга, механизма ввода номера при помощи экранной клавиатуры. Кнопка "Получить" становится доступной только при верификации введенного номера и согласием с обработкой персональных данных. Разрешение микросайта фиксированное, 1280х720.

### Так же было реализовано:

- видео (отрывок около минуты длиной) и баннер, появляющийся через 5 секунд от начала проигрывания ролика (на первом экране);
- автоматическое масштабирование микросайта под любое разрешение (в соотношении 16:9);
- валидация номера при помощи открытого сервиса [numverify](https://numverify.com/documentation).

## Использованные технологии и инструменты:

![React + хуки + router](https://img.shields.io/badge/-React+hooks+router-282727?style=for-the-badge)
<br>![TypeScript](https://img.shields.io/badge/-TypeScript-282727?style=for-the-badge)
<br>![numverify](https://img.shields.io/badge/-numverify-282727?style=for-the-badge)
<br>![SCSS](https://img.shields.io/badge/-SCSS-282727?style=for-the-badge)

---

## Перед запуском необходимо:

1. Установить Node.js:

   [Установить Node.js (ссылка)](https://nodejs.org/en/)

2. Обновить пакеты:

```
$ npm i
```

---

## Запуск проекта:

- Запуск локального сервера:

```
$ yarn start (npm start)
```