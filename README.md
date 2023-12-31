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

Далі треба розмістити зображення в один ряд та зробити пропорційними, тож:

1. Для `.category__photos` додай `df` \-> `display: flex;` та `gap: 3%;`.
2. Тепер задай ширину зображенням у відсотках: `w65%` для `wide` та `w32%` для `square`.

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

Залишилося додати відступи:

- Для `.category__photos` постав `mb16`.
- А для `.category__title` скинь їх `m0` -> `margin: 0;`.
- Для секції `.categories`, щоб вона занадто не розтягувалася на великих екранах, обмеж `max-width: 1020px;`.
- Та відцентруй її за допомогою `margin: 0 auto;`.
- Знизу додай відступ `mb120`.

Тобі залишається додати ще два таких блоки `article` із зображеннями та заголовками. Тільки в останньому першою має бути квадратне зображення.

### Заповнюємо переваги

Крім заголовка ця секція містить список переваг та опис. Додай все що необхідно:

1. Створи `div` із класом `how-to-buy__content`.
2. У нього додай тег `ul` із класом `how-to-buy__benefits`.
3. В `ul` додай 4 теги `li`, кожен зі своїм текстом із макета.
4. Після списку `ul` додай параграф `p` із класом `how-to-buy__description` та описом.
5. Тепер для всієї секції додай клас `how-to-buy` та `dispay: flex;`, щоб поставити заголовок поруч із контентом.
6. Додай ще `gap: 24px;`, щоб трохи відсунути текст.
7. Та скопіюй обмеження ширини та центрування з `.gategories`:

```css
max-width: 1020px;
margin: 0 auto;
```

Для `.how-to-buy__title` та `.how-to-buy__content` додай `flex-basis: 50%;` — це зробить їх однаковими по ширині.

Тепер стилізуй список `.how-to-buy__benefits`:

1. Прибери кружечки `list-style: none;`.
2. Скинь відступи `m0` та `p0`.
3. Зроби текст жирним `fwb`.
4. Додай відстань між елементами:

```css
display: flex;
flex-direction: column;
gap: 16px;
```

5. Відсунь наступний блок `mb40`.

### Робимо фіксований підвал

І залишилося лише додати підвал:

1. Додай до нього клас `footer`.
2. Задай висоту `h460`.
3. Завантаж фонове зображення `images/footer-bg.png`.
4. Скопіюй параметри фону з `.header` (тільки з новим зображенням).

Далі, щоб зафіксувати фон під час прокрутки, зроби наступне:

1. Додай `position: sticky;` для `.footer`.
2. Приліпи його до нижнього краю `bottom: 0;`.
3. Та сховай під сторінку `z-index: -1;`.
4. А щоб він не просвічувався, додай для `.main` білий фон `background-color: white;`.

Тепер подивись як це працює, та знов покажи `.header` і `.menu`, якщо вони були приховані.

Твоя сторінка готова!

### Завдання

Перевір, що категорії, переваги та футер виглядають як в макеті

🔐 Додай посилання на скріншот, де будуть нові секції

Ти можеш опублікувати свій скріншот за допомогою одного з ресурсів: [snipboard](https://snipboard.io/) або [imgbb](https://imgbb.com/) або [Flameshot](https://flameshot.org/).

### Фінальний код

Ось і все, тепер ти знаєш як створюються вебсайти!

Якщо раптом щось не вийшло, ось фінальний код

Зверни увагу: ми додали цей фінальний код із метою підказки. Але перш ніж туди підглянути, спробуй написати код із відео самостійно 😉

- _default.html_
- _default.css_


## Bose - Lesson 5 — Публікуємо сторінку в Netlify

Щоб опублікувати сторінку в Internet, зареєструйся на [Netlify](https://www.netlify.com/).

Далі перейди за посиланням у листі та відповіси на запитання: `Personal`, `Personal site` та `Hobby Developer`. Натисни `Continue to Deploy`.

Тепер клікни на посилання `Skip this step for now`, ти опинишся на персональній сторінці.

Знизу треба завантажити папку з твоїм сайтом (має бути 19 файлів). Коли завантаження завершиться, натисни `Get started` і відкрий свій сайт. Вгорі буде посилання, щоб його побачити.

Вітаю! Тепер твоя сторінка розміщена в Internet 😎

Якщо захочеш щось змінити, подивись у відео, як змінити <title> сторінки або адаптувати стилі для телефонів.
