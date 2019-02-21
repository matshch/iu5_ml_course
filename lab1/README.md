# Лабораторная работа №1 «Разведочный анализ данных. Исследование и визуализация данных»
Цель лабораторной работы, задание и ход работы приведены в&nbsp;[Jupyter-ноутбуке](eda_visualization.ipynb). Собранный отчёт с&nbsp;титульным листом и библиографией лежит [рядом](eda_visualization.pdf).

Чтобы собрать отчёт из&nbsp;Jupyter-ноутбука, используйте следующую команду:
```bash
jupyter nbconvert --to pdf --template=../common/template.tplx eda_visualization.ipynb
```

Для&nbsp;того, чтобы повторить вычисления в&nbsp;ноутбуке, не&nbsp;забудьте установить зависимости в&nbsp;ваше (возможно виртуальное) окружение:
```bash
pip3 install -r requirements.txt
```