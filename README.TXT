========================
BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).========================
BUILD OUTPUT DESCRIPTION
========================

When you build an Java application project that has a main class, the IDE
automatically copies all of the JAR
files on the projects classpath to your projects dist/lib folder. The IDE
also adds each of the JAR files to the Class-Path element in the application
JAR files manifest file (MANIFEST.MF).

Ensure that you have Java installed: JAR files require Java to be installed on your system. 
You can verify if Java is installed by opening a terminal or command prompt and running the following command:

java --version
If Java is installed, you will see the version information.
If not, you will need to download and install Java from the official website (https://www.java.com).

Locate the JAR file: Find the JAR file you want to run on your computer. Make sure you know its file path.

Open a terminal or command prompt: Open a terminal or Navigate to the directory containing the JAR file:
Run the JAR file in command prompt: Once you are in the directory containing the JAR file, use the following command to run it:

java -jar <filename>.jar

Replace <filename> with the actual name of the JAR file. 

java -jar siCalculator.jar

Press Enter to execute the command: After entering the command, press Enter, and Java will execute the JAR file.
To run the project directly:
download the jar file and if any other lib folder and un the jar file. It will execute as an exe file.


To run the project from the command line, go to the dist folder and
type the following:

java -jar "siCalculator.jar" 

To distribute this project, zip up the dist folder (including the lib folder)
and distribute the ZIP file.

Notes:

* If two JAR files on the project classpath have the same name, only the first
JAR file is copied to the lib folder.
* Only JAR files are copied to the lib folder.
If the classpath contains other types of files or folders, these files (folders)
are not copied.
* If a library on the projects classpath also has a Class-Path element
specified in the manifest,the content of the Class-Path element has to be on
the projects runtime path.
* To set a main class in a standard Java project, right-click the project node
in the Projects window and choose Properties. Then click Run and enter the
class name in the Main Class field. Alternatively, you can manually type the
class name in the manifest Main-Class element.
