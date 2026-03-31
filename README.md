# ML Analysis of Chemical Compounds

## Описание проекта
В данном проекте решается задача прогнозирования эффективности химических соединений против вируса гриппа.
Рассматриваются следующие задачи:
- Регрессия:
   IC50
   CC50
   SI
- Классификация:
   IC50 > медианы
   CC50 > медианы
   SI > медианы
   SI > 8
## Данные
- 1001 объект
- 214 признаков
- Все признаки — числовые дескрипторы
Целевые переменные:
- IC50
- CC50
- SI
Важно:
> SI рассчитывается как CC50 / IC50
## Используемые модели
- Linear Regression
- Decision Tree
- Random Forest
- Logistic Regression (для классификации)
## Основные результаты
- Лучшая модель: **Random Forest**
- IC50 и CC50 предсказываются хорошо
- SI предсказывается слабо (производный показатель)
## Рекомендации
- Моделировать IC50 и CC50
- SI рассчитывать по формуле: SI = CC50 / IC50
## Структура проекта
EDA.ipynb
model_ic50.ipynb
model_cc50.ipynb
model_si.ipynb
classification_ic50.ipynb
classification_cc50.ipynb
classification_si.ipynb
report.pdf
README.md
## Технологии
- Python
- pandas, numpy
- scikit-learn
- matplotlib, seaborn


  

