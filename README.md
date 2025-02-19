# Геоаналитика

`Цель исследования` — предсказание успешности объекта ритейла.


# Инструкция по использованию скриптов для прогнозирования

Данные инструкции помогут вам использовать скрипты для обучения модели прогнозирования и создания файла предсказаний.

## Описание файлов
- `submission.csv` - файл с предсказаниями модели.
- `train.py` - скрипт для обучения модели на обучающих данных.
- `solution.py` - скрипт для создания предсказаний на основе тестовых данных и сохранения их в CSV-файле.


## Как использовать
1. Убедитесь, что файлы с обучающими (`train.csv`) и тестовыми (`test.csv`) данными находятся в той же директории, что и скрипты.
2. Запустите `train.py` для обучения модели. Модель будет автоматически сохранена в файл `best_model.cbm`.
3. После обучения модели запустите `solution.py` для создания предсказаний.

## Требования

- Библиотеки Python: pandas, catboost, sklearn
- Обучающий (`train.csv`) и тестовый (`test.csv`) наборы данных.

Убедитесь, что все зависимости установлены перед запуском скриптов.

Также здесь хранится файл `geoanalytics`, в котором отображено само исследование.
