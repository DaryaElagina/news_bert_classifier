# Разработка модели, классифицирующей  новости по источникам

Цель проекта: Чтобы решение о покупке акций принимала нейросеть на основе последних новостей о той или иной компании, нужно научиться классифицировать все новости. Дана база новостей из разных источников. Необходимо написать модель, классифицирующую новости по источникам.

Используемые библиотеки и инструменты: pandas, numpy, torch, transformers, sklearn,DeepPavlov_rubert-base-cased.

Ход работы: 
* Провести предобработку текста;
* Сделать предсказание для данных, где источник новостей известен. Для этого:
* Выполнить токенизацию, лемматизацию, очистку от стоп-слов и ненужных символов;
* Преобразовать текстов в эмбеддинги при помощи Bert;
* Обучить модель логистической регрессии на эмбеддингах;
* Проверить качество модели на тестовой выборке;
* Сделать предсказание для данных, где источник новостей неизвестен.

Результат:
1. Проанализирована база новостей из разных источников.
2. Выполнена очистка данных и разделение датасета на выборки.
3. Текст преобразован в эмбеддинги при помощи Bert.
4. Обучена модель логистической регрессии. Качество модели удовлетворяет заданному пороговому значению.
5. Получено предсказание источников новостей. 



