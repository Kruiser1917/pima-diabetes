# Pima Indians Diabetes — Логистическая регрессия и метрики классификации

Учебный проект по модулю **04 Machine Learning (Тема 03: Логистическая регрессия и метрики)**.
Целевая переменная — `Outcome` (`1` — наличие диабета, `0` — отсутствие).

## Структура проекта

- `pima_diabetes_logreg.ipynb` — ноутбук с полным исследованием: анализ признаков и скрытых пропусков, стратифицированное разбиение `train/test`, константный baseline, обучение `LogisticRegression`, построение `Confusion Matrix`, `ROC` и `PR` кривых, эксперимент с порогами (`0.3`, `0.5`, `0.7`) и весами классов (`class_weight='balanced'`).
- `data/diabetes.csv` — датасет Pima Indians Diabetes (768 строк, 9 столбцов).
- `requirements.txt` — зависимости проекта.

## Быстрый запуск

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

