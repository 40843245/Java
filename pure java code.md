# Java
## pure java code

In `Main.java`, the code should look like this:

```
public class Main {
  public static void main(String[] args) {
    // TODO
    System.out.println("Hello World");
  }
}
```

In the above example, it will print output `Hello World`.

> [!IMPORTANT]
> In a pure java code, the name of file **must** match the class name. See above example.
> And the class must contain exactly one entry point named `main` which **must** be *public* and *static*.
> The declaration of `main` is shown as follows.
> ```
> public static void main(String[] args) {
>     // TODO
> }
> ```

> [!NOTE]
> Entry point of `.java` file is `main` method, `public static void main(String[] args)`.

> [!NOTE]
> Here `args` is an String array that stores argument when executing `.class` file.

For example, 
+ type `java Main`, the args will be an empty String array.
+ type `java Main "Nice to meet you."`, the args will be a String array with length 1. And the first elem of args (i.e. `args[0]` will be `"Nice to meet you."`)


> 
