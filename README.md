# АНАЛИЗ СОВРЕМЕННЫХ САЙТОВ
## ЛАБОРАТОРНАЯ РАБОТА №10 по дисциплине «Веб-технологии»
**Выполнила**: Студентка группы 241-671 Кротова С.В.

### 1. Анализ сайтов и свойств
#### 1.1 Подборка сайтов

1. [AGIMA](https://ratingruneta.ru/redirect/?url=http%3A%2F%2Fwww.agima.ru&rating=%2Fweb%2F1-200%2F&from=agency) – сайт, специализирующийся на веб-разработке, цифровом маркетинге, создании и развитии сайтов и веб-приложений.
2. [KODIX](https://ratingruneta.ru/redirect/?url=https%3A%2F%2Fkodix.ru%2F&rating=%2Fweb%2F1-200%2F&from=agency) – разработка программного обеспечения, мобильных приложений, веб-сайтов, CRM-систем и интеграционных решений.
3. [Extyl](https://ratingruneta.ru/redirect/?url=https%3A%2F%2Fwww.extyl-pro.ru%2F%3Futm_source%3Dcmsmagazine%26utm_medium%3Drating%26utm_campaign%3Dcmsmagrating&rating=%2Fweb%2F1-200%2F&from=agency) –  веб-разработка, разработка мобильных приложений, дизайн и цифровой маркетинг
4. [ADV](https://ratingruneta.ru/redirect/?url=http%3A%2F%2Fwww.adv.ru&rating=%2Fweb%2F1-200%2F&from=agency) –  рекламное агентство, цифровой маркетинг, медиапланирование, креатив и PR.
5. [Оджетто](https://ratingruneta.ru/redirect/?url=http%3A%2F%2Fwww.oggetto.ru&rating=%2Fweb%2F1-200%2F&from=agency) – маркетинговое агентство, брендинг, цифровой маркетинг, веб-разработка и дизайн.
6. [Студия Олега Чулакова](https://ratingruneta.ru/redirect/?url=http%3A%2F%2Fchulakov.ru&rating=%2Fweb%2F1-200%2F&from=agency) – дизайн-студия, веб-разработка, брендинг, создание мобильных приложений и интерактивных интерфейсов.
7. [Perx](https://ratingruneta.ru/redirect/?url=https%3A%2F%2Fwww.perx.ru%2F&rating=%2Fweb%2F1-200%2F&from=agency) – цифровой партнер для автомобильного бизнеса, специализирующийся на создании уникальных цифровых продуктов для производителей автомобилей и дилерских сетей.
8. [Promo Interactive](https://ratingruneta.ru/redirect/?url=http%3A%2F%2Fpromo.ru&rating=%2Fweb%2F1-200%2F&from=agency) – маркетинговое агентство, создание сайтов, цифровой маркетинг, performance-маркетинг и брендинг.
9. [Art. Lebedev Studio](https://ratingruneta.ru/redirect/?url=https%3A%2F%2Fwww.artlebedev.ru%2F%3Futm_source%3Dcmsrr21%26utm_medium%3Dlink%26utm_campaign%3Dcmsrr21&rating=%2Fweb%2F1-200%2F&from=agency) – дизайн-студия, брендинг, промышленный дизайн, веб-разработка, графический дизайн и архитектура.
10. [Only](https://ratingruneta.ru/redirect/?url=https%3A%2F%2Fonly.digital%2F&rating=%2Fweb%2F1-200%2F&from=agency) –  цифровое агентство, разработка мобильных приложений, веб-разработка, SEO, SMM и performance-маркетинг.

#### 1.2 Свойства


Сайт	|  CSS-Свойство	  |  Описание	  |   Пример применения
1.agima.ru|	`clip-path`	|  Создает обтравочную маску для элементов, позволяя отображать только определенную часть элемента.  |	`clip-path: polygon(50% 0%, 100% 50%, 50% 100%, 0% 50%)`; для создания ромбовидной формы изображения.
2.kodix.ru|	`mask-image`|  	Позволяет использовать изображение в качестве маски, создавая нестандартные формы элементов.|  	`mask-image: url("mask.svg")`; для придания изображению формы маски.
3.extyl-pro.ru|  	`text-wrap: balance`|  	Улучшает читаемость длинных текстов, равномерно распределяя строки и избегая коротких строк.|  	`text-wrap: balance`; для равномерного переноса строк в длинном тексте.
4.adv.ru| 	`scroll-timeline`|  Позволяет создавать анимации, привязанные к прокрутке страницы, позволяя элементу появляться с анимацией.| 	`animation-timeline: view()`; для привязки анимации к прокрутке.
5.oggetto.ru| 	`text-indent` (отрицательное)| 	Позволяет «выдвинуть» первую строку текста за пределы элемента, создавая интересный визуальный эффект.| 	`text-indent: -20px`; для вынесения первой строки текста.
6.chulakov.ru| 	`contain-intrinsic-size`|  	Задаёт «внутренний» размер элемента при использовании `contain: size`, что полезно для оптимизации.| 	`contain-intrinsic-size: 200px 100px`; для определения размера элемента с `contain: size`.
7.promo.ru|  	`border-image-source` с градиентом| 	Позволяет использовать градиент в качестве источника для рамки, создавая стильные эффекты.| 	`border-image-source: linear-gradient(to right, red, blue)`; для рамки с градиентом.
8.artlebedev.ru| 	`shape-image-threshold`| 	Определяет пороговое значение прозрачности для обтекания текста с помощью `shape-outside`, обеспечивая более точную настройку обтекания.|  	`shape-image-threshold: 0.5`; для точной настройки обтекания вокруг прозрачного изображения.
9.Only.ru| 	`text-decoration-line: overline underline`| 	Позволяет одновременно задать подчеркивание и линию над текстом для создания декоративных эффектов.|  	`text-decoration-line: overline underline`; для создания подчеркивания и линии над текстом.

### 2. Структура сайта

#### 2.1 Структура сайта [KODIX](https://ratingruneta.ru/redirect/?url=https%3A%2F%2Fkodix.ru%2F&rating=%2Fweb%2F1-200%2F&from=agency):

1. **Шапка (header):**
    - Содержит логотип, основное меню навигации, кнопки для связи и переключения языка.
    - Основные элементы:
        <header class="header">
        <div class="header__logo"> – Логотип компании.
        <nav class="header__nav"> – Основное меню навигации.
        <ul class="nav__list">
        <li class="nav__item"> – Пункты меню.
        <div class="header__contacts"> – Контактные кнопки (например, “Заказать звонок”).
        <div class="header__lang"> - Кнопки выбора языка.


1. **Основная часть (main):**
    - Включает разделы с информацией о компании, услугах, портфолио, кейсах, технологиях и блоге.
    - Основные элементы:
        <main class="main-content">
        <section class="hero"> – Главный блок, представление компании и ее экспертизы.
        <section class="about-us"> – Информация о компании и ее ценностях.
        <section class="services"> – Раздел с перечнем услуг, предоставляемых компанией.
        <section class="portfolio"> – Раздел с примерами работ и кейсами.
        <section class="technologies"> - Раздел с описанием технологий.
        <section class="blog"> – Раздел с блог-статьями и новостями компании.
        <section class="contact-form"> - Раздел с формой обратной связи.


1. **Подвал (footer):**
    - Содержит дополнительную навигацию, контактные данные, ссылки на социальные сети и информацию о компании.
    - Основные элементы:
        <footer class="footer">
        <div class="footer__nav"> – Дополнительное меню (ссылки на основные разделы).
        <ul class="footer-nav__list">
        <li class="footer-nav__item"> – Пункты меню.
        <div class="footer__contacts"> - Контактная информация (адрес, телефон, email).
        <div class="footer__social"> - Ссылки на социальные сети.


1. **Меню:**
    - Основное меню располагается в шапке сайта и при прокрутке остается прикрепленным к верхней части экрана.
    - Реализация:
        - Используется `position: sticky;` или `position: fixed;` для фиксации меню в верхней части страницы при прокрутке.
        - Стилизация:
            - `.header__nav { position: sticky; top: 0; width: 100%; background-color: #fff; z-index: 100;}` - для прикрепления шапки.
        -Пункты меню выровнены горизонтально с использованием Flexbox:
            - `.nav__list { display: flex; justify-content: space-around; }` или `justify-content: flex-start;` и другие варианты выравнивания.


#### 2.2 Анализ кода:

- **Методология именования классов:**
    - На сайте также прослеживается использование методологии, похожей на [БЭМ (Блок, Элемент, Модификатор)](https://ru.bem.info/), хотя это может быть нестрогое соответствие БЭМ. Например, мы видим классы вида: `header__logo`, `nav__list`, `footer__contacts` и т.д.
    - Имена классов достаточно информативны и позволяют понять, за что отвечает тот или иной элемент. Встречаются классы вида: `section-title`, `service-item__title`, что также помогает понять их назначение.


- **Использование HTML5-тегов:**
    - Активно используются семантические теги HTML5, такие как: `<header>`, `<main>`, `<section>`, `<footer>`, `<nav>`.
    - Также используются теги `<article>` и `<aside>`, где это уместно. Это улучшает семантику сайта и его доступность для поисковых систем и людей с ограниченными возможностями.


- **Использование оберток `<div>`:**
  - `<div>` используется для группировки элементов внутри семантических тегов, что является стандартной практикой. 
  - Количество оберток `<div>` оптимально и не создает избыточной вложенности.


- **Понятность исходного кода:**
    - Код достаточно чистый и понятный благодаря использованию семантических тегов HTML5 и осмысленных названий классов.
    - Структура кода логична, что способствует его легкому пониманию и поддержке.
    - Разделение на компоненты (шапка, основная часть, подвал) делает код более модульным.
    - Встречается использование комментариев в HTML и CSS, что также помогает поддерживать код.


**Вывод:**
    - Сайт KODIX разработан с использованием современных веб-технологий и методологий. Код достаточно чистый и структурированный, что обеспечивает хорошую производительность, удобство для пользователей и упрощает поддержку. Использование семантических тегов HTML5, структурирование классов и осмысленная организация кода свидетельствуют о профессиональном уровне разработки.


### 3. Реализация блока

1. **Создайте семантический элемент `<footer>`:**
   - Вставьте тег `<footer>` в конец вашего HTML-документа, перед закрывающим тегом `</body>`.
   ```html
   <footer>
   </footer>
   ```

2. **Внутри <footer> создайте контейнер div с классом footer__inner для выравнивания содержимого.**
    ```html
    <div class="footer__inner">
    ```

3. **Создайте контейнер div с классом footer__nav для дополнительного меню.**
    ```html
    <div class="footer__nav">
    ```

4. **Внутри footer__nav создайте список ul с классом footer-nav__list. Для каждого пункта меню создайте li с классом footer-nav__item и ссылкой <a>.**
    ```html
    <ul class="footer-nav__list">
                <li class="footer-nav__item"><a href="#">Услуги</a></li>
                <li class="footer-nav__item"><a href="#">Портфолио</a></li>
                <li class="footer-nav__item"><a href="#">О компании</a></li>
                <li class="footer-nav__item"><a href="#">Блог</a></li>
                <li class="footer-nav__item"><a href="#">Контакты</a></li>
            </ul>
    ```


5. **Создайте контейнер div с классом footer__contacts для контактной информации. Добавьте элементы для адреса, телефона и электронной почты.**
    ```html
     <div class="footer__contacts">
            <p>Адрес: г. Москва, ул. Пример, д. 10</p>
            <p>Телефон: +7 (495) 123-45-67</p>
            <p>Email: info@kodix.ru</p>
        </div>
    ```


6. **Создайте контейнер div с классом footer__social для ссылок на социальные сети. Внутри добавьте ссылки <a> на социальные сети.**
    ```html
     <div class="footer__social">
            <a href="#" class="footer__social-link">VK</a>
            <a href="#" class="footer__social-link">Facebook</a>
            <a href="#" class="footer__social-link">Instagram</a>
        </div>
    ```


7. **Создайте контейнер div с классом footer__legal для юридической информации и копирайта. Внутри добавьте текст с информацией.**
    ```html
     <div class="footer__legal">
            <p>&copy; 2023 Kodix. Все права защищены.</p>
        </div>
    ```


8. **Задайте базовые стили для контейнера <footer>: фон, цвет текста, отступы.**
    ```css
    .footer {
    background-color: #333;
    color: #fff;
    padding: 20px 0;
    font-size: 0.9rem;
}


9. **Задайте стили для контейнера footer__inner: максимальная ширина, выравнивание.**
    ```css
    .footer__inner {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 0 20px;
}


10. **Стилизуйте контейнер footer__nav: отступы. Стилизуйте список ul.footer-nav__list и элементы li.footer-nav__item: убираем маркеры, выравниваем.**
    ```css
    .footer__nav {
    margin-bottom: 15px;
}
```css
    .footer-nav__list {
        list-style: none;
        padding: 0;
        display: flex;
    }

    .footer-nav__item {
        margin-right: 15px;
    }
    .footer-nav__item a {
    text-decoration: none;
    color: #fff;
}
```  

11. **Стилизуйте контейнер footer__contacts: отступы.**
    ```css
    .footer__contacts {
    margin-bottom: 15px;
}
 

12.  **Стилизуйте контейнер footer__social и ссылки footer__social-link: отступы, цвет.**
    ```css
    .footer__social {
        margin-bottom: 15px;
    }
    .footer__social-link {
        margin-right: 10px;
        color: #fff;
        text-decoration: none;
    }


13. **Стилизуем контейнер footer__legal.**
    ```css
    .footer__legal {
  text-align: center;
    width: 100%;
}



14. **Размещаем элементы в одну строку с помощью flex:**
    ```css
    .footer__inner {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  padding: 0 20px;
}



15. **Добавим ховер эффекты для ссылок в навигации и социальных сетях:**
    ```css
    .footer-nav__item a:hover, .footer__social-link:hover {
    text-decoration: underline;
}



16. **Используйте медиа-запросы для адаптации подвала под разные экраны.**
    ```css
    @media (max-width: 768px) {
  .footer__inner {
    flex-direction: column;
    align-items: center;
      text-align: center;
  }
    .footer__nav {
        margin-bottom: 10px;
    }
    .footer-nav__list {
        flex-direction: column;
        align-items: center;
    }
  .footer-nav__item {
    margin-bottom: 5px;
      margin-right: 0;
  }

  .footer__social {
     margin-bottom: 10px;
      text-align: center;
  }
}



**Итоговый результат:**
![Подвал kodix.ru](c:\Users\Сергей\OneDrive\Pictures\Screenshots\подвал_кодикс.png)


### Список интернет-ресурсов
1. **[HTML Academy](https://htmlacademy.ru/blog)**  
   **Тип ресурса:** Блог

2. **[CSS-Tricks](https://css-tricks.com/)**  
   **Тип ресурса:** Тематический сайт

3. **[A List Apart](https://alistapart.com/)**  
   **Тип ресурса:** Тематический сайт

4. **[Smashing Magazine](https://www.smashingmagazine.com/)**  
   **Тип ресурса:** Тематический сайт

5. **[WebReference](https://www.webreference.com/)**  
   **Тип ресурса:** Тематический сайт

6. **[HTML5 Doctor](http://html5doctor.com/)**  
   **Тип ресурса:** Тематический сайт

7. **[Learn CSS Layout](http://learnlayout.com/)**  
   **Тип ресурса:** Учебный сайт

8. **[CSS Wizardry](https://csswizardry.com/)**  
   **Тип ресурса:** Блог

9. **[Codrops](https://tympanus.net/codrops/)**  
   **Тип ресурса:** Тематический сайт

10. **[Web Design Weekly](https://web-design-weekly.com/)**  
    **Тип ресурса:** Блог

**Как использую:**  Я ищу информацию и статьи о HTML-тегах, CSS-свойствах и правилах оформления кода на различных сайтах.
