# Como garantir uma instância única em Singleton

## Destrinchando uma instância

Instância seria quando estamos executando/chamando a funcão.

Como exemplo, vamos criar a seguinte classe em Java:

```java
public class Rafael {
    String name;
    String fav_food;
    int age;

    public void say_my_name(){
        System.out.println("Hello, my name is " + name + " a'm " + age + " years old, and my favorite food is " + fav_food);
    }
```

E agora vamos instanciar essa classe, isso irá transformá-la emum objeto.

```java
public static void main(String[] Args){
    Rafael rafael = new Rafael();

    rafael.name = "zozas";
    rafael.age = 18;
    rafael.fav_food = "hamburguer";

    rafael.say_my_name();
    }
```

Aqui, o objeto da classe Rafael foi instanciado como rafael, nisso conseguimos atribuir os valores que quisermos para esse objeto. Assim, a conclusão que temos é que a instância é apenas uma chamada, uma delcaracão de que estamos usando uma determi nada classe, já o objeto seria a individualizacão dessa instância.