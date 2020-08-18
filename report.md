# Отчёт о тестировании инструкции об установке OpenJDK11 на Windows 7

## Краткое описание

<17.08.2020> - было проведено тестирование документации по установке OpenJDK11 на Windows 7 64bit

На тестирование затрачено: <0.5 часа>

## Описание процесса тестирования

В ходе тестирования была использована [инструкция](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md/) для установки OpenJDK11 на компьютер с ситемой Windows. Следуя инструкции с Шага 1 по Шаг 7 OpenJDK11 была успешно установлена на компьютер без сбоев. В финальном шаге команда "Java -version" в терминале выдала следующую информацию: 
>"openjdk version "11.0.8" 2020-07-14
>OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
>OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)" что означает что установка прошла успешно.

В качестве тестовых данных использовались:
* [инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md/) на ОС Windows
* Архив Java 11 (OpenJDK11) с [сайта](https://adoptopenjdk.net/)

Тестирование производилось в следующем окружении:
* <Windows 7 Максимальная 64bit>