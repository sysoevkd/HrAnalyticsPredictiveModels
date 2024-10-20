# HrAnalyticsPredictiveModels

В этом проекте будет выполнена работа с данными, предоставленными компанией «Работа с заботой», которая занимается оптимизацией управления персоналом с помощью HR-аналитики. Основная цель исследования — разработать модели машинного обучения для предсказания уровня удовлетворённости сотрудников работой и вероятности их увольнения.

## Цель исследования

Разработка модели для предсказания уровня удовлетворённости сотрудников и модели для предсказания увольнения сотрудников. Это поможет компании снизить текучесть кадров и повысить удовлетворённость сотрудников, что, в свою очередь, ведёт к улучшению бизнес-показателей.

## Суть исследования

Будет проведён анализ характеристик сотрудников, таких как уровень удовлетворённости, должность, загруженность, зарплата и другие факторы, чтобы построить предсказательные модели. Эти модели помогут в оценке уровня удовлетворённости сотрудников и в предсказании увольнений, что является критически важным для бизнеса.

## Задачи исследования

1. Построить модель, предсказывающую уровень удовлетворённости сотрудников.
2. Построить модель, предсказывающую вероятность увольнения сотрудников.
3. Провести исследовательский анализ данных для выявления зависимостей между признаками.
4. Предобработать данные и подготовить их для обучения моделей.
5. Обучить и оценить модели, используя соответствующие метрики.

## Исходные данные

Данные представлены в нескольких файлах:

- **train_job_satisfaction_rate.csv** — тренировочная выборка для первой задачи.
- **test_features.csv** — входные признаки для тестовой выборки первой задачи.
- **test_target_job_satisfaction_rate.csv** — целевой признак для тестовой выборки первой задачи.
- **train_quit.csv** — тренировочная выборка для второй задачи.
- **test_target_quit.csv** — целевой признак для тестовой выборки второй задачи.

## Структура исследования

Данное исследование разделено на несколько частей:

### Часть 1. Изучение общей информации

1. Изучение файлов с данными, получение общей информации, загрузка библиотек.
2. Нахождение и ликвидация пропусков.

### Часть 2. Подготовка данных

1. Приведение данных к нужным типам.
2. Нахождение и исправление аномалий и ошибок.

### Часть 3. Исследовательский анализ данных

1. Исследование всех признаков и их влияние на целевые переменные.
2. Построение портрета «уволившегося сотрудника» и визуализация распределения уровня удовлетворённости.

### Часть 4. Моделирование

1. Обучение моделей для предсказания уровня удовлетворённости и увольнения сотрудников.
2. Оценка качества моделей с использованием SMAPE и ROC-AUC.

### Часть 5. Выводы

1. Формулирование выводов о наиболее эффективных моделях и рекомендаций для бизнеса.

---

Этот проект направлен на улучшение понимания факторов, влияющих на удовлетворённость сотрудников, и на снижение уровня увольнений, что поможет компании оптимизировать управление персоналом и избежать финансовых потерь.
