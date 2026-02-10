# Zamana Green Framework - Документация

## О фреймворке

Zamana Green - это легковесный HTML/CSS фреймворк для создания медицинских веб-платформ. Разработан с учетом лучших практик UI/UX дизайна медицинских сайтов, таких как sprosivracha.com.

## Особенности

- 🎨 Профессиональная медицинская цветовая палитра (зеленые и синие оттенки)
- 📱 Полностью адаптивный дизайн (mobile-first подход)
- ⚡ Легковесный - всего один CSS файл
- 🧩 Готовые компоненты для медицинских платформ
- ♿ Доступный и удобный интерфейс
- 🚀 Простая интеграция - подключите один файл

## Быстрый старт

### 1. Установка

Скачайте `zamana.css` и подключите к вашему проекту:

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
    <!-- Ваш контент -->
</body>
</html>
```

### 2. Использование компонентов

Просто используйте классы из фреймворка:

```html
<button class="btn btn-primary">Задать вопрос</button>
<div class="card">
    <h3 class="card-title">Заголовок</h3>
    <p>Содержимое карточки</p>
</div>
```

## Компоненты

### Навигация (Navbar)

Создайте профессиональную навигацию с липким позиционированием:

```html
<nav class="navbar">
    <div class="navbar-container">
        <a href="#" class="navbar-brand">Ваш Логотип</a>
        <button class="navbar-toggle" onclick="toggleMenu()">☰</button>
        <ul class="navbar-menu" id="navMenu">
            <li><a href="#home">Главная</a></li>
            <li><a href="#doctors">Врачи</a></li>
            <li><a href="#contact" class="btn btn-primary btn-sm">Контакт</a></li>
        </ul>
    </div>
</nav>
```

### Кнопки

Различные стили кнопок для разных целей:

```html
<!-- Основная кнопка -->
<button class="btn btn-primary">Основная</button>

<!-- Вторичная кнопка -->
<button class="btn btn-secondary">Вторичная</button>

<!-- Контурная кнопка -->
<button class="btn btn-outline">Контурная</button>

<!-- Размеры -->
<button class="btn btn-primary btn-lg">Большая</button>
<button class="btn btn-primary">Обычная</button>
<button class="btn btn-primary btn-sm">Маленькая</button>
```

### Карточки (Cards)

Универсальный компонент для отображения контента:

```html
<div class="card">
    <div class="card-header">
        <h3 class="card-title">Заголовок карточки</h3>
    </div>
    <div class="card-body">
        <p>Основной контент карточки</p>
    </div>
    <div class="card-footer">
        <button class="btn btn-primary">Действие</button>
    </div>
</div>
```

### Карточки врача

Специализированный компонент для профилей врачей:

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

### Карточки вопросов

Компонент для отображения вопросов пациентов:

```html
<div class="question-card">
    <div class="question-header">
        <div>
            <h3 class="question-title">Заголовок вопроса</h3>
            <p class="question-meta">
                <span>Имя, возраст</span> • 
                <span>2 часа назад</span>
            </p>
        </div>
        <span class="question-status status-answered">Отвечено</span>
    </div>
    <p class="question-content">
        Текст вопроса...
    </p>
    <div class="question-tags">
        <span class="tag">Терапия</span>
        <span class="tag">Температура</span>
    </div>
</div>
```

### Поисковая строка

Элегантная поисковая строка с кнопкой:

```html
<div class="search-container">
    <div class="search-bar">
        <input type="text" class="search-input" placeholder="Поиск...">
        <button class="search-btn">Поиск</button>
    </div>
</div>
```

### Формы

Компоненты для создания форм:

```html
<form>
    <div class="form-group">
        <label class="form-label">Имя</label>
        <input type="text" class="form-input" placeholder="Введите имя">
    </div>
    
    <div class="form-group">
        <label class="form-label">Сообщение</label>
        <textarea class="form-textarea" placeholder="Ваше сообщение"></textarea>
    </div>
    
    <button type="submit" class="btn btn-primary">Отправить</button>
</form>
```

### Бейджи и статусы

Индикаторы статуса:

```html
<span class="badge badge-success">Успех</span>
<span class="badge badge-info">Информация</span>
<span class="badge badge-warning">Предупреждение</span>
```

### Алерты

Информационные блоки:

```html
<div class="alert alert-success">Успешное сообщение</div>
<div class="alert alert-info">Информационное сообщение</div>
<div class="alert alert-warning">Предупреждение</div>
```

### Сетка (Grid System)

Адаптивная система сеток:

```html
<!-- 2 колонки -->
<div class="grid grid-2">
    <div>Колонка 1</div>
    <div>Колонка 2</div>
