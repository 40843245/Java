# Java
## data type
### primitive type (基礎型態)
#### number
##### integer
###### `short`

```
short shortNum1 = 1;
```

###### `byte`

```
byte byteNum1 = 1;
```

###### `int`

```
int intNum1 = 1;
```

> [!TIP]
> 1 Bytes = 8 bits

| type | how many bytes does it hold? | range | range | example |
| :- | :- | :- | :- | :- |
| `byte` | 1 Byte | `-2^(8-1) ~ 2^(8-1)-1` | `-128 ~ 127` | `123 ` <br> `-125`|
| `short` | 2 Byte | `-2^(16-1) ~ 2^(16-1)-1` | `-32,768 ~ 32,767` | `235` <br> `-367`|
| `int` | 4 Byte | `-2^(32-1) ~ 2^(32-1)-1` | `-2,147,483,648 ~ 2,147,483,647` | `214,748,364` <br> `-2,147,483,646`|

###### `Integer`

```
Array<Integer> integerArray1 = new Array<Integer>();
```


##### floating number
###### `float`

```
float floatNum1 = 1.0F;
```

```
float floatNum2 = 1.0f;
```

###### `double`

```
double doubleNum1 = 1.0;
```

```
double doubleNum2 = 1.0D;
```

```
double doubleNum3 = 1.0d;
```

#### logical
##### `boolean`

It can be one of `true` or `false`.

```
boolean booleanValue = true;
```

```
boolean booleanValue = false;
```

#### letter
##### `char`

```
char letter`` = 'A';
```

```
char letter2` = '\n';
```

```
char letter3` = '\u0123';
```

```
char letter4` = '\0';
```

