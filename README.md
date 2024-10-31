В этом задании вы будете работать с различными типами событий и обработчиков в
JavaScript.
Все задачи решайте внутри тега script.
Дан HTML:

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Homework 5</title>
</head>

<body>
    <p class="super_element">Привет</p>
    <img src="https://placeimg.com/50/50/animals" alt="">
    <img src="https://placeimg.com/50/50/arch" alt="">
    <img src="https://placeimg.com/50/50/nature" alt="">
    <img src="https://placeimg.com/50/50/people" alt="">
    <img src="https://placeimg.com/50/50/tech" alt="">
    <img src="https://placeimg.com/50/50/tech/grayscale" alt="">
    <img src="https://placeimg.com/50/50/tech/sepia" alt="">
    <br>
    <button>Кнопка</button>
    <button class="super_element">Кнопка с классом btn</button>
    <button>Кнопка</button>
    <br>
    <textarea></textarea>
    <br>
    <ul>
        <li>
            <button>Кнопка 1</button>
        </li>
        <li>
            <button>Кнопка 2</button>
        </li>
        <li>
            <button>Кнопка 3</button>
        </li>
        <li>
            <button>Кнопка 4</button>
        </li>
    </ul>
</body>

</html>
```

Задачи:

1. Необходимо вывести сообщение в консоль "все теги прогрузились", когда все
теги будут созданы браузером.
2. Необходимо вывести сообщение в консоль "страница загрузилась", когда все
ресурсы страницы будут загружены.
3. При клике на какой-либо тег на странице в консоль должно выводиться
сообщение следующего вида:
- Класс "super_element" присутствует в элементе "div".
- Сообщение должно определять присутствует ли класс "super_element" у
элемента и выводить в нижнем регистре верный тег в данной строке, по
которому был совершен клик.
- Необходимо использовать делегирование.
4. Сделайте так, чтобы при наведении на textarea в консоли появлялось
сообщение: "Вы навели на textarea."
5. Необходимо повесить событие клика на тег ul. В обработчике события в
консоль выводите текст, который записан внутри элемента кнопки, по которой
был произведен клик. Если клик был не по кнопке, то ничего выводить не нужно.
Необходимо использовать делегирование.
6. Вопрос: Почему в console.log сначала пишется текст из 5 задания и только
потом текст из 3 задания, если мы кликаем по кнопкам в ul? Ответ
необходимо написать здесь же, под этим комментарием, своими словами.
7. С помощью JS необходимо изменить цвет заднего фона каждого второго тега li.