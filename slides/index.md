---
marp: true
paginate: true
size: 16:9
transition: pull
header: '<span class="nordic">Фронтенд vs. бэкенд</span>'
title: "Разработка для начинающих: фронтенд vs. бэкенд @inordic.ru"
_paginate: false
_header: ""
_class: imageLeft
---

<!-- _class: titular -->

# Разработка для начинающих: фронтенд vs. бэкенд

---

<!-- _class: author -->
<div class="author-card">
    <img width="150" src="./assets/vbifonix.png" />
    <div class="author-text">
        <span class="author-name">Михаил Кононенко</span>
        <span class="author-tg"><a href="https://t.me/vbifonix"><i class="icon-send"></i>@vbifonix</a></span>
        <span class="author-resume">
            Фронтенд-разработчик в <img src="assets/joom_logo.svg" height="18px" style="margin-bottom: -3px;" />
        </span>
    </div>
</div>

<div class="author-card">
    <img width="150" src="./assets/timofey.png" />
    <div class="author-text">
        <span class="author-name">Тимофей Житков</span>
        <span class="author-tg"><a href="https://t.me/timondecathlon"><i class="icon-send"></i>@timondecathlon</a></span>
        <span class="author-resume">
            Senior Fullstack-разработчик в <img src="assets/mb_logo.png" height="18px" style="margin-bottom: -3px;" />
        </span>
    </div>
</div>

---

![bg](assets/microwave_guy.png)
<!-- _transition: fade .1s -->

---
<!-- _transition: fade .1s -->

![bg](assets/not_a_microwave_guy.png)

---

![bg](assets/office_people.png)

---

![w:900px](assets/horrible_website.webp)

---

![w:900px](assets/ozon.png)

---

![w:900px](assets/ymaps.png)

---

![w:900px](assets/gmeet.png)

---

![](assets/alfabank.png)

---

<!-- _transition: fade .1s -->

![two devices](assets/web/0.png)

---
<!-- _transition: fade .1s -->

![with routing](assets/web/1.png)

---
<!-- _transition: fade .1s -->

![with more routing](assets/web/2.png)

---
<!-- _transition: fade .1s -->

![with provider](assets/web/3.png)

---
<!-- _transition: fade .1s -->

![with servers](assets/web/4.png)

---
<!-- _transition: fade .1s -->

![with dns request](assets/web/5.png)

---
<!-- _transition: fade .1s -->

![browser](assets/browser/0.png)

---
<!-- _transition: fade .1s -->

![browser](assets/browser/1.png)

---
<!-- _transition: fade .1s -->

![browser](assets/browser/2.png)

---
<!-- _transition: fade .1s -->

![browser](assets/browser/3.png)

---
<!-- _transition: fade .1s -->

![browser](assets/browser/4.png)

---

<!-- _transition: fade .1s -->

![browser](assets/browser/5.png)

---
<!-- _transition: fade .1s -->

![alt text](assets/browser/6.png)

---
<!-- _transition: fade .1s -->

![browser](assets/browser/7.png)

---
<!-- _transition: fade .1s -->

![browser](assets/browser/8.png)

---
<!-- _transition: fade .1s -->

![browser](assets/browser/9.png)

---
<!-- _transition: fade .1s -->

![browser](assets/browser/10.png)

---

<!-- _transition: fade .1s -->

![browser](assets/browser/11.png)

---
<!-- _transition: fade .1s -->

![browser](assets/mobile_app.png)

---

![bg](assets/shaking.png)

---

# За что платят фронтендеру?

---

![w:850](assets/figma_layout.png)

<!-- _footer: '[Metoric Sales Analytics от Barly Design @ dribble](https://dribbble.com/shots/24801899-Metoric-Sales-Analytics)' -->

---
<!-- Кроме того, что контент показался - важно, чтобы можно было заказать сырную шавуху -->
![](assets/eda_order.webp)

---
<!-- Оживляем интерфейс -->
<button class="scared animated" onclick="javascript:(() => {let a = document.querySelector('.scared'); a.innerText = 'ЛАДНО НЕ БУДУ'; a.classList.add('away'); setTimeout(() => a.remove(), 5000)})()">ДА НЕ ТРЯСИСЬ ТЫ</button>

---

![](assets/animation_design.webp)

---
<!-- Адаптивная вёрстка -->
![alt text](assets/responsive.png)

---

![alt text](assets/mcqueen.png)

---

![with servers](assets/cdn.png)

---
![alt text](assets/webvitals.png)
<!-- _footer: '[Web Vitals](https://web.dev/articles/vitals?hl=ru)' -->

---

![alt text](assets/accessibility.png)
<!-- Один мой знакомый занимается веб-разработкой даже несмотря на то, что лишился зрения -->
<!-- _footer: '[Сайт социального фонда России](https://sfr.gov.ru)' -->

---

![alt text](assets/superbusy.png)

<!-- _footer: '[Super busy UI @ dribble.com](https://dribbble.com/shots/15347979-Super-busy-UI)' -->

---

![alt text](assets/shield.png)

---

![alt text](assets/wordle.png)

<!-- _footer: '[Wordle по-русски](https://wordle.belousov.one)' -->

---

![alt text](assets/seo.png)

---

# За что платят бэкендеру?

---

<!-- _class: backend -->

* `Хранение и обработка данных`
* `API для веб- и мобильных приложений`
* `Эффективные алгоритмы`
* `Безопасность данных и компании`
* `Масштабируемость и отказоустойчивость`

---

# Как?

<span style="font-size: 0.5em">(frontend эдишен)</span>

