# Spring Web - Basic

Environment:
- Install Java 11
- Install Maven 3.6.3
- Install Git 2.3
- Install <b>IntelliJ 2020.3 IDEA</b> or <b>Visual Studio Code</b>

Basic codes:
- Use start.spring.io to initializr boilplate and include dependency with Spring Web
- Unzip it to loacl folder

Code changes:
- Add Controller with RquestMapping for "/" 

Issues and walkaround: 
- Build .jar, got Error (Exception in thread "main" java.lang.NoClassDefFoundError: org/springframework/boot/SpringApplication or no main manifest attribute). 
-  Option 1: https://www.youtube.com/watch?v=wPGSas_f0ts (IntelliJ setup in details)
-  Option 2: https://www.youtube.com/watch?v=7POM0bZ6yEQ change pom.xml to add <packaging>jar</packaging> and run cmd "mvn package"


