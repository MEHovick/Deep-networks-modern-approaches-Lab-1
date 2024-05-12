## Инструкция

1) Устновить библиотеки torch, numpy, matplotlib, notebook
2) Запустить последовательно все ячейки из файла main.ipynb

## Описание методов

В работе представленн единый класс NeuralNetworkForNumbers, представляющий многослойный перцептрон, который содержит в себе методы:

1) init - инициализация начальных параметров (количество нейронов скрытого слоя, количество пикселей изображения\размер входного слоя, количество классов)
2) loss - функция потерь
3) sigmoid - функция активации
4) softmax - многопеременная логистичяеская функция
5) forward - функция прохода "вперед", для вычисления выходов нейронной сети
6) backprop - функция вычисления градиентов функции ошибки
7) train - функция обучения