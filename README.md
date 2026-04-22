# Code
```java
class Car {
    String color;
    int speed;

    public void drive(){
        System.out.println("color: " + color + " speed: " + speed);
    }
}

class Maincar{
    public static void main ( String[]abc){
        Car x = new Car();
        x.color = "Red";
        x.speed = 100;
        x.drive();
    }
}
```
