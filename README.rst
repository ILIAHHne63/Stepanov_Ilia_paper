|test| |codecov| |docs|

.. |test| image:: https://github.com/intsystems/ProjectTemplate/workflows/test/badge.svg
    :target: https://github.com/intsystems/ProjectTemplate/tree/master
    :alt: Test status
    
.. |codecov| image:: https://img.shields.io/codecov/c/github/intsystems/ProjectTemplate/master
    :target: https://app.codecov.io/gh/intsystems/ProjectTemplate
    :alt: Test coverage
    
.. |docs| image:: https://github.com/intsystems/ProjectTemplate/workflows/docs/badge.svg
    :target: https://intsystems.github.io/ProjectTemplate/
    :alt: Docs status


.. class:: center

    :Название исследуемой задачи: Применение синтетических данных, полученных с помощью генеративной нейросети, для повышения качества моделей детекции
    :Тип научной работы: НИР
    :Автор: Степанов Илья Дмитриевич
    :Научный руководитель: к.ф-м.н., Грабовой Андрей Валерьевич
    :Научный консультант(при наличии): Филатов Андрей Викторович

Abstract
========

Аугментация данных играет ключевую роль в улучшении производительности моделей машинного обучения, особенно в области компьютерного зрения. Традиционные методы, такие как повороты, сдвиги и регулировка яркости, ограничены в своей способности обеспечивать значительные семантические вариации, что часто приводит к плохому обобщению на новые данные.

В данной статье мы представляем новый подход, который позволяет заменять объекты на изображениях. Используя Visual Language Models, мы получаем описания изображений, а затем, используя Large Language Models, определяем, что можно заменить на изображении и составляем расширенный 'prompt', с помощью которого можем генерировать модифицированные данные. Таким образом, мы увеличиваем количество данных с использованием осмысленных 'prompts'.

Мы демонстрируем эффективность данного подхода, проводя бенчмаркинг моделей, обученных с аугментированными и без аугментированных данных, показывая улучшения в производительности моделей детекции.

Research publications
===============================
1. 

Presentations at conferences on the topic of research
================================================
1. 

Software modules developed as part of the study
======================================================
1. A python package *mylib* with all implementation `here <https://github.com/intsystems/ProjectTemplate/tree/master/src>`_.
2. A code with all experiment visualisation `here <https://github.comintsystems/ProjectTemplate/blob/master/code/main.ipynb>`_. Can use `colab <http://colab.research.google.com/github/intsystems/ProjectTemplate/blob/master/code/main.ipynb>`_.
