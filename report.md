# Отчёт о тестировании <Money Transfer>


5.12.2021 было проведено воспроизведение ситуации пополнения счета, приложения "Money Transfer"

На тестирование затрачено: 20 мин

В результате тестирования выявлены следующие дефекты:

При переводе средств, баланс получается отрицательный 

https://github.com/AlesandrM/Homework-Java1/issues/1

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Задание 1 https://github.com/netology-code/javaqa-homeworks/blob/master/intro/MERGED.md


В качестве тестовых данных использовались данные из задачи 1:

• текущий баланс счёта клиента - переменная типа int, значение - 2_000_000_000 (два миллиарда рублей)
  
• сумма перевода - переменная типа int, значение - 500_000_000 (пятьсот миллионов рублей)
  
• переменная для хранения итогового значения - тип int


Тестирование производилось в следующем окружении:
* Windows 7; 64-ОС 
* openjdk version "11.0.12" 2021-07-20
* IntelliJ IDEA 2021.2.3 (Community Edition)
