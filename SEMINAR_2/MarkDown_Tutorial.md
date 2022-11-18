# Туториал по языку разметки MarkDown

## Работа с заголовоками


##  Работа со списками

Для создания неупорядоченных (ненумерованных) списков можно использовать или `*`, или `-`, или `+`. Например:

- элемент 1
- элемент 2
- элемент ...

Вложенные пункты создаются четырьмя пробелами перед
маркером пункта:

* элемент 1
*  элемент 2
    * вложенный элемент 2.1
    * вложенный элемент 2.2
* элемент ...

ля создания упорядоченных (нумерованных) списков необходимо проставлять цифру (любую) с точкой в начале строки. Вложенные пункты создаются четырьмя пробелами перед маркером пункта. Например:

1. элемент 1
2. элемент 2
    1. вложенный
    2. вложенный
3. элемент 3

Для создания списка с абзацами, необходимо проставлять 4 пробела или один tab в начале строки. Например:

    * Раз абзац. Lorem ipsum dolor sit amet, consectetur adipisicing elit.

    * Два абзац. Donec sit amet nisl. Aliquam semper ipsumsit amet velit. Suspendisse id sem consectetuer liber luctus adipiscing

    * Три абзац. Ea, quis, alias nobis porro quos laborumminus sed fuga odio dolore natus quas cum enim necessitatibus magni provident non saepe sequi?
 
## Работа с изображениями

бла бла воздушный шарик
чтобы добавить изображения в MarkDown, используйте следующую конструкцию:

![Альтернативный текст](https://img1.goodfon.ru/wallpaper/nbig/1/d9/cvety-priroda-leto-3724.jpg)



## Работа с таблицами 

Для того чтобы добавить таблицу в MarkDown, нужно пойти на некоторые ухищрения. Вофспользуемся разметкой GFM, пример:

First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell

Для красоты можно и по бокам линии нарисовать:

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |



Можно управлять выравниванием столбцов при помощи
двоеточия.


| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |


Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.

Для всего остального есть обычный HTML. Воспользуйтесь тегом table: 
~~~HTML
<table><td><tr></tr></td></table>
~~~

