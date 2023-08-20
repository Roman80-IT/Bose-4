## Bose - Lesson 4 — Завершуємо сторінку

Ну що, залишилося зовсім небагато, тож зовсім скоро ти зможеш поділитися своїми успіхами!

### Додаємо категорії із зображеннями
Наступний блок категорій також містить 3 блоки із зображеннями та заголовками. Тож додамо структуру:

1. Завантаж зображення `Headphones-earbuds-wide` та `Headphones-earbuds-square` в папку `images/categories`.
2. Додай тег `article` з класом `category`.
3. Усередину встав `div` із класом `category__photos`.
4. І `h3` з класом `category__title` та текстом `Headphones & earbuds`.
5. Тепер всередину `category__photos` встав 2 зображення з класами `photo-wide` та `photo-square` відповідно.
6. В атрибут `alt` для обох пропиши назву категорії.
7. Далі треба розмістити зображення в один ряд та зробити пропорційними, тож:

```css
.category__photos {
    display: flex;
    gap: 3%;
}
.photo-wide {
    width: 65%;
}
.photo-square {
    width: 32%;
}
```



### Завдання

Заповни картки товарів даними з макету

Завантаж та використай відповідні зображення

🔐 Додай посилання на скріншот, де буде твоя секція з рекомендованими товарами.

Ти можеш опублікувати свій скріншот за допомогою одного з ресурсів: [snipboard](https://snipboard.io/) або [imgbb](https://imgbb.com/) або [Flameshot](https://flameshot.org/).

### Фінальний код уроку
Зверни увагу: ми додали цей фінальний код із метою підказки. Але перш ніж туди підглянути, спробуй написати код із відео самостійно 😉

- *default.html*
- *default.css*
