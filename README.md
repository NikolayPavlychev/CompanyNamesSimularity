Задача построения поискового движка

Baseline

1. Препроцессинг данных - чистка и нормализация
2. Обучение skipgram-эмбеддингов и вычисление эмбеддингов названий компаний
3. Вычисление попарного косинусного расстояния
3. Undersampling по 3600 примеров на каждый класс
3. Обучение классификатора на базе логистической регрессии 

Метрика : f1-score на тестовой выборке

              precision    recall  f1-score   support

           0       0.93      0.91      0.92      1087
           1       0.91      0.93      0.92      1073

    accuracy                           0.92      2160
   macro avg       0.92      0.92      0.92      2160
weighted avg       0.92      0.92      0.92      2160


Performance : Обучение эмбеддингов 26 s

Альтернативные подходы.

sentence-transformers/distiluse-base-multilingual-cased-v2

Метрика : f1-score на тестовой выборке


              precision    recall  f1-score   support

           0       0.92      0.91      0.92      1087
           1       0.91      0.92      0.92      1073

    accuracy                           0.92      2160
   macro avg       0.92      0.92      0.92      2160
weighted avg       0.92      0.92      0.92      2160

Performance : Обучение эмбеддингов 48 s

sentence-transformers/paraphrase-multilingual-MiniLM-L12-v2

Метрика : f1-score на тестовой выборке

              precision    recall  f1-score   support

           0       0.93      0.91      0.92      1087
           1       0.91      0.93      0.92      1073

    accuracy                           0.92      2160
   macro avg       0.92      0.92      0.92      2160
weighted avg       0.92      0.92      0.92      2160

Performance : Обучение эмбеддингов 1 m 18 s



