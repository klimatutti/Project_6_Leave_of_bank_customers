 # Проект_6_Отток_клиентов_банка

 Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.

Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Вам предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

Постройте модель с предельно большим значением F1-меры.

Сначала мы подготовим данные: рассмотрим общую информацию о датафрейме и пропуски в нем. В исследовании задачи рассмотрим насколько сбалансированы классы, преобразуем категориальные признаки в численные с помощью техники прямого кодирования, затем обойдем дамми-ловушку, отмасштабируем признаки и попробуем обучить модель без баланса классов.

В следующем блоке испробуем несколько способов балансировки классов и протестируем разные модели для того, чтобы добиться наилучшего значения F1-меры. Выберем лучшую модель и применим её к тестовой выборке.

# Project_6_Leave_of_bank_customers

Customers began to leave Beta-Bank. Every month. A little, but noticeable. Banking marketers figured it was cheaper to keep current customers than to attract new ones.

It is necessary to predict whether the client will leave the bank in the near future or not. You are provided with historical data on customer behavior and termination of agreements with the bank.

Build a model with an extremely large F1-measure.

First, we will prepare the data: we will consider general information about the dataframe and gaps in it. In the study of the problem, we consider how balanced the classes are, we convert categorical features into numerical ones using the direct coding technique, then we bypass the dummy trap, scale the features and try to train the model without class balance.

In the next block, we will try several ways to balance classes and test different models in order to achieve the best F1-measure value. Let's choose the best model and apply it to the test sample.
