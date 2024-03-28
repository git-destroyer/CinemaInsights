# Анализ Данных Фильмов с IMDb и Reddit

## Описание проекта

Проект посвящен анализу данных о фильмах с использованием открытых данных IMDb и информации о популярности фильмов на платформе Reddit. Цель проекта - выявить тренды и предпочтения аудитории, а также понять, как различные характеристики фильма (жанр, год выпуска, рейтинг) влияют на его популярность в интернете.

## Исходные данные

В проекте используются следующие наборы данных:

- `title.basics.tsv` и `title.rating.tsv` из открытых данных IMDb ([ссылка на источник](https://developer.imdb.com/non-commercial-datasets/)), содержащие информацию о названиях фильмов, их жанрах, годах выпуска и рейтингах.
- `df_2015_2020_5000_with_reddit.xlsx` и `df_2015_2020_5000_with_reddit_imdb.xlsx` - обработанные данные, объединяющие информацию IMDb с данными о количестве постов на Reddit, связанных с каждым фильмом.

## Структура проекта

Проект включает в себя следующие этапы работы с данными:

1. **Загрузка и первичная оценка данных**: Импорт данных из источников и оценка их структуры и полноты.
2. **Предобработка данных**: Очистка, трансформация и подготовка данных к анализу.
3. **Разведочный анализ данных (EDA)**: Статистический анализ и визуализация данных для выявления основных тенденций и закономерностей.
4. **Глубокий анализ данных**: Сравнительный анализ фильмов по жанрам и годам выпуска, анализ изменения интереса к фильмам со временем на основе данных Reddit.
5. **Выводы**: Подведение итогов анализа, обсуждение ключевых находок и ограничений исследования.

Весь аналитический процесс выполнен в Jupyter Notebook с использованием языка программирования Python и библиотек для анализа данных (Pandas, Matplotlib, Seaborn).

## Инструкции по использованию

Для запуска анализа необходимо:

1. Склонировать репозиторий с проектом:
   ```bash
   $ git clone https://github.com/git-destroyer/CinemaInsights.git 
   ```
2. Скачать `title.basics.tsv.gz` и `title.rating.tsv.gz` по [ссылке](https://datasets.imdbws.com/)
3. Извлечь `title.basics.tsv` и `title.basics.tsv` в репозиторий.
4. Открыть Jupyter Notebook `Итоговый_проект- Фам Тхэ Ань.ipynb` и выполнить код по шагам.

## Лицензия

Данные IMDb предоставляются для личного и некоммерческого использования в соответствии с условиями, указанными на сайте [IMDb](https://developer.imdb.com/non-commercial-datasets/). Все аналитические материалы и код являются открытыми и распространяются под лицензией MIT.
