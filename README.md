# Simple Spring Web Application

## Environment:
- Install Java 11
- Install Maven 3.6.3
- Install Git 2.3
- Install <b>IntelliJ 2020.3 IDEA</b> or <b>Visual Studio Code</b>

## Basic codes:
- Use start.spring.io to initializr boilerplate and include dependency with Spring Web
- Unzip it to local folder

## Code changes:
- Add @RestController with @RequestMapping for "/" 

## Issues and walkaround: 
- Build .jar, when run 'java -jar *.jar' got Error (Exception in thread "main" java.lang.NoClassDefFoundError: org/springframework/boot/SpringApplication or no main manifest attribute). 
-  Option 1: https://www.youtube.com/watch?v=wPGSas_f0ts (IntelliJ setup in details) - Basically File->Project Structure->Artifacts-> + -> Jar -> Empty -> click .jar -> Add Manifest file and main class -> + (output Layout) -> add Module output -> add library files -> OK -> Build -> Rebuild Project -> Build Artifact -> * -> Rebuild
-  Option 1: is to make sure Manifest and main class are all included properly in IntelliJ Project 
-  Option 2: https://www.youtube.com/watch?v=7POM0bZ6yEQ change pom.xml to add <packaging>jar</packaging> and run cmd "mvn package"


