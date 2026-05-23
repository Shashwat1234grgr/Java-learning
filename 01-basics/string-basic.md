# Strings Basics in Java

Strings are used to store text in Java.

- A String can contain:
  - words
  - numbers
  - sentences
  - symbols

###Anything written inside double quotes `" "` is considered a String.
###Java provides many built-in String methods.
###String indexing starts from `0`.

## Creating a String

```java
String name = "Shashwat";
```

- `String` → data type
- `name` → variable name
- `"Shashwat"` → value


## String Example

```java
String message = "Java is fun";

System.out.println(message);
```

Output:

```java
Java is fun
```

---

## Common String Methods

- length() | Returns length of string |
- toUpperCase() | Converts string to uppercase |
- toLowerCase() | Converts string to lowercase |
- charAt() | Returns character at specific index |
- contains() | Checks if string contains text |

## length() Example

```java
String name = "Shashwat";

System.out.println(name.length());
```

Output:

```java
8
```

---

## toUpperCase() Example

```java
String language = "java";

System.out.println(language.toUpperCase());
```

Output:

```java
JAVA
```

---

## toLowerCase() Example

```java
String language = "JAVA";

System.out.println(language.toLowerCase());
```

Output:

```java
java
```

---

## charAt() Example

```java
String name = "Shashwat";

System.out.println(name.charAt(0));
```

Output:

```java
S
```

---

## contains() Example

```java
String sentence = "Java is powerful";

System.out.println(sentence.contains("Java"));
```

Output:

```java
true
```
- String indexing
- manipulating text using methods
