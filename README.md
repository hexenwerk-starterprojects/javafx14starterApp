# HelloFX Sample

JavaFX 13 HelloFX sample to run with different options and build tools.

Download [JDK 11 or later](http://jdk.java.net/) for your operating system.
Make sure `JAVA_HOME` is properly set to the JDK installation directory. 

## Maven

### Linux / Mac

If you run on Linux or Mac, follow these steps:

    cd HelloFX/Maven/hellofx
    
To compile and run the project:
    
    mvn clean javafx:run

### Windows

If you run on Windows, follow these steps:

    cd HelloFX\Maven\hellofx

To run the project:
    
    mvn clean javafx:run
    
### Intellij 

If you run main class from Intellij Runner, set the following VM parameters

    --module-path c:\tools\JavaFx\javafx-sdk-14.0.2.1\lib\ --add-modules javafx.controls