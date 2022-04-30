# Рекомендация тарифов

# Цель

Построить модель для задачи классификации, которая выберет подходящий тариф. Выбрать лучшую модель.

# Вывод

Я исследовал и сравнил качество следующих моделей на валидационной выборке:

    Модель дерева решений. Accuracy = 0,812
    Модель случайного леса. Accuracy = 0,83
    Модель логистической регрессии. Accuracy = 0,768

Качество моделей на тестовой выборке:

    Модель дерева решений. Accuracy = 0,781
    Модель случайного леса. Accuracy = 0,804
    Модель логистической регрессии. Accuracy = 0,74

Все модели прошли оценку на адекватность.

В цели к проекту указано, что нужно довести долю правильных ответов по крайней мере до 0.75. Две модели справились с этой задачей. Модель логистической регрессии не достаточно точна для этой задачи.

Наилучший результат accuracy у модели случайного леса. Accuracy = 0,804.

# Стек

pandas, sklearn

# Статус

Завершен. Возможны доработки оформления и оптимизации кода.