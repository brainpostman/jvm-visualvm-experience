На картинке:
Сначала идет подгрузка классов (графики Classes и Metaspace) по строчкам 1, 2 и 3.  

При создании объекта класса SimpleObject также подгружается еще один класс (стрелка 456).  

При подгрузке классов происходит инициализация cтатических полей, под которые выделяется память в хипе (на графике Heap стрелки 1, 2, 3).  

Затем при создании непосредственно объектов класса SimpleObject выделяется память в хипе (строчки и стрелки 4, 5, 6 на графике Heap).