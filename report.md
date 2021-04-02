# Отчёт о тестировании Bonus+

Протестировать код по добавлению дополнительных бонусов клиентам
02.04.2020 - 02.04.2020 было проведено функциональное тестирование базового  приложения Money Transfer

На тестирование затрачено: 15 минут

### В результате тестирования выявлены следующие дефекты:
**[Неверно рассчитывается сумма бонусов
](https://github.com/fiolentanna/hw_bonus/issues/1)**

### Процесс тестирования

В процессе тестирования использовались следующие артефакты:
* Cоздать новый проект по тестированию на IntelliJ IDEA 2020.3.3 (Community edition)
* Написать базовое приложение, используя вводные данные
```
public class Main {
public static void main(String[] args) {
double regularBonus = 0.3;
double specialBonus = 0.6;
double totalBonus = regularBonus + specialBonus;
System.out.println(totalBonus);
}
}
```
* Запустить проверку

### Тестирование производилось в следующем окружении:
* macOS BIG Sur
* версия Java - "11.0.10"
* IntelliJ IDEA 2020.3.3 (Community edition)