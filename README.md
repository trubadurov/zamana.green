# Zamana Green Framework

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-green)
![License](https://img.shields.io/badge/license-MIT-blue)
![CSS](https://img.shields.io/badge/CSS-Framework-brightgreen)

**Современный HTML/CSS фреймворк для медицинских веб-платформ**

[Demo](index.html) • [Документация](DOCUMENTATION.md) • [GitHub](https://github.com/trubadurov/zamana.green)

</div>

---

## 🌟 О проекте

Zamana Green - это легковесный и профессиональный HTML/CSS фреймворк, разработанный специально для создания медицинских веб-платформ. Дизайн вдохновлен лучшими практиками современных медицинских сайтов, таких как sprosivracha.com.

### ✨ Ключевые особенности

- 🎨 **Медицинский дизайн** - профессиональная цветовая палитра (зеленые и синие оттенки)
- 📱 **Адаптивный** - работает на всех устройствах (desktop, tablet, mobile)
- ⚡ **Легковесный** - всего один CSS файл, никаких зависимостей
- 🧩 **Готовые компоненты** - карточки врачей, вопросы, формы и многое другое
- ♿ **Доступный** - семантический HTML и удобный интерфейс
- 🎯 **Простой** - понятная структура классов, легко освоить
- 🔧 **Настраиваемый** - CSS переменные для кастомизации

## 🚀 Быстрый старт

### Установка

1. **Скачайте файлы:**
   ```bash
   git clone https://github.com/trubadurov/zamana.green.git
   ```

2. **Подключите CSS:**
   ```html
   <link rel="stylesheet" href="zamana.css">
   ```

3. **Начните использовать:**
   ```html
   <button class="btn btn-primary">Задать вопрос</button>
   ```

### Базовый шаблон

```html
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Моя медицинская платформа</title>
    <link rel="stylesheet" href="zamana.css">
</head>
<body>
    <nav class="navbar">
        <div class="navbar-container">
            <a href="#" class="navbar-brand">Ваш Сайт</a>
            <ul class="navbar-menu">
                <li><a href="#home">Главная</a></li>
                <li><a href="#doctors">Врачи</a></li>
            </ul>
        </div>
    </nav>

    <section class="hero">
        <div class="container">
            <h1 class="hero-title">Добро пожаловать</h1>
            <p class="hero-subtitle">Ваш подзаголовок</p>
            <a href="#" class="btn btn-primary btn-lg">Начать</a>
        </div>
    </section>

    <!-- Ваш контент -->
</body>
</html>
```

## 📦 Компоненты

### Навигация
```html
<nav class="navbar">
    <div class="navbar-container">
        <a href="#" class="navbar-brand">Логотип</a>
        <ul class="navbar-menu">
            <li><a href="#">Главная</a></li>
        </ul>
    </div>
</nav>
```

### Кнопки
```html
<button class="btn btn-primary">Основная</button>
<button class="btn btn-secondary">Вторичная</button>
<button class="btn btn-outline">Контурная</button>
<button class="btn btn-primary btn-lg">Большая</button>
<button class="btn btn-primary btn-sm">Маленькая</button>
```

### Карточки
```html
<div class="card">
    <h3 class="card-title">Заголовок</h3>
    <p class="card-body">Контент карточки</p>
    <button class="btn btn-primary">Действие</button>
</div>
```

### Карточка врача
```html
<div class="card doctor-card">
    <img src="avatar.jpg" alt="Доктор" class="doctor-avatar">
    <h3 class="doctor-name">Иванов Иван</h3>
    <p class="doctor-specialty">Терапевт</p>
    <div class="doctor-rating">
        <span>⭐ 4.9</span>
        <span class="badge badge-success">Онлайн</span>
    </div>
    <a href="#" class="btn btn-primary">Консультация</a>
</div>
```

### Карточка вопроса
```html
<div class="question-card">
    <div class="question-header">
        <div>
            <h3 class="question-title">Вопрос</h3>
            <p class="question-meta">Имя • 2 часа назад</p>
        </div>
        <span class="question-status status-answered">Отвечено</span>
    </div>
    <p class="question-content">Текст вопроса...</p>
    <div class="question-tags">
        <span class="tag">Терапия</span>
    </div>
</div>
```

### Поиск
```html
<div class="search-container">
    <div class="search-bar">
        <input type="text" class="search-input" placeholder="Поиск...">
        <button class="search-btn">Поиск</button>
    </div>
</div>
```

### Формы
```html
<form>
    <div class="form-group">
        <label class="form-label">Имя</label>
        <input type="text" class="form-input">
    </div>
    <div class="form-group">
        <label class="form-label">Сообщение</label>
        <textarea class="form-textarea"></textarea>
    </div>
    <button type="submit" class="btn btn-primary">Отправить</button>
</form>
```

### Сетки
```html
<div class="grid grid-3">
    <div>Колонка 1</div>
    <div>Колонка 2</div>
    <div>Колонка 3</div>
</div>
```

## 🎨 Цветовая палитра

| Цвет | Код | Использование |
|------|-----|---------------|
| Primary Green | `#4CAF50` | Основной цвет действий |
| Primary Blue | `#2196F3` | Акцентный цвет |
| Light Blue | `#E3F2FD` | Фон информационных блоков |
| Light Green | `#E8F5E9` | Фон успешных блоков |
| White | `#FFFFFF` | Фон карточек |
| Light Gray | `#F5F5F5` | Основной фон |

## 📱 Адаптивность

Фреймворк автоматически адаптируется под размер экрана:

- **Desktop** (> 768px): Полный функционал с сетками
- **Tablet** (≤ 768px): Сетки в 1-2 колонки, мобильное меню
- **Mobile** (≤ 480px): Оптимизация для маленьких экранов

## 📖 Документация

Полная документация доступна в файле [DOCUMENTATION.md](DOCUMENTATION.md), где вы найдете:

- Подробное описание всех компонентов
- Примеры кода для каждого элемента
- Руководство по кастомизации
- JavaScript функции
- Лучшие практики

## 🖥️ Демо

Откройте `index.html` в браузере, чтобы увидеть все компоненты фреймворка в действии. Демо-страница включает:

- Навигацию с липким позиционированием
- Hero-секцию с поиском
- Карточки врачей
- Список вопросов и ответов
- Форму обратной связи
- Статистику
- Профессиональный footer

## 🛠️ Кастомизация

Фреймворк использует CSS переменные для легкой кастомизации:

```css
:root {
    /* Измените цвета */
    --primary-green: #your-color;
    --primary-blue: #your-color;
    
    /* Настройте отступы */
    --spacing-md: 20px;
    
    /* Измените радиусы */
    --radius-md: 10px;
}
```

## 🌐 Браузеры

Поддерживаются все современные браузеры:
- Chrome (последние 2 версии)
- Firefox (последние 2 версии)
- Safari (последние 2 версии)
- Edge (последние 2 версии)

## 📄 Структура проекта

```
zamana.green/
├── zamana.css          # Основной файл фреймворка
├── index.html          # Демо-страница с примерами
├── DOCUMENTATION.md    # Полная документация
└── README.md          # Этот файл
```

## 💡 Примеры использования

Фреймворк идеально подходит для:

- ✅ Медицинских консультационных платформ
- ✅ Сайтов клиник и больниц
- ✅ Телемедицинских сервисов
- ✅ Платформ записи к врачам
- ✅ Медицинских блогов и форумов
- ✅ Образовательных медицинских ресурсов

## 🤝 Вклад

Мы приветствуем вклад в развитие проекта! Если у вас есть идеи или вы нашли ошибку:

1. Создайте issue
2. Отправьте pull request
3. Предложите улучшения

## 📝 Лицензия

MIT License - используйте свободно в любых проектах.

## 👨‍💻 Автор

Создано для медицинских веб-платформ с вдохновением от лучших практик индустрии.

## 🙏 Благодарности

Дизайн вдохновлен современными медицинскими платформами, такими как sprosivracha.com, с фокусом на:
- Профессионализм и доверие
- Простоту использования
- Доступность для всех пользователей
- Современный и чистый интерфейс

---

<div align="center">

**Создано с ❤️ для медицинских веб-проектов**

[⬆ Наверх](#zamana-green-framework)

</div>
