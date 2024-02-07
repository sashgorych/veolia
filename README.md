
# Структура сторінок
```
<div class="content">
        <section class="breadcrumb"></section>
        --- Блок заголовку
        --- контент сторінки
</div>
```
# Блок заголовку.має 3 вигляди для різних сторінок
- текст зліва, слайдер з картинками справа (лише головна сторінка)
```
    <div class="main-p-bl1">
        <div class="main-p-bl1-in default-block">
            <div class="lft">
                <h1>Veolia в Україні</h1>
                <p>ВАШ НАДІЙНИЙ ПАРТНЕР У СФЕРІ УПРАВЛІННЯ ВІДХОДАМИ </p>
                <a href="">Дізнатись більше</a>
            </div>
            <div class="rgt">
                <div class="banner-slider banner-slider-pc">
                    <div class="slide-banner pc-slide">
                        <img src="data:image/png;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs=" data-lazy="" alt="">
                    </div>
            </div>
        </div>
    </div>
    </div>

```
- текст зліва, картинка справа (будь-яка сторінка, на вибір)
```
<div class="first-slide">
        <div class="main-p-bl1-in">
            <div class="lft">
                <h1>PAGE TITLE</h1>
                <p>PAGE SUBTITLE</p>
            </div>
            <div class="rgt">
                <img src="" alt="">
            </div>
        </div>
    </div>
```
- просто текст
```
 <div class="first-slide first-simple-slide">
        <div class="main-p-bl1-in default-block content-record">
            <div class="lft">
                <h1>PAGE TITLE</h1>
            </div>
        </div>
    </div>
```
# Акордіон ``` div.open_close_block ``` - один окремий елемент, ``` <div class="default-block addition-info-block"> ``` - обгортка
```
 <div class="default-block addition-info-block">
        <div class="open_close_block">
            <div class="o_p_ttl">
                <p>ЗАГОЛОВОК</p>
            </div>
            <div class="o_p_content">
                <div class="default-text">
                    КОНТЕНТ
                </div>
            </div>
        </div>
    </div>
```
# Структура текстової сторінки
```
<div class="content">
        <section class="breadcrumb"></section>
        --- Блок заголовку
        <div class="content-page">
            <div class="content-record default-padding default-text default-block">    
                Сюди виводити текст який ввели в адмінці
            </div>
        </div>
</div>
```
