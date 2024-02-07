# Перший блок, слайдер має 3 вигляди для різних сторінок
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
