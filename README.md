# North Brew — Landing Page

Односторінковий адаптивний сайт кав'ярні North Brew. Чистий HTML/CSS/JS, без збірки та залежностей — працює одразу після відкриття `index.html` у браузері.

## Онлайн

Після увімкнення GitHub Pages сайт буде доступний за адресою:

```
https://dokuyoba-pixel.github.io/north-brew-site/
```

## Локальний перегляд

Просто відкрийте `index.html` у браузері — жодних додаткових кроків не потрібно.

## Структура

- `index.html` — увесь сайт (розмітка, стилі, скрипти в одному файлі)
- `images/` — сюди можна покласти власні фото (див. нижче)

## Заміна фото

Зараз фото підвантажуються з Unsplash (заглушки). Щоб додати власні:

1. Покладіть файли у папку `images/` (наприклад `images/hero.jpg`)
2. У `index.html` замініть відповідний `src="https://images.unsplash.com/..."` на `src="images/hero.jpg"`

Місця з фото в коді:
- Hero — секція `.hero-media`
- «Про нас» — секція `.about-media`
- Галерея — картки `.gallery-item` (6 фото)

## Технології

- HTML5 / CSS3 (custom properties, grid, flexbox)
- Vanilla JavaScript (без фреймворків)
- Google Fonts: Fraunces, Manrope, JetBrains Mono
