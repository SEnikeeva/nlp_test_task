# nlp_test_task
tweets ssentiment analysis

## Классификаторы (бинарный, трехклассовый), определяющие тональность поста в twitter'е.

1. Входные данные.

Корпус с SemEval 2016 task 4 subtask A (train и test) - объединенный датасет, находщийся в data/data.csv
Для обучения разделяется на train_data и test_data в соотношении 9 к 1.

2. TwitterSentimentAnalysis2 - ноутбук с моделями LSTM, CNN, обученными для бинарной классификации. TwitterSentimentAnalysis3 - для трехклассовой.

3. В output.txt оценки моделей (точность, полнота и F-мера).


Ссылки на код в google colaboratory: 

https://colab.research.google.com/drive/10EDPBjGCWvzHFq_q8FFVTPaI8Bng3xdX?usp=sharing

https://colab.research.google.com/drive/1W5QfS1XoQDD7tvssNJjCDn4ZqmQ9O467?usp=sharing
