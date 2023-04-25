# **Grid**
### ***01.*** *Ant-Grid*
### ***02.*** *MUI-Grid*


___ 
___

# Grid

- The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.
>> ![](https://th.bing.com/th?id=OIP.-8kz6V1-xTbUfwKrvF1ZUQHaJl&w=219&h=284&c=8&rs=1&qlt=90&o=6&dpr=1.3&pid=3.1&rm=2)


 # ***Ant-Grid***

___
- In the grid system, we define the frame outside the information area based on row and column, to ensure that every area can have stable arrangement.

Following is a brief look at how it works:

Establish a set of column in the horizontal space defined by row (abbreviated col).
Your content elements should be placed directly in the col, and only col should be placed directly in row.
The column grid system is a value of 1-24 to represent its range spans. For example, three columns of equal width can be created by <Col span={8} />.
If the sum of col spans in a row are more than 24, then the overflowing col as a whole will start a new line arrangement.
Our grid systems base on Flex layout to allow the elements within the parent to be aligned horizontally - left, center, right, wide arrangement, and decentralized arrangement. The Grid system also supports vertical alignment - top aligned, vertically centered, bottom-aligned. You can also define the order of elements by using order.

Layout uses a 24 grid layout to define the width of each "box", but does not rigidly adhere to the grid layout.

Перевод :

- В системе сетки мы определяем рамку за пределами информационной области на основе строки и столбца, чтобы гарантировать, что каждая область может иметь стабильное расположение.
- 
Установите набор столбцов в горизонтальном пространстве, определяемом строкой (сокращенно col).
Ваши элементы контента должны быть размещены непосредственно в столбце, и только столбец должен быть размещен непосредственно в строке.
Система сетки столбцов представляет собой значение от 1 до 24 для представления диапазонов диапазонов. Например, три столбца одинаковой ширины можно создать с помощью <Col span={8} />.
Если сумма кол пролетов подряд больше 24, то переполненный столбец в целом начнет новую расстановку линий.
Наши системы сетки основаны на компоновке Flex, что позволяет выравнивать элементы внутри родительского элемента по горизонтали - по левому краю, по центру, по правому краю, по широкому расположению и децентрализованному расположению. Система Grid также поддерживает вертикальное выравнивание - выравнивание по верху, по центру по вертикали, выравнивание по низу. Вы также можете определить порядок элементов с помощью order.
Макет использует макет сетки 24 для определения ширины каждого «блока», но не жестко придерживается макета сетки.

![](https://github.com/Musozoda/lecture-2/blob/main/images/grid.png)


 # ***MUI-Grid*** 
 
 ___
- The Material Design responsive layout grid adapts to screen size and orientation, ensuring consistency across layouts.
 
 Перевод : 

- Адаптивная сетка макета Material Design адаптируется к размеру и ориентации экрана, обеспечивая согласованность между макетами.








