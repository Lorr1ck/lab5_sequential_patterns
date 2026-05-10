# Лабораторная работа №5: Поиск последовательных шаблонов

## Описание
Реализация алгоритмов поиска последовательных шаблонов: AprioriAll (с нуля), PrefixSpan (библиотека). Анализ последовательностей покупок клиентов.

## Датасет
Online Retail (https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)

## Структура
- `data/online_retail.csv` – данные транзакций
- `notebooks/05_sequential_patterns.ipynb` – основной ноутбук
- `report/sequential_report.md` – отчёт

## Запуск
```bash
git clone https://github.com/Lorr1ck/lab5_sequential_patterns.git
cd lab5_sequential_patterns
pip install pandas numpy matplotlib seaborn networkx python-dateutil
jupyter notebook notebooks/05_sequential_patterns.ipynb
