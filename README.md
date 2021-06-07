# Комп’ютерне бачення для систем допомоги водієві
[![Emgu CV](https://avatars1.githubusercontent.com/u/2035816?v=3&s=40)](https://github.com/emgucv/emgucv)
## Огляд
Це сховище містить основні програми для розпізнавання дорожніх знаків та виявлення смуги руху. Код написаний на C # .NET і використовує Emgu CV (3.1.0.2504) як обгортку для OpenCV.

## TrafficSignRec
Інструмент виявлення та розпізнавання на основі SURF (прискорення надійних функцій). Він використовує гомографію з RANSAC для підвищення стабільності. Набір відомих ознак відповідає кандидатам на зображенні.

![TrafficSignRec demo](https://github.com/anthony-mestdach/TrafficComputerVision/blob/master/Code/Results/TrafficSignRec/Afbeelding1.png)

# HaarCascadeDetector
Детектор знаків на основі Хаара. Для виявлення знаку обмеження швидкості 90 км / год (бельгійський) включено кілька каскадних файлів Хаара.

![HaarCascadeDetector demo](https://github.com/anthony-mestdach/TrafficComputerVision/blob/master/Code/Results/HaarCascadeDetector/demo.png)

![LaneDetection demo](https://github.com/anthony-mestdach/TrafficComputerVision/blob/master/Code/Results/LaneDetection/LaneDetection.gif)
