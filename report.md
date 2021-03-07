# Отчёт о тестировании KeyValidator

## Тестирование документации(инструкции по установке OpenJDK11), установки и совместимости, работы согласно руководству пользования.

03.03.2021 01:30 - 03.03.2021 01:35 было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 5 минут

В результате тестирования выявлены следующие дефекты:
* KeyValidator.class - treats a valid keys as invalid [Click to ISSUE](https://github.com/k2wln/homework-221/issues/1)
* KeyValidator.class - treats a invalid key as valid [Click to ISSUE](https://github.com/k2wln/homework-221/issues/4)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Git bash

В качестве тестовых данных использовались данные:
* [Тестовые данные](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

Тестирование производилось в следующем окружении:
* Windows 10 Pro, 20H2 Version, 64 bit
* Java Version 11.0.10
