# README hw1

Задача: многоклассовая классификация  
Колаб: https://colab.research.google.com/drive/1v4wqDQl6gJpLhm4-VZBD695foHPRg467?usp=sharing

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
- оптимайзер: SGD  
- lr: 0.001  
- momentum: 0.9  
- epoch: 4  
- batch: 64  
  
Loss:  
![loss](https://i.ibb.co/qYVXj0Ps/BDcpgdlip36d.jpg)  

Accuracy:  
![accuracy](https://i.ibb.co/q3Hbm8b8/a9-HWJJCS5w-Yc.jpg)  

Метрики:  
| Класс | Точность |
|-------|----------|
| plane | 92.86%   |
| car   | 94.00%   |
| bird  | 79.75%   |
| cat   | 71.23%   |
| deer  | 87.27%   |
| dog   | 72.88%   |
| frog  | 87.50%   |
| horse | 90.62%   |
| ship  | 96.55%   |
| truck | 92.31%   |

Пример распознавания:  
![example](https://i.ibb.co/0y0YtYj2/QAm-Oq-ABx-Fq-Eh.jpg)  
