

# basement-controller ESPHOME Версия 2.0

[![License][license-shield]][license]
[![ESPHome release][esphome-release-shield]][esphome-release]

[license-shield]: https://img.shields.io/static/v1?label=License&message=MIT&color=orange&logo=license
[license]: https://opensource.org/licenses/MIT
[esphome-release-shield]: https://img.shields.io/static/v1?label=ESPHome&message=2025.7.2&color=green&logo=esphome
[esphome-release]: https://GitHub.com/esphome/esphome/releases/

<img src="https://github.com/ananyevgv/basement-controller/blob/main/basement-v2.jpg">


| basement                                                  | plata                                                   | 
|------------------------------------------------------------|-----------------------------------------------------------|
| ![basement](https://github.com/ananyevgv/basement-controller/blob/main/basement.jpg) | ![plata](https://github.com/ananyevgv/basement-controller/blob/main/plata.jpg) |

Контролер для управлением подвальным помещением.

Отслеживает:
  1. Работу погружного насоса (время включения выключения, количество включений за сутки, продолжительность работы, ток потребления) датчик ZMCT103C
  2. Температуру на улице и в нутри отведеного для хранения помещения.
  3. Управление климатом в помещении для хранения (в зависимости от уличной температуры вытяжка, элементы пельтье (планирую заменить на что то более серьезное) )
  4. Мониторинг ИБП
  5. Превышение уровня грунтовых вод, вывод звукового сигнала.

Анимированый вывод статусов на дисплей dss1322

Для мониторинга ИБП испльзуется слегка доработаный компонент: 
https://github.com/syssi/esphome-apc-ups

Корпус контролера использовал готовую модель (обработаную напильником):
https://www.thingiverse.com/thing:3582642/files

Корпус ZMCT103C:

https://github.com/ananyevgv/basement-controller/blob/main/ZMCT103C-ver.stl
https://github.com/ananyevgv/basement-controller/blob/main/ZMCT103C.stl

<img src="https://github.com/ananyevgv/basement-controller/blob/main/ZMCT103C.jpg" height="300">
