# prac_nn_1

Моя нейросеть - фактически обученный ResNet50V2 с накинутым сверху двумя полносвязными слоями на 256 и 9 выходами соответственно.  Достигнутый accuracy на полном тестовом датасете - 0.9707 \
Для обучения я использовал 0.75 часть большого датасета, т.к. коллаб больше не пережевал((((( \
LBL-1 Валидация модели на части обучающей выборки \
LBL-3 Автоматическое сохранение модели \
LBL-5 Вывод различных показателей в процессе обучения \
Не знаю, можно ли это считать моей наработко, потому что оно все выводится автоматически \
LBL-8 построение матрицы ошибок, специфичности и чувствительности модели \
LBL-11 Аугментация данных \
LBL-12 Наверно, сохранение каждые 25 итераций, вместо с load и train, это возможность дообучения
