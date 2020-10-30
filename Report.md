# Отчёт о тестировании Money Transfer
## Краткое описание
28.10.2020 было проведено функциональное тестирование приложения Money Transfer.

На тестирование затрачено: 2 часа

**В результате тестирования выявлен следующий дефект:**
* [При использовании переменной типа int в сумме, превыщающей 2 147 483 647, итоговое число высчитывается некорректно. #1](https://github.com/ViktoriaMasl/Money-Transfer/issues/1)

В качестве тестовых данных использовались суммы [из задания](https://github.com/netology-code/javaqa-homeworks/tree/master/programming).

*Тестирование производилось в следующем окружении:*

PC, Windows 10 Pro версия 1903  
IntelliJ IDEA 2020.2.3 (Community Edition)  
Build #IC-202.7660.26, built on October 6, 2020  
Runtime version: 11.0.8+10-b944.34 amd64  
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
