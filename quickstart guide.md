# Java
## Installation
You can install `java` from [Java official website](https://www.java.com/en/download/windows_manual.jsp) or [Oracle](https://www.oracle.com/)

I will only show that download from [Oracle](https://www.oracle.com/).

1. To install the installation app.
   1. First, visit [Java Download in Oracle](https://www.oracle.com/java/technologies/downloads/#jdk22-windows)
   2. Then according to java version you want to download, OS in device , specification in device.
   3. Then click the link to download the installation app.
2. Run installation app.
   1. Click installation app (.exe) to run the installation app.
   2. It will pop up a installation wizard. Configure the setting up then click Next.
   3. Wait.
3. Set the directory which contains `javac.exe` to system environment variable and reboot the device to make it effect (if it has been NOT set yet).

Now, you can write your java code.

## Write your first java code
1. Create a `.java` file (for example ``
2. Write a java code which looks like this in text editor (such as `VSC`) or Java IDE (such as `Eclipse`). I will explain the meaning of the following Java code.

```
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

> [!IMPORTANT]
> In a pure java code, the name of file **must** match the class name. See above example.
> And the class must contain exactly entry point named `main` which **must** be *public* and *static*.
> ```
> public static void main(String[] args) {
>     System.out.println("Hello World"); 
> }
> ```

3. To compile `Main.java`.
   1. In terminal, change directory to the directory of the file.
   2. In terminal, type `javac Main.java` and press `Enter` to execute the command.
![image](https://github.com/user-attachments/assets/315ea5ae-2b24-4a9d-bccc-a2f625150040)

> [!IMPORTANT]
> Here, you should see a file named `Main.class`.

4. To run `Main.class` file.



   
