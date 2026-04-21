# RDD

Этот репозиторий содержит материалы и код для вопроизведения результатов статьи о 

## Содержание

- **AppliedMicroeconometrics.ipynb** - Jupyter ноутбук с практическими примерами применения микроэконометрических методов
- **AppliedMicroeconometrics.pdf** - Подробное описание эксперимента
- **Lee D. Randomized experiments from non-random selection in U.S. House elections.pdf** - Научная статья о рандомизированных экспериментах
- **data_for_problem2.dta** - Набор данных в формате Stata для решения задач

## Темы

- Причинный вывод (Causal Inference)
- Микроэконометрика
- Рандомизированные эксперименты
- Анализ данных наблюдений

## Требования

Для работы с материалами вам понадобятся:

- Python 3.x с библиотеками:
  - pandas
  - numpy
  - matplotlib/seaborn
  - jupyter
- Stata или Python-библиотека `pyreadstat` для открытия .dta файлов

## Использование

1. Клонируйте репозиторий:
```bash
git clone <repository-url>
cd <repository-directory>
```

2. Откройте Jupyter ноутбук:
```bash
jupyter notebook AppliedMicroeconometrics.ipynb
```

3. Для загрузки данных в Python:
```python
import pandas as pd
data = pd.read_stata('data_for_problem2.dta')
```

## Лицензия

Образовательные материалы. Пожалуйста, указывайте источники при использовании.
