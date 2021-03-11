# Отчёт о тестировании Credit Card Number Validator
## Краткое описание

10.03.2021 - 10.03.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:
Не проходят валидацию номера карт в составе которых больше или меньше 16 знаков. Независимо от платежной системы. 
* https://github.com/Lexx-Psi/Lec1.1-HW2-CreditCardNumberValidator/issues/1#issue-827612577

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Руководство по установке IntelliJ IDEA](https://github.com/netology-code/javaqa-homeworks/blob/863ba97c5114ff5fd279e86ed86aef066e224ac6/intro/idea.md)

В качестве тестовых данных использовались данные [Тестовые номера карт](https://github.com/Lexx-Psi/Lec1.1-HW2-CreditCardNumberValidator/blob/fc7018a09901e412a862e19e5b6a61909ba5a564/%D0%A2%D0%B5%D1%81%D1%82%D0%BE%D0%B2%D1%8B%D0%B5%20%D0%BD%D0%BE%D0%BC%D0%B5%D1%80%D0%B0%20%D0%BA%D0%B0%D1%80%D1%82) с сайта [freeformater.com](https://www.freeformatter.com/credit-card-number-generator-validator.html)

Тестирование производилось в следующем окружении:
* ОС Майкрософт Windows 10 Pro Версия	10.0.19042 Сборка 19042
* java version "11.0.10" 2021-01-19 LTS
* IntelliJ IDEA 2020.3.2 (Community Edition) Build #IC-203.7148.57