</div>

<!-- 3 колонки -->
<div class="grid grid-3">
    <div>Колонка 1</div>
    <div>Колонка 2</div>
    <div>Колонка 3</div>
</div>

<!-- 4 колонки -->
<div class="grid grid-4">
    <div>Колонка 1</div>
    <div>Колонка 2</div>
    <div>Колонка 3</div>
    <div>Колонка 4</div>
</div>
```

На мобильных устройствах сетка автоматически переключается в одну колонку.

### Контейнеры

Ограниченная ширина контента:

```html
<!-- Контейнер с максимальной шириной 1200px -->
<div class="container">
    Контент
</div>

<!-- Контейнер на всю ширину -->
<div class="container-fluid">
    Контент
</div>
```

### Секции

Структурирование страницы:

```html
<section class="section">
    <div class="container">
        <h2 class="section-title">Заголовок секции</h2>
        <p class="section-subtitle">Подзаголовок секции</p>
        <!-- Контент -->
    </div>
</section>
```

### Hero секция

Главный баннер страницы:

```html
<section class="hero">
    <div class="container">
        <h1 class="hero-title">Заголовок</h1>
        <p class="hero-subtitle">Подзаголовок</p>
        <a href="#" class="btn btn-primary btn-lg">Действие</a>
    </div>
</section>
```

### Подвал (Footer)

Профессиональный футер:

```html
<footer class="footer">
    <div class="container">
        <div class="footer-grid">
            <div class="footer-section">
                <h3>О нас</h3>
                <p>Описание</p>
            </div>
            <div class="footer-section">
                <h3>Ссылки</h3>
                <ul>
                    <li><a href="#">Ссылка 1</a></li>
                    <li><a href="#">Ссылка 2</a></li>
                </ul>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2026 Ваша компания</p>
        </div>
    </div>
</footer>
```

## Утилиты

### Выравнивание текста

```html
<div class="text-center">Центр</div>
<div class="text-left">Слева</div>
<div class="text-right">Справа</div>
```

### Отступы

Margin (внешние отступы):
```html
<div class="mt-sm">margin-top: small</div>
<div class="mt-md">margin-top: medium</div>
<div class="mt-lg">margin-top: large</div>
<div class="mt-xl">margin-top: extra-large</div>

<div class="mb-sm">margin-bottom: small</div>
<div class="mb-md">margin-bottom: medium</div>
<div class="mb-lg">margin-bottom: large</div>
<div class="mb-xl">margin-bottom: extra-large</div>
```

Padding (внутренние отступы):
```html
<div class="pt-sm">padding-top: small</div>
<div class="pt-md">padding-top: medium</div>
<div class="pt-lg">padding-top: large</div>
<div class="pt-xl">padding-top: extra-large</div>

<div class="pb-sm">padding-bottom: small</div>
<div class="pb-md">padding-bottom: medium</div>
<div class="pb-lg">padding-bottom: large</div>
<div class="pb-xl">padding-bottom: extra-large</div>
```

## Цветовая палитра

### Основные цвета

- **Primary Green** (`--primary-green`): #4CAF50 - основной зеленый
- **Primary Blue** (`--primary-blue`): #2196F3 - основной синий
- **Light Blue** (`--light-blue`): #E3F2FD - светло-синий фон
- **Light Green** (`--light-green`): #E8F5E9 - светло-зеленый фон

### Нейтральные цвета

- **White** (`--white`): #FFFFFF
- **Light Gray** (`--light-gray`): #F5F5F5
- **Gray** (`--gray`): #9E9E9E
- **Dark Gray** (`--dark-gray`): #424242
- **Text Dark** (`--text-dark`): #212121

### Статус цвета

- **Success** (`--success`): #4CAF50 - успех
- **Warning** (`--warning`): #FF9800 - предупреждение
- **Error** (`--error`): #F44336 - ошибка
- **Info** (`--info`): #2196F3 - информация

## CSS переменные

Фреймворк использует CSS переменные для легкой кастомизации:

```css
:root {
    /* Цвета */
    --primary-green: #4CAF50;
    --primary-blue: #2196F3;
    
    /* Отступы */
    --spacing-sm: 8px;
    --spacing-md: 16px;
    --spacing-lg: 24px;
    --spacing-xl: 32px;
    
    /* Радиусы */
    --radius-sm: 4px;
    --radius-md: 8px;
    --radius-lg: 12px;
    
    /* Тени */
    --shadow-sm: 0 1px 2px rgba(0, 0, 0, 0.05);
    --shadow-md: 0 4px 6px rgba(0, 0, 0, 0.1);
    --shadow-lg: 0 10px 15px rgba(0, 0, 0, 0.1);
}
```

### Кастомизация

Вы можете переопределить переменные в своем CSS:

```css
:root {
    --primary-green: #your-color;
    --spacing-md: 20px;
}
```

## Адаптивный дизайн

Фреймворк адаптируется к разным размерам экрана:

- **Desktop**: > 768px - полный функционал
- **Tablet**: 768px и меньше - сетки становятся в 1 колонку
- **Mobile**: 480px и меньше - уменьшенные размеры элементов

### Контрольные точки

```css
/* Планшет и меньше */
@media (max-width: 768px) {
    /* Стили для планшета */
}

