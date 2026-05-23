# Logical Operators

Logical operators are used to combine multiple conditions in Java.

- They return:
  - `true`
  - `false`

##Logical operators are mostly used in:
- conditions
- decision making
- loops

## Logical Operators

- Logical AND `&&`
  - Returns `true` if both conditions are true.

- Logical OR `||`
  - Returns `true` if at least one condition is true.

- Logical NOT `!`
  - Reverses the boolean value.

## Example

```java
boolean isStudent = true;
boolean hasID = true;

// Logical AND
System.out.println(isStudent && hasID);
```

Output:

```java
true
```

---

```java
boolean hasPermission = false;

// Logical OR
System.out.println(isStudent || hasPermission);
```

Output:

```java
true
```

---

```java
boolean isLoggedIn = true;

// Logical NOT
System.out.println(!isLoggedIn);
```

Output:

```java
false
```
