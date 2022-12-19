# Нейронные сети

Практические работы по нейронным сетям (Tensorflow Keras)

**Нейронная_сеть(код).ipynb** - реализация полносвязной НС с помощью инструментов python.

**TransferLearning_FineTuning.ipynb** - практическое применение FineTuning для обучения классификатора изображений.



## Object Detection

Использование библиотеки object detection для работы в Google Colab (под TensorFlow 2).
В отдельной папке загружены используемые файлы, скрипты, pipeline для обучения модели.

Использованы инструкции:

https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html#tensorflow-object-detection-api-installation

https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/training.html

А также, ряд скриптов заимствован из статьи https://habr.com/ru/post/530850/

Для корректной работы именно из Google Colab были вненсены изменения в некоторые библиотечные файлы:
label_map_util.py, tf_example_decoder.py, visualization_utils.py

Работа делалась в учебных целях, был использован набор из 10 фотографий будильника. Все описанные шаги можно применить и для более сложных задач.
