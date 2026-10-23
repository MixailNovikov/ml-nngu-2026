# Классификация высокого макиавеллизма (MACH-IV)

Домашнее задание по курсу «Машинное обучение»: предсказать, попадает ли человек в верхние 20% по шкале макиавеллизма, по личности (TIPI), демографии и словарному тесту. kNN с подбором k, сравнение с логистической регрессией и градиентным бустингом, подбор порога при дисбалансе 20/80. Лучший результат — test ROC-AUC 0.807.

## Данные
MACH-IV, Open Source Psychometrics Project (2017–2019): https://openpsychometrics.org/_rawdata/ — архив `MACH_data.zip`. Файл `data.csv` положить в папку `data/` (в репозиторий не включён).

## Запуск
conda env create -f environment.yml
conda activate ml_env
jupyter lab high_mach_classification.ipynb

`knn_grid.csv` — сохранённые результаты подбора k; удалите файл, чтобы пересчитать.
