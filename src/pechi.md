# Мониторинг температуры муфельных печей

## Проблема
Некоторые лабораторные работы, проводимые в 379А, предполагают использование муфельных печей. 
Для контроля температуры на начальных этапах используются ртутные градусники, 
однако с их помощью замер можно получить только до 500 градусов. 
Для более высоких температур используют термпопару, которая имеет большую шкалу деления,
что не позволяет получить точную информацию о температуре внутри печи. Также в кабинете имеется только одна термопара, а печей всего три.
<p align="center">
<img src="https://sun9-55.userapi.com/impg/iIh3K7vBh4_prumo5oRm5jgNN-KnvFzLr9DB2w/_6t7Vuc4TP8.jpg?size=2560x1178&quality=95&sign=b0cdf95ef62f373f52b3997be1795dec&type=album" width="600" height="auto" align="center">
</p>

## Задача

Обеспечить точный мониторинг температуры трех муфельных печей одновременно

---

## Компоненты
- Плата Arduino Nano
- 3x Аналогоцифровой преобразователь MAX6675
- 3x Термопара типа K
- LCD 1602 I2C
- PET-G пластик

---

## Инструменты
- 3D Принтер Flying Bear Ghost 5
- Fusion 360
- Arduino IDE

---

## Процесс создания

Первым шаг это создание электрической схемы будущего устройства.
По составленной схеме собирается рабочий прототип на макетной плате.

Мозгами устройства выступает плата Arduino Nano. Ее программирование велось в среде Arduino IDE 2.0.
От платы требовалось получить значение с термопар и вывести их на экран.

---

Удостоверившись, что электрическая схема и программа микроконтроллера работает
мы приступили к проектирования корпуса. Составив примерную компоновку корпуса мы принялись
делать 3D модели каждого компонента в Fusion 360. А далее уже спроектировали сам корпус.

<p align="center">
  <img src="https://sun9-35.userapi.com/impg/ihPscY7y8kmBRXhznQvzA2f1NOpP9-3aEkCxRA/HsQdci_2NPk.jpg?size=1920x1080&quality=95&sign=86b4e495eb478980273642b324740ac1&type=album" width="600" hieght="auto" align="center">
</p>


Модель корпуса была разбита на три части: переднюю, заднюю крышку и основу.
Эти детали были распечатаны на 3D принтере. Печать заняла около 10 часов.

<p align="center">
<img src="https://sun9-84.userapi.com/impg/C68tDJhAacva_rv7a2mD99AuOt1mUsPUUAojmA/S5VlnxVfxO0.jpg?size=1080x612&quality=95&sign=ec0188d0a32539f70ada16e2cfc78039&type=album" width="600" hieght="auto" align="center">
<p>
  
Далее мы собрали корпус вместе с электроникой, установили термопары в муфельные печи и проверили на работоспособность.

<p align="center">
<img src="https://sun9-80.userapi.com/impg/8VkSNokwi3wApw8PlSdQ81E_hokFf3Z1KAQnLg/le6F1isoniM.jpg?size=1840x2096&quality=95&sign=384f772cc3d681df497939ae95366a7c&type=album" width="600" hieght="auto" align="center">
<img src="(https://sun9-28.userapi.com/impg/TccEJRasAeoqJUmQ3X-57alI11_S_CK5TW4G1A/u9G7jNMXWkM.jpg?size=1840x1320&quality=95&sign=c3f6ea8cbfde1d5dbcf71e254c08f6ad&type=album" width="600" hieght="auto" align="center">
</p>

---

## Над проектом работали:
- Владислав Пинчук 19-КС
- Тимофей Востряков 21-ВТ
