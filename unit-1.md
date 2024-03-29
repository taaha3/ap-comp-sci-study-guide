# AP Computer Science A Study Guide



## Basic Program

```java
// Single line comment

/*
 * Multi
 * line
 * comment
 */

public class Hello { // Class must be same name as file (Hello.java)
    
    public static void main(String[] args) {
        
        // System.out is an object used to display text in the console
        System.out.print("Line ");
        System.out.println("1");
        System.out.println("Line 2");

    }
}
    
```

## Errors

| Type | Example | Cause | Happens when? |
| ---- | ------- | ---------- | ---------- |
| Syntax/Compiler Error | `System.out.println("hi"];` | Code typed incorrectly | Compile time |
| Exception | Dividing by 0 | Something problematic/impossible happens as the code runs making it stop | Run time |
| Logic Error | Using + instead of - | Better word would be mistake, you did something wrong in your code so the result is wrong | Usually after run and compared actual output to anticipated output |


## Data Types

Primitive (built-in, no methods):

| Identifier | Example |
| ---------- | ------- |
| `int` | `10` |
| `double` | `10.1234` |
| `bool` | `true` |

Non-primitive (generally user made, have methods):

| Identifier | Example |
| ---------- | ------- |
| `String` | `"Hello hi"` |


## Variables

- Definition: A name given to a memory location that holds a specified type of value
- Naming rules: Can have letters, numbers, and underscores. Can't start with number. Can't use reserved keywords.
- Use `final` keyword before type to make variable non-reassignable (constant, use BIG_ANGRY_CASE)









