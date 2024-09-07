# Java
## Syntax
### output
> [!IMPORTANT]
> `System` is in `java.lang` class.
>
> However, by default `java.lang` is imported.
>
> Thus, it is NOT needed to import it by `import java.lang.*;`

For example, 

to print `Hello, World!` with new line.

```
System.out.println("Hello, World!");
```

> [!TIP]
> + To simply print without new line, use `print` method.
> + To simply print with new line, use `println` method.
> + To print with format without new line, use `printf` method.


### copy 
#### shallow copy
- For all types.
+ `=`

- For array.
+ `java.lang.System.arraycopy` method.
+ `java.util.Arrays.copy` method.

or simply use a `for` loop to shallow copy each elements.
### comparison
#### referential comparison
1. `==`: compare two instances points to same reference.
2. `!=`: opposite of `==`

#### non-referential comparison
1. `equals` method: compare values of two instance are same.

> [!NOTES]
> There are no `notequals` method in Java.
>
> To compare values of two instance are NOT same.
>
> One can use negation and `equals` method.

### get input
To get input from input stream in Java, follow these steps.

1. create an instance of `Scanner` class with input stream as an argument. As follows.

```
var scanner = new Scanner(System.in);
```

2. call its method to get inputs. For example

```
var line = scanner.nextLine();
```

> [!IMPORTANT]
> The `Scanner` is in `java.util` class, thus, please import it by `import java.util.Scanner;` at the begin of the code (Of course, there are many way).
## reference
I will provide some links about Java.

+ [Java w3school](https://www.w3schools.com/java/)
