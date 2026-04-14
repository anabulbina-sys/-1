# lab-1
Описание проделанной работы

00_distance.py
Вычисление расстояний между городами
Программа рассчитывает расстояния между тремя городами (Москва, Лондон, Париж) по их координатам. Используется формула Евклидова расстояния. Результат сохраняется в виде вложенного словаря, где для каждой пары городов указано расстояние с округлением до двух знаков после запятой.
Результат: <img width="782" height="43" alt="image" src="https://github.com/user-attachments/assets/155b8faf-2518-4e8f-8a8b-1d8df9839941" />


01_circle.py
Площадь круга и проверка принадлежности точек
Программа вычисляет площадь круга с заданным радиусом и проверяет, лежат ли две точки внутри этого круга. Центр круга находится в начале координат (0, 0). Для расчётов используется значение π ≈ 3.1415926. Результаты выводятся с точностью до 4 знаков.
Результат: <img width="94" height="63" alt="image" src="https://github.com/user-attachments/assets/c8be9018-2dfe-4aea-a8b2-1cc6dbc09885" />


02_operations.py
Расстановка математических знаков
Задача: расставить знаки +, -, * и скобки между числами 1, 2, 3, 4, 5 так, чтобы получить 25. Порядок чисел сохраняется. Решение: 1 * (2 + 3) + 4 * 5 = 25.
Результат: <img width="30" height="38" alt="image" src="https://github.com/user-attachments/assets/ca996833-8a68-438d-b514-c116c27a601f" />


03_favorite_movies.py
Извлечение подстрок с помощью срезов
Из строки с перечислением фильмов с помощью только срезов (без использования .split() и других методов) извлекаются:
первый фильм
последний фильм
второй фильм
второй фильм с конца
Результат: <img width="120" height="69" alt="image" src="https://github.com/user-attachments/assets/3f2080bc-68bd-4799-8440-7366ebafff6f" />


04_my_family.py
Список семьи и рост членов семьи
Создаётся список членов семьи и вложенный список с именами и ростом. Программа выводит рост отца и общий рост всех членов семьи путём сложения значений из вложенных списков.
Результат: <img width="227" height="38" alt="image" src="https://github.com/user-attachments/assets/53951890-5fb5-48f7-92a7-a69599d61646" />


05_zoo.py
Управление списком животных в зоопарке
Операции со списком zoo:
вставка медведя между львом и кенгуру
добавление списка птиц в конец
удаление слона
вывод номеров клеток (для человека, с единицы) для льва и жаворонка
Результат: <img width="594" height="94" alt="image" src="https://github.com/user-attachments/assets/6853780b-8deb-483c-a941-5f5b0be29751" />


06_songs_list.py
Подсчёт времени звучания песен
Даны два формата хранения данных: список списков и словарь. Программа вычисляет общее время звучания:
для списка: песни 'Halo', 'Enjoy the Silence', 'Clean'
для словаря: песни 'Sweetest Perfection', 'Policy of Truth', 'Blue Dress'
Результаты округляются согласно заданию.
Результат: <img width="618" height="47" alt="image" src="https://github.com/user-attachments/assets/6ce11703-770c-46f2-9fc3-6987f17c4a33" />


07_secret.py
Расшифровка секретного сообщения
Зашифрованная фраза хранится в виде списка строк. По заданному ключу (номера букв, срезы с шагом, обратный порядок) извлекаются буквы и составляется осмысленная фраза на русском языке.
Результат: <img width="77" height="93" alt="image" src="https://github.com/user-attachments/assets/9844d0e6-e89f-4484-a53c-e535269f74bf" />


08_garden.py
Операции с множествами: сад и луг
Из кортежей с повторяющимися названиями цветов создаются множества. Выполняются операции:
объединение (все виды цветов)
пересечение (растут и там, и там)
разность (только в саду / только на лугу)
Результат: <img width="679" height="81" alt="image" src="https://github.com/user-attachments/assets/b2b001f0-e605-4542-9e4c-a5919b44ebca" />


09_shopping.py
Поиск минимальных цен на сладости
Из словаря с ценами в трёх магазинах для каждой сладости вручную выбираются два магазина с самыми низкими ценами. Результат оформлен в виде вложенного словаря.
Результат: <img width="1603" height="36" alt="image" src="https://github.com/user-attachments/assets/d850a7ef-f0ec-417c-bf4a-cff4d8bf9882" />


10_store.py
Учёт товаров на складе (ручной расчёт)
По кодам товаров из одного словаря находятся партии товаров в другом словаре. Для каждого товара вручную (без циклов) суммируется количество и общая стоимость всех партий. Результат выводится в формате: Товар - X шт, стоимость Y руб.
Результат: <img width="251" height="91" alt="image" src="https://github.com/user-attachments/assets/277b590a-5bc5-4258-8d83-61869493fd37" />


Шпаргалку по работе с командами git 

Ссылки на используемые материалы
Словари: https://docs.python.org/3/tutorial/datastructures.html#dictionaries
Метод dict.items(): https://docs.python.org/3/library/stdtypes.html#dict.items
Dict comprehensions: https://docs.python.org/3/tutorial/datastructures.html#dictionaries 
Функция round(): https://docs.python.org/3/library/functions.html#round
W3Schools Python Dictionaries: https://www.w3schools.com/python/python_dictionaries.asp
Real Python — словари в Python: https://realpython.com/python-dicts/
Евклидово расстояние: https://ru.wikipedia.org/wiki/Евклидова_метрика
малоизвестных возможностей стандартной библиотеки Python:
https://proglib.io/p/7-maloizvestnyh-vozmozhnostey-standartnoy-biblioteki-python-2024-08-27
