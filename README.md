### Задача 

**Определить самые загруженные часы в течении недели**

Для этого были решены следующие задачи:
1. В датасете `workouts` введем две новые колонки: `hour` — час и `day_number` — номер дня в неделе
2. Сгруппирован датасорс по часу и дню недели и посчитаем количество тренировок
3. Создана сводная таблица, где:
- `index` — dayofweek
- `columns` — hour
- `values` — workout_id.
4. Построен heatmap
![image](https://github.com/fleisan18/loads_in_fitnes_center/assets/92662450/6c7495df-d2bf-49aa-9553-95d3850528bd)
Самыми нагруженными оказались будние вечерние часы с 18 до 20 за исключением пятницы.
