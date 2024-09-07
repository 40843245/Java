# Java
## data type
### primitive type (基礎型態)
#### number
##### integer
###### `short`

```
short shortNum1 = 1;
```

###### `Short`

```
Array<Short> shortArray1 = new Array<Short>();
```

###### `byte`

```
byte byteNum1 = 1;
```

###### `Byte`

```
Array<Byte> byteArray1 = new Array<Byte>();
```

###### `int`

```
int intNum1 = 1;
```

###### `Integer`

```
Array<Integer> integerArray1 = new Array<Integer>();
```
###### `long`

```
long longNum1 = 1L;
```

> [!CAUTION]
> NOT recommended
> 
> ```
> long longNum1 = 1l;
> ```
>
> since they are usually mispelled `1`(number one) `l` and (lowercase letter `l`).

```
long longNum1 = 1.0L;
```

###### `Long`

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

###### `Float`

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

###### `Double`

#### logical
##### `boolean`

It can be one of `true` or `false`.

```
boolean booleanValue = true;
```

```
boolean booleanValue = false;
```

##### `Boolean`

```
Array<Boolean> booleanArray1 = new Array<Boolean>();
```

The enum value of `Boolean` 

```
Boolean.TRUE;
```


```
Boolean.FALSE;
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

##### `Character`

```
Array<Character> characterArray1 = new Array<Character>();
```

> [!TIP]
> 1 Bytes = 8 bits

| type | how many bytes or bits does it hold? | range | range | example |
| :- | :- | :- | :- | :- |
| `byte` | 1 Byte | `-2^(8-1) ~ 2^(8-1)-1` | `-128 ~ 127` | `123 ` <br> `-125`|
| `short` | 2 Byte | `-2^(16-1) ~ 2^(16-1)-1` | `-32,768 ~ 32,767` | `235` <br> `-367`|
| `int` | 4 Byte | `-2^(32-1) ~ 2^(32-1)-1` | `-2,147,483,648 ~ 2,147,483,647` | `214,748,364` <br> `-2,147,483,646`|
| `boolean` | 1 bit |  |  | `true` <br> `false`|
| `char` | 2 Byte | ascii code in `0 ~ 2^16-1` | ascii code `0 ~ 65535` | `A`<br> `\n` <br> `\0` <br> `\u0`<br> `\u65535` <br> `\u100`|


To known its min value and max value of primitive type, use the enum value of the class. See the following example.

`Range.java`

```
public class Range{
	public static void main(String[] args){
		System.out.printf("The min of byte:%d, the max of byte:%d.%n", Byte.MIN_VALUE,Byte.MAX_VALUE);
		System.out.printf("The min of short:%d, the max of short:%d.%n", Short.MIN_VALUE,Short.MAX_VALUE);
		System.out.printf("The min of int:%d, the max of int:%d.%n", Integer.MIN_VALUE,Integer.MAX_VALUE);
		System.out.printf("The min of long:%d, the max of long:%d.%n", Long.MIN_VALUE,Long.MAX_VALUE);
		System.out.printf("The min of char:%h, the max of char:%h.%n", Character.MIN_VALUE,Character.MAX_VALUE);
		System.out.printf("The true value in boolean:%b, The false value in boolean:%b.%n", Boolean.TRUE,Boolean.FALSE);
	}
  }

```
