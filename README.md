# goit-advancedjs-hw-05
# Критерії приймання

- Створено репозиторій `goit-advancedjs-hw-05`.
- Домашня робота містить посилання на робочу сторінку на `GitHub Pages`.
- До роботи прiкрiплено файл репозиторiю у форматi `zip`.
- Коректно налаштоване середовище розробки.
- Коректно налаштований компілятор.
- Встановлено source maps в tsconfig.json у проєкті TypeScript.

#### Формат оцінювання:

- Оцінка від 0 до 100

#### Формат здачi:

- Посилання на робочу сторінку на `GitHub Pages`
- Прикрiплений файл репозиторію у форматi `zip`

## Завдання

Потрібно встановити та налаштувати середовище розробки. Усі детальні кроки
описані в роздiлах конспекту 4-6.

#### Короткий опис дій:

1. Створи репозиторій на GitHub під назвою goit-advancedjs-hw-05.
2. Налаштуй середовище розробки (Тема 9.4 “Встановлення та налаштування
   середовища розробки”).
3. Налаштуй компілятор (Тема 9.5 “Налаштування компілятора”).
4. Встанови source maps в tsconfig.json у проєкті TypeScript для налагодження
   коду у браузері (Тема 9.6 “Debugging”).

### TypeScript init

- npm install -g typescript
- tsc --init
- tsc
- tsc -w
- npm init -y
- npm i --save-dev @web/dev-server

` "scripts": { "start": "web-dev-server --node-resolve --open --watch" },`

- npm start