<div id="header" align="center">
  <img src="https://boomboxpilot.ru/wp-content/uploads/8/6/a/86a4d7b1a8eae29af13187b2c1438a74.jpeg" width="700"/>
</div>

# Music genre classification project 

## Описание проекта  

**Задача проекта**  
Классификация музыкальных треков по жанрам. 

В нашем распоряжении датасет с описанием музыкальных треков. Данные взяты с сайта [Kaggle.com](https://www.kaggle.com/), ссылка на страничку датасета: [Prediction of music genre](https://www.kaggle.com/datasets/vicsuperman/prediction-of-music-genre/data?select=music_genre.csv).  

Датасет представляет собой табличные данные формата csv.  
Описание колонок:  
- instance_id (уникальное ID для каждого трека);  
- признаковое описание:  
    - artist_name;  
    - track_name;  
    - popularity;  
    - acousticness;  
    - danceability;  
    - duration_ms;  
    - energy;  
    - instrumentalness;  
    - key;  
    - liveness;  
    - loudness;  
    - mode;  
    - speechiness;  
    - tempo;  
    - obtained_date;  
    - valence;  
- music_genre (целевая переменная).    

Всего записей в датасете 50005.  

Целевая переменная имеет 10 значений классов (музыкальных жанров): 'Electronic', 'Anime', 'Jazz', 'Alternative', 'Country', 'Rap', 'Blues', 'Rock', 'Classical', 'Hip-Hop'.  

Этапы выполнения проекта:  
- загрузка данных и библиотек;  
- предобработка и исследовательский анализ данных;
- исследование моделей;  
- тестирование лучшей модели;  
- анализ важности признаков для лучшей модели;  
- общий вывод по проекту.
