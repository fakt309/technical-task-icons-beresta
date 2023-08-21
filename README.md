# Техническое задание
![preview](https://github.com/fakt309/technical-task-icons-beresta/assets/43887554/f994240e-daca-40dc-b795-9f51e1c20ad3)

## Краткое описание
Нужно перерисовать иконки в svg формате (всего 43 примерно, но некоторые похожие), некоторые из них анимированые (около 20 штук).

## Предистория
Я пишу приложение [beresta.app](https://beresta.app), своими силами я отрисовал каждую иконку, в целом получилось неплохо, но нету какой-то единой концепции.  
А некоторые из них получились совсем убогими (что меня и подтолкнуло в конечном итоге к аутсорсу).  
По сути тут все что нужно сделать, это заного перерисовать все иконки вашими профессиональными рукими, чтобы была какая-то единая концепция всех иконок прослежиловался единый стиль.

## Требования к картинкам
- Тонкие линии (сейчас они 2px можно примерно также или возможно посмотреть вариант с 1px)
- Обязательно svg формат (анимированные тоже)
- Цвет везде только белый (#ffffff) кроме отдельных картинок, которые лежат в папке `colored`

---
---
---
---
---

## Полное описание
Нужно перерисовать все картинки, которые находятся в папке `assets` (другие папки не трогаем, они нужны только для справки и понимания общего контекста задания)  
Не обязательно полностью менять все картинки, например там где крестик, так и оставляем крестик, просто делаем его более красивым подгоняем под единый стиль. Но в некоторых местах возможно нужно полностью заменить иконку на что-то новое. Зависит от видение автора.

---
---

### assets/icons
То что находиться в папке `assets/icons` это иконки, которые чаще всего используются в кнопках (не анимированные, кроме `loading.svg`).
Скрины где они используются есть в папке `explanation/desktop` (1.png-4.png) и `explanation/phone` (1.png-5.png). Можно также самому зайти на сайт [beresta.app](https://beresta.app) и просмотреть.  
Все эти иконки должны быть только белого цвета, кроме загрузки не анимрованные.

---
---

### assets/colored/flags
Ну здесь все очень просто. Это разноцветные иконки флагов двух стран: америка и россия. В принципе сейчас меня полностью устраивает как они выглядят, только не нравится их размер. Американский флаг какой-то квадратный, а российский прямоугольный. Нужно сделать их по размерам как российский сейчас.

---
---

### assets/colored/stickers
![1](https://github.com/fakt309/technical-task-icons-beresta/assets/43887554/9ecb8f06-c37c-4484-b957-8fcfba6b999f)
Вот здесь проявляется основной талант художника. Здесь 4 картиноки. Примеры использования также есть `explanation/phone` (6.png-9.png). **Они все должны быть анимированные зацикленные, цветные, красочные, но также чтобы не сливались с коричневым фоном (#473C33).** Хочется что-то типо стикеров в телеграме.
Стиль flat примерно такой как на картинке выше.  
По каждой картинке отдельно напишу что хотелось бы видеть.

#### assets/colored/stickers/flashCamera.svg
Здесь должна быть камера, типо снимок, которая фотогрофирует и из неё вылетает свет.

#### assets/colored/stickers/gotostages.svg
Здесь должна быть человек, в одежде, который поднимается по лесинкам вид с боку как в 2d игре. Нужно проприсовать руки с пальцами и лицо, нормальное. Не так как сейчас просто палки.

#### assets/colored/stickers/screeneye.svg
Здесь тот же человек поднимает свой телефон, желательно закос под google pixel и делает снимок. Также как и сейчас оставить, только прорисовать все детальнее: одежду, лицо, руки, норм телефон, и т. д.

#### assets/colored/stickers/stars.svg
![2](https://github.com/fakt309/technical-task-icons-beresta/assets/43887554/630c8c1d-6eac-4686-9269-3533301c63e9)

Здесь нужно вообще полностью поменять картинку на конфети, как в стикере телеграм. Сейчас эти убогие звездочки, это самое худшее что я нарисовал. Нужно просто сделать стикер из телеграма, только в своем стиле. Пример выше.

---
---

### assets/tutorial
![3](https://github.com/fakt309/technical-task-icons-beresta/assets/43887554/01283985-8221-4929-9c13-b7c045b1bd18)

Ну и последняя папка это `assets/tutorial`. Это картинки которые используются для обучалки. Здесь всего 4 картинки в 4 вариантах. Для русского и английского. Для десктопной версии и для мобильного. Все должно выглядеть по анимации также как и сейчас, единственное иконки нужно заменить на те, котрые будут новые прерисованные. Все текста и весь контент остаётся таким же. Используем только белый цвет на коричневом фоне (#473C33).  
По сути это анимации 4 шагов которые нужно сделать: создать заметку, отметить как выполнено, отметить как отменено, перетащить заметку.  
**И ЕЩЕ ОДИН ВАЖНЫЙ МОМЕНТ**: данные картинки нужно обернуть в рамку телефона(закос под google pixel 7 pro) и в рамку десктопного монитора.  
**И ЕЩЕ ОДИН ВАЖНЫЙ МОМЕНТ**: курсор мыши нужно перерисовать на более аккуратный, сейчас это как-то не оч выглядит.  
**И ЕЩЕ ОДИН ВАЖНЫЙ МОМЕНТ**: Палец, который используется в мобильном варианте - не годиться. Нужно сделать полностью руку которая обхватывает телефон. слева видны 4 пальца и большой палец справа, который водит по экрану. Типо как на картинке выше.
