## Счетчики покрытия
JaCoCo использует набор различных счетчиков для расчета показателей покрытия.

### Instructions
Наименьшая единица отсчета, предоставляет информацию об объеме кода, который был выполнен или пропущен.
### Branches
Метрика подсчитывает общее количество ветвей if и switch в методе и определяет количество выполненных или пропущенных ветвей. 

Состояния:
* Нет покрытия - нет ответвлений в линии (красный ромб)
* Частичное покрытие - выполнена только часть ветвей в линии (желтый ромб)
* Полное покрытие - Все ответвления в линии выполнены (зеленый ромб)
* ### Lines 
Рассчитывается информация о покрытии для отдельных строк. Исходная строка считается выполненной, если была выполнена хотя бы одна инструкция, назначенная этой строке.

Состояния:
* Нет покрытия - ни одна инструкция в строке не была выполнена (красный фон)
* Частичное покрытие - выполнена только часть инструкции в строке (желтый фон)
* Полное покрытие - все инструкции в строке выполнены (зеленый фон)



