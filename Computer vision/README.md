# Обработка фотографий покупателя
[ipynb](https://github.com/naumovakotya/Portfolio/blob/main/Computer%20vision/Processing%20of%20customer's%20photos.ipynb)

## Описание проекта

## Навыки и инструменты
* **python**
* **pandas**
* tensorflow.keras.applications.resnet.**ResNet50**
* tensorflow.keras.layers.**GlobalAveragePooling2D**
* tensorflow.keras.layers.**GDense**
* tensorflow.keras.models.**Sequential**
* tensorflow.keras.optimizers.**Adam**
* tensorflow.keras.preprocessing.image.**ImageDataGenerator**

## Общий вывод
Была постоена и обучена свёрточная нейронная сеть на базе `ResNet50` из библиотеки `tensorflow.keras` на датасете с фотографиями людей разных возрастов для сетевого супермаркета. Нейронная сеть была обучена с целью фотофиксации в прикассовой зоне для определения возраста клиентов, чтобы анализировать покупки и предлагать товары, которые могут заинтересовать покупателей этой возрастной группы и контролировать добросовестность кассиров при продаже алкоголя.

По ТЗ модель `MAE`< 8, однако получилось достичь `MAE` = 5.7854, что хороший результат.
