## Platform-independent
Java prograns run on most operating systems and are not tied to specific hardware.
- Java programs can run on Linux, Windows, macOS, etc.
- Programs don't run directly on the OS, but in a `Java Virtual Machine` (JVM)
- There are JVMs available for most platforms.
- Java programs run on any `JVM-regardless pf underlying OS`.

### Java Virtual Machine
The `Java Program` we want this to run on any combination of operating system and hardware. That is, whether your machine runs an Intel microprocessor or one developed by AMD,
the program should just run and you should not have to develop a separate program for each different configuration of hardware

![image](https://github.com/user-attachments/assets/211736f6-7e05-4b46-b466-528c719cd241)

OS will handle all the things for us:
![image](https://github.com/user-attachments/assets/c989fa96-4f8a-4c22-8956-d2d932918c43)

But each operating system has its own set of system calls which means the java program will eventually need to translated to those calls. So, its very hard for a developer to handle different code for different OS and for that developer needs knowledge about OS and Java language both. So as a solution we can add a extra layer between OS and our Java program, then our code will not tightly coupled on the platform in which the code runs.
The extra layer in the interaction is the `Java Virtual Machine`.

![image](https://github.com/user-attachments/assets/fd8d8211-bc18-4faf-a7d6-1cacc6dbe3d9)

There are different JVM for different OS

![image](https://github.com/user-attachments/assets/e94fc055-8451-4671-9e32-2efc7416668e)



