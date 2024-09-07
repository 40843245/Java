# Java
## data type
### reference type (參考型態)
Alias as `class type`.

#### string
##### `String`

`""` refers String literal (字串常量)

```
public class StringEx {
	public static void main(String[] args) {
		var name1 = "Justin";
		var name2 = "Justin";
		var name3 = new String("Justin");
		var name4 = new String("Justin");

		System.out.println(name1==name1);
		System.out.println(name1==name2);
		System.out.println(name2==name3);
		System.out.println(name3==name4);

		System.out.println(name1.equals(name1));
		System.out.println(name1.equals(name2));
		System.out.println(name2.equals(name3));
		System.out.println(name3.equals(name4));
	}
}

```

```
public class StringEx2 {
	public static void main(String[] args) {
		var str1 = "Ja" + "va";
		var str2 = "Java";

		System.out.println(str1==str2);
		
		System.out.println(str1.equals(str2));
	}
}

```
### class type (類別型態)
Alias as `reference type`.

> [!TIP]
> `class type` is an alias of `reference type`, but I highly recommend not to call it as `class type` since it is usually confused with `class` type.
