# Сверточные нейронные сети (Convolutional Neural Networks). Архитектура и гипперпараметры. GoogLeNet
Учебно-методический материал

Подготовлено: Артём Сучков

Convolutional Neural Networks (CNN) Structure and Parameters. GoogLeNet
Educatorial for Classification case studying \ CNN neural network theory with practice script of GoogLeNet 

## Содержание занятия

##### Нейронные сети в задачах распознавания изображений
- Распознавание изображений в задачах классификации. 
- ANN в задачах распознавания изображений. Матрицы. 
##### Сверточная нейронная сеть Convolution Neural Network. Введение
- Предпосылки создания свёрточных сетей. Класс CNN
- Отцы-основатели. Torsten Nils Wiesel, David H. Hubel. Yann LeCun
- Идея метода Сonvolution Neural Network
- Принцип организации сверточной нейронной сети: СNN и FF
##### Главные компоненты сверточной нейронной сети
- Фильтры; 
- Свёртка. Карты признаков. Каналлы;
##### Архитектурная парадигма сверточных нейронных сетей
- Локальное восприятие;
- Идентичность ядра весов
- Субдискретизация
##### Субдискретизация 
- Padding. Сохранение масштаба изображения. Добавочные значения. Zero frame;
- Stride. Изменение шага смещения фильтра. Bias;
- Pooling. Объединение карт признаков по признакам. Обобщение/Детализация. MaxPooling

##### Обучение сети класса CNN
- Гипперпараметры в обучении нейронной сети класса CNN;
- Основные принципы обучения нейронной сети класса CNN;
- Библиотеки данных для обучения нейронной сети класса CNN в задачах распознавания изображений;
- Метод регуляризации Dropout
