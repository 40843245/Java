# Java
## syntax
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
- For all non-primitive type. (Including `String`, for more details, see [`String` section in data type.md](#string))
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

2. `>` : greater than (gt)
3. `<` : less than (lt)
4. `>=` : greater than or equal to (ge)
5. `<=` : less than or equal to (le)

### logical operator

> [!CAUTION]
> It has feature, short-circuit evaluation.

| logical operator | meaning | expression | `a` | `b` | result |
| :- | :- | :- | :- | :- | :- |
| `&&` | `and` | `a&&b` | `true` | `true` | `true`|
| `&&` | `and` | `a&&b` | `false` | `true` | `false`|
| `&&` | `and` | `a&&b` | `true` | `false` | `false`|
| `&&` | `and` | `a&&b` | `false` | `false` | `false`|

| logical operator | meaning | expression | `a` | `b` | result |
| :- | :- | :- | :- | :- | :- |
| `\|\|` | `or` | `a\|\|b` | `true` | `true` | `true`|
| `\|\|` | `or` | `a\|\|b` | `false` | `true` | `true`|
| `\|\|` | `or` | `a\|\|b` | `true` | `false` | `true`|
| `\|\|` | `or` | `a\|\|b` | `false` | `false` | `false`|

| logical operator | meaning | expression | `a` | result |
| :- | :- | :- | :- | :- |
| `!` | `not` | `!a` | `true` | `false` | 
| `!` | `not` | `!a` | `false` | `true` | 

### bitwise operator

| bitwise operator | meaning | expression |
| :- | :- | :- |
| `&` | `bitwise and` | `a&b` |
| `\|` | `bitwise or` | `a\|b` |
| `~` | `bitwise not` | `~a` |
| `^` | `bitwise xor` | `a^b` |

| bitwise operator | meaning | expression |
| :- | :- | :- |
| `<<` | `left shift` | `a<<b` |
| `>>` | `right shift` | `a>>b` |


### input
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
