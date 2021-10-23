# HW08_CourseProject

![sentiment-analysis](https://github.com/cLamik/HW08_CourseProject/blob/main/sentiment-analysis.jpg)

## Анализ тональности рецензий фильмов
Проект выполнен в рамках курсового проекта в OTUS, курс [Machine Learning. Professional](https://otus.ru/lessons/machinelearning/?int_source=courses_catalog&int_term=data-science "Machine Learning. Professional")

## Исходные данные / Сбор данных
В качестве исходных данных для проекта брались рецензии оставленные на различные фильмы сайта [kinopoisk](https://www.kinopoisk.ru/ "kinopoisk") (именно фильмы, без сериалов и мультфильмов).

**[course_project_parser_ids](https://github.com/cLamik/HW08_CourseProject/blob/main/course_project_parser_ids.ipynb "course_project_parser_ids")** - парсер id фильмов kinopoisk-а. Требовалось сначала собрать данные по id фильмам, т.к. если брать числа просто по порядку, то часто попадаешь на несуществующие страницы сайта.

**[course_project_parser](https://github.com/cLamik/HW08_CourseProject/blob/main/course_project_parser.ipynb "course_project_parser")** - непосредственно парсер рецензий фильмов.

**[course_project_union](https://github.com/cLamik/HW08_CourseProject/blob/main/course_project_union.ipynb "course_project_union")** - т.к. парсер запускался несколько раз, то требовалось потом объединить данные в один **[датасет](https://disk.yandex.ru/d/rIhPG_s7QJ4FMg "comments_full")**.

## EDA + Topic modeling

**[course_project_eda](https://github.com/cLamik/HW08_CourseProject/blob/main/course_project_eda.ipynb "course_project_eda")** - EDA данных.

**[course_project_topic_modeling_v1](https://github.com/cLamik/HW08_CourseProject/blob/main/course_project_topic_modeling_v1.ipynb "course_project_topic_modeling_v1")** - Topic modeling визуализация v1.

**[course_project_topic_modeling_v2](https://github.com/cLamik/HW08_CourseProject/blob/main/course_project_topic_modeling_v2.ipynb "course_project_topic_modeling_v2")** - Topic modeling визуализация v2.

## Анализ

**[course_project_nltk_all](https://github.com/cLamik/HW08_CourseProject/blob/main/course_project_nltk_all_v2.ipynb "course_project_nltk_all")** - анализ тональности рецензий фильмов (все типы рецензий: положительные, отрицательные, нейстральные) с использованием библиотеки nltk + LogisticRegression.

**[course_project_nltk_bad_good](https://github.com/cLamik/HW08_CourseProject/blob/main/course_project_nltk_bad_good_v2.ipynb "course_project_nltk_bad_good")** - анализ тональности рецензий фильмов (с двумя типами рецензий: положительные, отрицательные) с использованием библиотеки nltk + LogisticRegression.

**[course_project_bert_all](https://github.com/cLamik/HW08_CourseProject/blob/main/course_project_bert_all.ipynb "course_project_bert_all")** - применение BERT для анализа тональности рецензий (все типы рецензий: положительные, отрицательные, нейстральные).

**[course_project_bert_bad_good](https://github.com/cLamik/HW08_CourseProject/blob/main/course_project_bert_bad_good.ipynb "course_project_bert_bad_good")** - применение BERT для анализа тональности рецензий (с двумя типами рецензий: положительные, отрицательные).

## Дополнительный материал

**[stopwords-ru](https://github.com/stopwords-iso/stopwords-ru "stopwords-ru")** - использовались также стоп-слова из данного проекта.
