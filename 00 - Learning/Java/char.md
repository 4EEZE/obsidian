Char - тип данных предназначенный для хранения 1 символа из таблицы Unicode.

Сам символ храниться в переменной как код символа из тыблицы Unicode. То есть этот код будет выводить весь английский алфавит:

```java
public class Main {  
    public static void main(String[] args) {  
        char english_alphabet_letter = 'A';  
  
        for (int i = 65; i < 123; i++) {  
            System.out.print(english_alphabet_letter++);  
        }  
    }  
}

//РЕЗУЛЬТАТ:
//ABCDEFGHIJKLMNOPQRSTUVWXYZ[\]^_`abcdefghijklmnopqrstuvwxyz
```
