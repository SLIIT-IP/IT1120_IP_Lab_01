# IT1120_IP_Lab_01
# Part A – Java Setup

## JDK Download
1. Visit Oracle Java Download Page: [Oracle Java Download Page](https://www.oracle.com/java/technologies/downloads/)
2. Select Java Version: Select the latest Java Development Kit (JDK) version. In this example, JDK 22 is selected.
3. Choose Your Operating System: Click on the appropriate download link for your operating system (Windows, macOS, Linux).
4. Download the Installer: For Windows, select the link for the `x64 Installer` to begin downloading the file named: `jdk-22_windows-x64_bin.exe`
5. Complete the Installation: Once downloaded, run the `jdk-22_windows-x64_bin.exe` file and follow the on-screen instructions to install Java.

## Java Environment Home Path Setup
1. Locate Installation Directory: Java installation default location is:
  
3. Open System Properties:
- **Open the Start Menu:** Click on the Start button or press the Windows key.
- **Access Control Panel:** Type `Control Panel` into the search box and click on it from the search results.
- **System and Security:** In the Control Panel, click on `System and Security`.
- **System:** Click on `System`.
- **Advanced System Settings:** Click `Advanced system settings` on the right side.
3. Environment Variables: In System Properties window under `Advanced` tab click on the `Environment Variables` button.
4. Select JAVA_HOME: In the System variables section click `New` to create a new variable:
- **Set Variable name:** `JAVA_HOME`
- **Set Variable value:** the path to your Java installation e.g:
  ```
  C:\Program Files\Java\jdk-22
  ```

## Update Path Variable
1. Select the `Path` variable under `System Variables` and click `Edit` button.
2. Click `New` and add:
3. 3. Confirm Changes: Click `OK` to apply the changes.

## Verify The Installation (Java Version Check)
1. Open Command Prompt.
2. Check Java Version: Type `java -version` in the command prompt and press Enter.

# Part B – Java Hello World Program

## Create a Folder
1. In Desktop of your computer, create a New Folder named: `Lab 1`
2. Open Notepad: Start Notepad on your computer to begin writing your program.

## Hello World Program
In Notepad, write your first Hello World Java program as below:
```java
public class Lab1Q1 {
 public static void main(String[] args) {
     System.out.println("Hello World! - ITxx xxx xxx");
 }
}

