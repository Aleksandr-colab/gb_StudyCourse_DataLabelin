С сайта https://www.wildberries.ru/ соберем информацию о книгах по машинному обучению.

На сайте https://www.wildberries.ru/ найдена поисковая строка и с помощью скрипта сделан поиск 
по словам "книги машинное обучение". Реализовано прокручивание страницы, чтобы загрузились все 
товары. Далее сохранили все ссылки на книги в список и если присутствовала кнопка "Следующая страница",
то скрипт нажимал её. 

После того как были собраны все ссылки на книги, в другом окне браузера открывалась каждая ссылка и 
извлекались следующие данные:
- название
- цена
- издательство
- артикл товара на сайте
- автор
- жанр
- язык
- год издания
- обложка

Все параметры (таймауты, число пикселей прокрутки и т.д.) подбирались экспериментальным путём.

Реализация в файле [S07HW.py](https://github.com/TanXmas/gb_StudyCourse_DataLabeling/blob/master/S07/S07HW.py).  
Пример собранных данных в файле [data.csv](https://github.com/TanXmas/gb_StudyCourse_DataLabeling/blob/master/S07/data.csv) 
