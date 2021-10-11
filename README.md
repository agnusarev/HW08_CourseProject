# HW08_CourseProject

## Анализ тональности рецензий фильмов
Проект выполнен в рамках курсового проекта в OTUS, курс [Machine Learning. Professional](https://otus.ru/lessons/machinelearning/?int_source=courses_catalog&int_term=data-science "Machine Learning. Professional")

## Исходные данные
В качестве исходных данных для проекта брались рецензии оставленные на различный фильмы сайта kinopoisk (именно фильмы, без сериалов и мультфильмов).

**course_project_parser_ids** - парсер id фильмов kinopoisk-а. Требовалось сначала собрать данные по id фильмам, т.к. если брать числа просто по порядку, то попадаешь на несуществующие страницы сайта.

**course_project_parser** - непостредственно парсер рецензий фильмов.

**course_project_union** - т.к. пасер запускался несколько раз, то требовалось потом объединить данные в один датасет.
