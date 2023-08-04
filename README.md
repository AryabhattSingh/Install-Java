# Installing Java and Running Java Programs

This README file provides step-by-step instructions on how to download and install Java on your system and how to run a Java program. It also explains whether it is possible to run a Java program with only the Java Runtime Environment (JRE) installed.

## Installing Java

To run Java programs on your system, you need to install the Java Development Kit (JDK). The JDK includes both the Java Runtime Environment (JRE) and tools required for Java development.

Follow these steps to install Java on your system:

1. **Download JDK:** Visit the official Oracle website or OpenJDK website to download the latest version of the JDK for your operating system. Ensure you download the appropriate version (e.g., Windows, macOS, or Linux) and select the appropriate architecture (e.g., 32-bit or 64-bit) based on your system.

2. **Install JDK:** Run the downloaded installer and follow the on-screen instructions to install the JDK on your system.

3. **Set Environment Variables (Optional):** After installation, you may need to set the "PATH" environment variable to point to the JDK's "bin" directory. This allows you to run Java commands from any location in your terminal or command prompt.

4. **Verify Installation:** Open a terminal or command prompt and type the following command:

```bash
java -version
```

This command should display the installed Java version, confirming that Java is successfully installed on your system.

## Running a Java Program

Once you have Java installed on your system, you can run Java programs using the Java Development Kit (JDK). Here's how:

1. **Write a Java Program:** Create a Java source file with the extension ".java" containing your Java program's code. For example, create a file named "MyProgram.java" with the following content:

```java
public class MyProgram {
    public static void main(String[] args) {
        System.out.println("Hello, Java World!");
    }
}
```

2. **Compile the Java Program:** Open a terminal or command prompt, navigate to the directory containing your Java source file, and use the "javac" command to compile the program:

```bash
javac MyProgram.java
```

This command will generate a bytecode file named "MyProgram.class" if there are no compilation errors.

3. **Run the Java Program:** After successfully compiling the program, use the "java" command to run it:

```bash
java MyProgram
```

The output will display:

```
Hello, Java World!
```

Congratulations! You have successfully executed a Java program on your system.

## Running a Java Program with JRE only

The Java Runtime Environment (JRE) is sufficient to run Java programs that have already been compiled into bytecode. However, it does not include the Java compiler ("javac"), which is necessary to compile Java source files. Therefore, you can run a Java program with only the JRE installed if you have the compiled ".class" files.

For example, if you have a compiled Java program named "MyProgram.class," you can run it using the JRE as follows:

```bash
java MyProgram
```

However, if you want to modify or develop Java programs, you need the full JDK, which includes the compiler and other development tools.

That's it! You now know how to download, install, and run Java on your system, and understand the difference between using JRE and JDK for running Java programs. Happy coding!