---
<!--
- Три кита веб-разработки
- Javascript - это язык программирования, который выполняется в браузере.
- HTML - что показывается
- CSS - как выглядит
- JS - как оно себя ведёт
-->

![w:500](./assets/whales.png)

* ![w:80](assets/html.png) - Что показывается на странице
* ![w:80](assets/css.png) - Как оно выглядит
* ![w:80](assets/js.png) - Как оно себя ведёт

---

![browsers_desktop](assets/image-4.png)
![browsers](assets/image-3.png)

---

# HTML

```html
<!DOCTYPE html>
<html lang="ru">
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
    </head>
    <body>
        <h1 class="heading">Привет, мир!</h1>
        <p class="paragraph">Этот текст может ничего не значить...</p>
    </body>
</html>
```

---

![html example](assets/html_screenshot.png)

---

# CSS

```css
.heading {
    color: #850;
    font-size: 32px;
}

.paragraph {
    background-color: #f1c40f;
    border-radius: 8px;
}
```

---

![css](assets/css_screenshot.png)

---

# JS

```js
let a = document.querySelector('.scared');
a.innerText = 'ой всё';
a.classList.add('away');

setTimeout(
    () => a.remove(),
    5000
)
```

---

<button class="scaredToo" onclick="javascript:(() => {let a = document.querySelector('.scaredToo'); a.innerText = 'ой всё'; a.classList.add('away'); setTimeout(() => a.remove(), 5000)})()">Я на грани</button>

---
![roadmap](assets/frontend-1.png)

<!-- _footer: '[Frontend Development Roadmap @ roadmap.sh](https://roadmap.sh/frontend)' -->

---

![alt text](assets/is-odd.png)

<!-- _footer: '[is-odd @ npmjs.org](https://www.npmjs.com/package/is-odd)' -->

---

![alt text](assets/vue-react.png)

---

![technologies](assets/tech.png)

---

<!-- _class: backend -->

# Как?

<span style="font-size: 0.5em">(backend эдишен)</span>

---

<!-- _class: backend -->

# [`https://roadmap.sh/backend`](https://roadmap.sh/backend)

---

# Остальные навыки

---

# Технические (hard skills)

* Редактор или IDE - рекомендация начинающим - [Visual Studio Code](https://aka.ms/vscode)
* Git и хранение исходного кода
* UNIX (shell) - умение работать в операционной системе
* Технические подробности устройства интернета
* Развёртывание приложений
* Автоматизация (в том числе сборки и развёртывания)
* Понимание своей сферы - методологии, фреймворки, хорошие практики

---

# Ещё технические, но уже не совсем

* Умение гуглить, читать документацию, задавать (в меру) глупые вопросы и применять новые знания
* Логическое мышление
* Алгоритмы и структуры данных (в основном на собеседованиях)
* Чистота, читаемость кода. Архитектура проекта
* Код-ревью

---

# Нетехнические (soft skills)

* Критика - как воспринимать, так и давать
* Компромиссы
* Понимание проблем. Зачем это всё?
* Процессы в команде и компании

---

# Карьера

---

<!-- _class: rotatingImg -->
# Предпочтения

![](assets/thinking.png)

---

# Перспективы

![w:400](assets/intern.png)

---
![alt text](assets/bogatyri.png)

---

![lead](assets/lead-and-manager.png)

---

<!-- _class: screaming -->

![bg](assets/huell.png)

# Зарплаты

---

![alt text](assets/front-intern.png)

<!-- _footer: '[Хабр Карьера](https://career.habr.com/salaries?locations%5B%5D=c_678&qualification=Intern&spec_aliases%5B%5D=frontend)' -->
---

![alt text](assets/back-intern.png)

<!-- _footer: '[Хабр Карьера](https://career.habr.com/salaries?locations%5B%5D=c_678&qualification=Intern&spec_aliases%5B%5D=backend)' -->

---

![alt text](assets/fullstack.png)

---

# Работодатели

---

* Маркетинговые агенства
* Аутсорс/аутстафф
* Продуктовая компания
* Стартап
* Не-айти компания

---

# Как выбрать путь?

---

# Как изучать?

---

Будущим фронтендерам рекомендую для самостоятельного изучения:

- [Frontend Development Roadmap @ roadmap.sh](https://roadmap.sh/frontend)
- <https://stepik.org/course/38218/promo> бесплатный курс по HTML/CSS от моего товарища на stepik
- <https://learn.javascript.ru> - учебник по javascript
- <https://karmazzin.gitbook.io/eloquentjavascript_ru> - ещё один учебник по javascript

---

#### Cпасибо&excl;

<!-- _class: author screaming -->
<div class="author-card">
    <img width="150" src="./assets/vbifonix.png" />
    <div class="author-text">
        <span class="author-name">Михаил Кононенко</span>
        <span class="author-tg"><a href="https://t.me/vbifonix"><i class="icon-send"></i>@vbifonix</a></span>
        <span class="author-resume">
            Фронтенд-разработчик в <img src="assets/joom_logo_white.svg" height="18px" style="margin-bottom: -3px;" />
        </span>
    </div>
</div>

<div class="author-card">
    <img width="150" src="./assets/timofey.png" />
    <div class="author-text">
        <span class="author-name">Тимофей Житков</span>
        <span class="author-tg"><a href="https://t.me/timondecathlon"><i class="icon-send"></i>@timondecathlon</a></span>
        <span class="author-resume">
            Senior Fullstack-разработчик в <img src="assets/mb_logo_white.png" height="18px" style="margin-bottom: -3px;" />
        </span>
    </div>
</div>
