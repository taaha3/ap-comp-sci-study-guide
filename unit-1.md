# Unit 1

## 1.1

Here's a basic Java program called "Hello.java":

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

Programs can have 3 kinds of errors:

| Type | Example | Cause | When? |
| ---- | ------- | ----- | ----- |
| Syntax/Compiler Error | `System.out.println("hi"];` | Code typed incorrectly | Compile time |
| Exception | Dividing by 0 | Something problematic happens as the code runs making it stop | Run time |
| Logic Error | + instead of - | Better word would be mistake, you did something wrong in your code so the result was wrong | Usually after run and compared actual output to anticipated output |



