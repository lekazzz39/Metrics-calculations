# Расчёты метрик
### Суть
Сюда я сохраняю примеры расчетов продуктовых метрик. 


### Какие метрики есть:
 - Динамика ARPPU
 - Кумулятивный APRRU когорты
 - ad-hoc специфичного показателя
 - Retention 

### Что используется:
Расчеты написаны на Python 3.9, SQL (SQLite диалект).
Основные модули:
 - pandas
 - numpy
 - pandasql

С помощью pandas и numpy генерируется датасет. SQL используется для расчётов. Retention сделан на основе имеющегося датасета (файл promo.csv).


### Особенности окружения. 
Написан при помощи актуальных пакетов anaconda3.
Версии:
Python 3.9.7
numpy 1.20.3
pandas 1.3.4
pandasql 0.7.3

Для установки pandasql:
Conda:
```
conda install -c anaconda pandasql
```

Pip:
```
pip install -U pandasql
```



### Ссылки на источники 
[Расчет retention](https://medium.com/@adrianovalexey/%D1%80%D0%B0%D0%B7-%D0%B8-%D0%BD%D0%B0%D0%B2%D1%81%D0%B5%D0%B3%D0%B4%D0%B0-%D0%BA%D0%B0%D0%BA-%D0%B0%D0%B2%D1%82%D0%BE%D0%BC%D0%B0%D1%82%D0%B8%D0%B7%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D1%82%D1%8C-%D0%BF%D0%BE%D1%81%D1%82%D1%80%D0%BE%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BA%D0%BE%D0%B3%D0%BE%D1%80%D1%82-%D1%81-python-%D0%B8-pandas-74f2c38dd3f7)
[Кумулятивный ARPPU](https://www.devtodev.com/education/articles/ru/138/glavnie-metriki-arpu-i-arppu-odna-bukva-i-printsipialynie-otlichiya)
[Кумулятивный ARPPU когорты](https://www.devtodev.com/education/articles/ru/146/glavnie-metriki-nakopitelyniy-arpu)
