# High Heels by Lada - Сайт танцевальной студии

Элегантный одностраничный сайт для преподавателя танцев High Heels в Санкт-Петербурге.

## 📁 Структура файлов

```
├── index.html          # Главная страница
├── styles.css          # Стили сайта
└── images/            # Папка для изображений (создайте)
    └── lada.jpg       # Ваше фото
```

## 🚀 Как выложить на GitHub Pages

### Шаг 1: Создайте репозиторий
1. Зайдите на [github.com](https://github.com)
2. Нажмите **New repository**
3. Назовите его: `high-heels-lada` (или любое другое имя)
4. Выберите **Public**
5. Нажмите **Create repository**

### Шаг 2: Загрузите файлы
1. Нажмите **uploading an existing file**
2. Перетащите файлы:
   - `index.html`
   - `styles.css`
3. Нажмите **Commit changes**

### Шаг 3: Загрузите изображение
1. Создайте папку `images` в репозитории
2. Загрузите ваше фото как `lada.jpg`
3. Или замените путь к фото в `index.html`:
   ```html
   <!-- Найдите эту строку и измените путь -->
   <img src="/mnt/user-data/uploads/photo_5228986236523976287_y__1_.jpg" 
   <!-- На эту -->
   <img src="images/lada.jpg"
   ```

### Шаг 4: Активируйте GitHub Pages
1. Перейдите в **Settings** → **Pages**
2. В разделе **Source** выберите **main** branch
3. Нажмите **Save**
4. Через 1-2 минуты ваш сайт будет доступен по адресу:
   `https://ваш-username.github.io/high-heels-lada/`

## ⚙️ Что нужно настроить

### 1. Замените ID формы для popup
В файле `index.html` найдите:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```
Зарегистрируйтесь на [formspree.io](https://formspree.io) и вставьте свой ID.

### 2. Обновите ссылки для шеринга
Найдите в `index.html`:
```html
<a href="https://vk.com/share.php?url=YOUR_URL"
```
Замените `YOUR_URL` на URL вашего сайта.

### 3. Добавьте Google Analytics (опционально)
Найдите:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-XXXXX-X"></script>
```
Замените `UA-XXXXX-X` на ваш ID из Google Analytics.

## 📱 Контакты

- Instagram: [@olaadik_](https://www.instagram.com/olaadik_)
- Telegram: [@lamariyazg](https://t.me/lamariyazg)
- Адрес: СПб, Чкаловский проспект 15Г, студия Jonathan Dance

## 🎨 Технологии

- HTML5
- CSS3 (с переменными и современными эффектами)
- Vanilla JavaScript (без фреймворков)
- Адаптивный дизайн
- SEO-оптимизация

## 📝 Лицензия

© 2024 High Heels by Lada. Все права защищены.
