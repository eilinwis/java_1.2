**Отчёт о тестировании IntelliJ IDEA Community Edition, Credit Card Number Validator**

**Краткое описание**

04.03.2021 - 04.03.2021 было проведено функциональное тестирование Credit Card Number Validator, тестирование установки приложения IntelliJ IDEA Community Edition.

На тестирование затрачено: 3

В результате тестирования выявлены следующие дефекты:

[Версия OpenJDK11 не соответствует заявленной](https://github.com/eilinwis/java_1.1/issues/1)

[Невалидный ключ проходит валидацию](https://github.com/eilinwis/java_1.1/issues/3#issue-822010170)

[Валидные ключи не проходят валидацию](https://github.com/eilinwis/java_1.1/issues/2#issue-822006391)


**Описание процесса тестирования**

В процессе тестирования использовались следующие артефакты*:

[Инструкция по установке IntelliJ IDEA Community Edition](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/idea.md)

[Код приложения Credit Card Number Validator](https://github.com/netology-code/javaqa-homeworks/tree/master/intro) 
Примечание: код расположен в блоке "Задание №2"



В качестве тестовых данных использовались данные:

[Сайт-генератор номеров кредитных карт](https://www.freeformatter.com/credit-card-number-generator-validator.html) 
(поле "Fake credit card numbers for all major brands")


**Тестирование производилось в следующем окружении:**

ПК Windows 10 64 bit

Java 11.0.10" 2021-01-19 LTS

IntelliJ IDEA Community edition 20.3.2