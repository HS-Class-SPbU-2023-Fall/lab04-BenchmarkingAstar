# lab04-BenchmarkingAstar

Лабортная делается в Jupyter Notebook, при этом заготовки нет (имеет смысл пользоваться тем, что вы сдедали в рамках 2-й и 3-й лабы).

Основная цель лабы - научится проводить массовые сравнительные тесты алгоритмов эвристического поиска.

Для этой лабы необходимо провести тестирование различных версий A* для задачи планирования **на 8-связном гриде без срезания углов**.

4.1. Версия A* = A* + эвристика + (опциально) tie-breaking.

4.2. Эвристики для тестирования: Евклид, Диагональная (Octile distance), Чебышев, Манхэетен (недопустимая эвристика для 8-связного случая).

Для тестирования необходимо использовать коллекцию данных MovingAI (https://movingai.com/benchmarks/grids.html).


5.1. В тестирование должно быть включено не менее 3 карт из различных коллекций (3 карт с визуально различной топологией).

5.2. Для каждой карты должно быть использовано не менее 100 заданий различной сложности

5.3. Для лучшего понимания устройства коллекции MovinaAI рекомендуется ознакомиться со статьей (ссылка есть на сайте)

Должны (как минимум) отслеживаться следующие индикаторы: успешность решения задания (алгоритм нашел кратчайший путь или нет), число раскрытий, время работы алгоритма.

6.1. Необходимо представить результаты экспериментов в аггрегированном виде (в видео графиков и/либо таблиц). Плюсом будет представление не только усредненных значений, но и показателей разброса.

6.2. Тетрадка должна содержать текстовую ячейку с объяснением experimental setup (какие карты и задаиня вы выбрали, почему, какие индикаторы отслеживались, как читать таблицы/графики) и анализом трендов.

PS: Чем более наглядные картинки и описание - тем лучше!
