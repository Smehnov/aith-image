# README hw3

Задача: многоклассовая классификация  
Колаб:  https://drive.google.com/file/d/1SyRDMmS4klvSgU1TqZ779n2tIZMQx9uP/view?usp=sharing

Описание: Тренируем SSL модель для угла поворота изображения, затем используем ее для обучения классификатора для CIFAR-10. Ввиду недостатка времени и вычислительных ресурсов я использовал малое количество эпох. Точность получилась небольшой, а модель на основе SSL показала результат хуже, чем базовый классификатор.

Датасет: Cifar 10  


Классы:  
- airplane   
- automobile  
- bird  
- cat  
- deer  
- dog  
- frog  
- horse  
- ship  
- truck  
  
Архитектура: VGG16  
  
Гиперпараметры:   
- оптимайзер: Adam  
- lr: 0.01  
- momentum: 0.9  
- epoch: 4  
- batch: 128  
  

Пример распознавания:  
![example](https://i.ibb.co/0y0YtYj2/QAm-Oq-ABx-Fq-Eh.jpg)  


## Тренируем модель SSL для определения угла поворота изображения
![ssl](https://i.ibb.co/mCfKv2qY/image.png)

## Сравнение стандартной модели и модели на основе SSL на N% размеченной выборки 
Тренируем модель на разных выборках: 100%, 50%, 10%

![100%](https://i.ibb.co/pBGkC6XQ/results-100-2.png)
![50%](https://i.ibb.co/XxD49nvn/results-50-2.png)
![10%](https://i.ibb.co/3mTKfHp7/results-10.png)


