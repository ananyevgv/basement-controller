# basement-controller Версия 2.0

| basement                                                  | plata                                                   | display                                    |
|------------------------------------------------------------|-----------------------------------------------------------|--------------------------------------------|
| ![basement](https://github.com/ananyevgv/basement-controller/blob/main/basement.jpg) | ![plata](https://github.com/ananyevgv/basement-controller/blob/main/plata.jpg) | ![display](https://github.com/ananyevgv/basement-controller/blob/main/display.jpg) |

Контролер для управлением подвальным помещением.

Отслеживает:
  1. Работу погружного насоса (время включения выключения, количество включений за сутки, продолжительность работы, ток потребления) датчик ZMCT103C
  2. Температуру на улице и в нутри отведеного для хранения помещения.
  3. Управление климатом в помещении для хранения (в зависимости от уличной температуры вытяжка, элементы пельтье (планирую заменить на что то более серьезное) )
  4. Мониторинг ИБП
  5. Превышение уровня грунтовых вод. 

Анимированый вывод статусов на дисплей dss1322

Для мониторинга ИБП испльзуется слегка доработаный компонент: 
https://github.com/syssi/esphome-apc-ups

Корпус контролера использовал готовую модель:
https://www.thingiverse.com/thing:3582642/files

Корпус ZMCT103C:
https://github.com/ananyevgv/basement-controller/ZMCT103C.stl
https://github.com/ananyevgv/basement-controller/ZMCT103C-ver.stl
