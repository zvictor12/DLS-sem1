# Object Detection

## О задаче

Домашнее задание по улучшению базового детектора объектов на датасете Halo Infinite. Цель — доработать архитектуру и поднять mAP.

## Что сделано

- подготовлен датасет и аугментации изображений;
- доработан backbone с возможностью разморозки последних слоев;
- реализованы компоненты neck/head для детектора;
- разобраны FPN, Decoupled Head и варианты target assignment;
- добавлены loss-компоненты для bbox-регрессии.

## Стек

- Python
- PyTorch
- torchvision
- Albumentations
- Roboflow
- matplotlib
