# User Input in Java

User input allows users to enter data while the program is running.

###In Java, we use the `Scanner` class to take input from the user.

###User input is important because it makes programs interactive.

## Import Scanner

Before using `Scanner`, we need to import it.

```java
import java.util.Scanner;
```

## Creating a Scanner Object

```java
Scanner sc = new Scanner(System.in);
```

- `Scanner` → class used for input
- `sc` → object name
- `System.in` → takes input from keyboard

---

## Example

```java
import java.util.Scanner;

public class UserInputExample {

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        System.out.print("Enter your name: ");

        String name = sc.nextLine();

        System.out.println("Hello " + name);

    }

}
```


## Output

```java
Enter your name: Shashwat
Hello Shashwat
```

## Different Scanner Methods

-  nextInt() = Reads integer 
-  nextDouble() = Reads decimal number 
-  next() = Reads one word 
-  nextLine() = Reads full sentence 
-  nextBoolean() = Reads true or false 

## Integer Input Example

```java
import java.util.Scanner;

public class AgeExample {

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

        System.out.print("Enter your age: ");

        int age = input.nextInt();

        System.out.println("Your age is " + age);

    }

}
```

---

## Output

```java
Enter your age: 23
Your age is 23
```
