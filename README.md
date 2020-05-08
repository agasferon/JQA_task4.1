# Задача №1 - Мили (модернизация)

## Исходный код BonusMilesService.class
```java
public class BonusMilesService {
    public int calculate(int cost) {
        return cost / 20;
    }
}
```
## Исходный код Main.class
```java
public class Main {
    public static void main(String[] args) {
        BonusMilesService service = new BonusMilesService();
        int price = 10_000;
        int miles = service.calculate(price);
        System.out.println(miles);
    }
}
```
Работа написана в следующем окружении:
* Windows 10 1903 18362.778
* openjdk version "11.0.7" 2020-04-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.7+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.7+10, mixed mode)