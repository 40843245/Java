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
2. Write a java code which looks like this in text editor (such as `VSC`) or Java IDE (such as `Eclipse`). I will explain the meaning of the following Java code in later section.

```
public class Main {
  public static void main(String[] args) {
    // TODO
   System.out.println("Hello World");
  }
}
```

> [!IMPORTANT]
> In a pure java code, the name of file **must** match the class name. See above example.
> And the class must contain exactly one entry point named `main` which **must** be *public* and *static*.
> The declaration of `main` is shown as follows.
> ```
> public static void main(String[] args) {
>     // TODO
> }
> ```

3. To compile `Main.java`.
   1. In terminal, change directory to the directory of the file.
   2. In terminal, type `javac Main.java` and press `Enter` to execute the command.

> [!IMPORTANT]
> Here, you should see a file named `Main.class` if there are NO errors.
> If there are compilation errors, see the error message and fix it. (The issues are usually about your Java code.)
> If there are NO compilation errors, but there are other error message, also see the error message and fix it. (But the issues are usually about command that you've just entered.)

4. To run `Main.class` file.
   1. In terminal, type `java Main` and press `Enter`. <br> Now you will see Output `Hello World`.

> [!IMPORTANT]
> **DON'T** type `java Main.class` in terminal. Type `java Main`.

Figure to illustrate the example.

![image](https://github.com/user-attachments/assets/315ea5ae-2b24-4a9d-bccc-a2f625150040)

![image](https://github.com/user-attachments/assets/cf8d0c84-f25c-4845-9c43-08ac7aaaf220)

![image](https://github.com/user-attachments/assets/99eb513b-d8d2-42a6-bdae-0e0f02287a6d)

### Demo
For demo, see my YT video
+ [Set system environment variable in Windows 11](https://www.youtube.com/watch?v=cuumLQEDRtc)
+ [compile .java file in terminal in Windows 11](https://www.youtube.com/watch?v=FqZhTjDUnDs)
+ [execute .class file in terminal in Windows 11](https://www.youtube.com/watch?v=e8xkB5fm6Qg)


## Syntax
