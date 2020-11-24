# TvTropesMovieData

[Итоговый файл с данными](https://raw.githubusercontent.com/slowwavesleep/TvTropesMovieData/main/data/tropes_movie_data_final.csv)

## Описание данных

- `tropes_title` — название фильма на tvtropes.org (из url)
- `tropes` — список тропов данного фильма в виде строки (элементы разделены символом `|`)
- `imdb_id` — идентификатор фильма на IMDB
- `imdb_genres` — список жанров фильма на IMDB в виде строки 
- `movielens_id` — идентификатор фильма в датасете Movielens
- `tmdb_id` — идентификатор фильма на The Movie Database
- `movielens_title` — название фильма в датасете movielens
- `movielens_genres` — список жанров фильма в датасете Movielens в виде строки (элементы разделены символом `|`)
- `movielens_year` — год фильма, извлечённый из названия в датасете Movielens

Разделитель столбцов: `,`.

## Пропуски в данных
Не все идентификаторы IMDB существуют в датасете Movielens. В этих случаях `movielens_id` имеет значение `99999999`.

## Использованные библиотеки
- Список тропов собран с помощью [tropescraper](https://github.com/raiben/tropescraper)
- Идентификаторы IMDB получены с помощью поиска через [IMDbPY](https://imdbpy.github.io/)

## Использованные данные
- [MovieLens](https://grouplens.org/datasets/movielens/)
- IMDB Datasets(https://www.imdb.com/interfaces/)
