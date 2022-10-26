Задача построения поискового движка

Baseline
1. Препроцессинг данных - чистка и нормализация
2. Обучение skipgram-эмбеддингов и вычисление эмбеддингов названий компаний
3. Оценка ближайших названий по косиносному расстоянию

Метрика : accuracy на базе предсказаний на базе 3658 пар названий компаний(is_duplicate=1)

Подход на базе NER и сопоставление названий ЮЛ с использованием выделенных сущностей