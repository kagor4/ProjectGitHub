Целью данного проекта является построение модели для прогнозирования ухода клиентов из "Бета-Банка". В качестве ключевой метрики качества модели установлено значение F1-меры, которое необходимо повысить до минимума 0.59.

Исследованы три модели классификации с учетом дисбаланса классов: DecisionTreeClassifier, RandomForestClassifier и LogisticRegression. DecisionTreeClassifier и RandomForestClassifier показали хорошие показатели точности и полноты. LogisticRegression демонстрирует более низкие показатели. Лучшей моделью может быть RandomForestClassifier, так как она обеспечивает хороший баланс между точностью и полнотой.

Были достигнуты важные цели. При поставленной задаче добиться F1-меры равно 0.59, получилось достичь F1-меру 0.61 на тестовой выборке. Модель RandomForestClassifier, обученная с использованием увеличением выборки, демонстрирует хорошие показатели при прогнозировании ухода клиентов из "Бета-Банка".
