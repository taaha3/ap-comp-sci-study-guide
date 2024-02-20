# Unit 1

## 1.1

Here's a basic Java program called "Hello.java":

```java
// Single line comment

/*
 * Multi line
 * comment
 */

public class Hello { // Class must be same name as file (MyClass.java)
    
    public static void main(String[] args) { // Main method, program runs here
        
        // System.out is an object used to display text in the console

        System.out.print("How "); // Prints text to console but doesn't move cursor to next line
        System.out.print("are ");
        System.out.println("you? Onto the next line!"); // Prints text and moves cursor to next line and back to the very left
        System.out.println("Hi from the next line!");

        // The argument to the print functions is a string literal (certain sequence of characters)
        // They are enclosed within " like "string literal!! 123 :)"
        
    }
}
    
```

Programs can have 3 kinds of errors:

| Type | Example | Detection |
| ---- | ------- | --------- |
| Syntax/Compiler Error | System.**ot**.println("hi") | Some IDEs detect these as you type the code, but syntax errors are found when the code is compiled, stopping compilation and so not running |
| Exception | Dividing by 0 | The code is written correctly, but as it runs a problem arises (either purposeful or because of impossibility) so it "throws an exception" and terminates |
| Logic Error | Adding 2 instead of 3 | The code is written correctly and runs correctly, but the thing you anticipated didn't happen. You made the error |