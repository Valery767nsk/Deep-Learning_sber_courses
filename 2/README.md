# Курсовая Deep Learning Весна 2021 на тему LightAutoML.
Сфокусировался на решении бизнес задач с помощью ML, а точнее на автоматизацию машинного обучения с помощью фреймворка LightAutoML(LAMA). 
Прохожу курс и решал задачи, включая в kernel LAMA. 
1. [LightAutoML course homework 1](https://www.kaggle.com/c/lightautomlcourse-hw1) (Business task)
2. [CommonLit Readability Prize](https://www.kaggle.com/c/commonlitreadabilityprize) (NLP)
3. [LightAutoML course finals](https://www.kaggle.com/c/lightautoml-course-finals/overview)  (new task)
 
В курсовой я участвовал в соревновании и тестировал LightAutoML. [Tabular Playground Series - Jun 2021](https://www.kaggle.com/c/tabular-playground-series-jun-2021/overview)

Исходный набор искусственных данных предназначен для прогнозирования категории продукта электронного магазина.
- создал Neural Network с помощью библиотеки keras DL_NN.ipynb
- обучил одну модель LAMA, сгенерировал три признака (результат обучения линейной регрессии, LGBM, Catboost) NN_LightAutoML.ipynb
- на вход обучения второй модели отдаём исходные данные, predicts из первого LightAutoML и Neural Network