/* Мобильные устройства */
@media (max-width: 480px) {
    /* Стили для мобильных */
}
```

## JavaScript функции

Для полной функциональности добавьте эти скрипты:

### Переключение мобильного меню

```javascript
function toggleMenu() {
    const menu = document.getElementById('navMenu');
    menu.classList.toggle('active');
}

// Закрытие меню при клике вне его
document.addEventListener('click', function(event) {
    const navbar = document.querySelector('.navbar');
    const menu = document.getElementById('navMenu');
    
    if (!navbar.contains(event.target) && menu.classList.contains('active')) {
        menu.classList.remove('active');
    }
});
```

### Плавная прокрутка

```javascript
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            target.scrollIntoView({
                behavior: 'smooth',
                block: 'start'
            });
        }
    });
});
```

## Примеры использования

### Страница с вопросами

```html
<section class="section">
    <div class="container">
        <h2 class="section-title">Вопросы пациентов</h2>
        
        <div class="question-card">
            <div class="question-header">
                <div>
                    <h3 class="question-title">Вопрос о здоровье</h3>
                    <p class="question-meta">
                        <span>Пациент, 30 лет</span> • 
                        <span>1 час назад</span>
                    </p>
                </div>
                <span class="question-status status-answered">Отвечено</span>
            </div>
            <p class="question-content">Текст вопроса...</p>
            <div class="question-tags">
                <span class="tag">Терапия</span>
            </div>
        </div>
    </div>
</section>
```

### Профили врачей

```html
<section class="section">
    <div class="container">
        <h2 class="section-title">Наши специалисты</h2>
        
        <div class="grid grid-3">
            <div class="card doctor-card">
                <img src="doctor.jpg" alt="Доктор" class="doctor-avatar">
                <h3 class="doctor-name">Доктор Иванов</h3>
                <p class="doctor-specialty">Терапевт</p>
                <div class="doctor-rating">
                    <span>⭐ 4.9</span>
                    <span class="badge badge-success">Онлайн</span>
                </div>
                <a href="#" class="btn btn-primary">Консультация</a>
            </div>
            <!-- Больше врачей -->
        </div>
    </div>
</section>
```

## Лучшие практики

1. **Используйте семантический HTML** - `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`
2. **Оптимизируйте изображения** - используйте правильные форматы и размеры
3. **Добавьте alt-теги** - для доступности
4. **Тестируйте на разных устройствах** - проверяйте адаптивность
5. **Используйте CSS переменные** - для легкой кастомизации

## Поддержка браузеров

- Chrome (последние 2 версии)
- Firefox (последние 2 версии)
- Safari (последние 2 версии)
- Edge (последние 2 версии)

## Лицензия

MIT License - используйте свободно в коммерческих и некоммерческих проектах.

## Поддержка

Если у вас есть вопросы или предложения:
- Создайте issue на GitHub
- Отправьте pull request с улучшениями

## Обновления

**Версия 1.0.0** (2026)
- Первый релиз
- Полный набор компонентов для медицинских платформ
- Адаптивный дизайн
- Доступность

---

Создано с ❤️ для медицинских веб-платформ
