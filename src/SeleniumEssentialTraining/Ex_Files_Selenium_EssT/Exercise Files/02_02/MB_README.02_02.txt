Update JDK. See Notes.txt in course base dir.

Go to start/test
cp KeyboardAndMouseInput.java KeyboardandMouseInput.java.org

Update path to chromedriver to
/Users/marco/IdeaProjects/SeleniumEssentialTraining/src/SeleniumEssentialTraining

# Plain compile and run
https://www.tutorialspoint.com/How-to-run-a-java-program

Build:
/usr/bin/javac KeyboardAndMouseInput.java

KeyboardAndMouseInput.java:1: error: package org.openqa.selenium.chrome does not exist

javac -help 
Include CLASSPATH

javac -classpath 
javac -cp 

javac -cp  /Users/marco/IdeaProjects/SeleniumEssentialTraining/Src/SeleniumEssentialTraining/selenium-java -cp /Users/marco/IdeaProjects/SeleniumEssentialTraining/Src/SeleniumEssentialTraining/selenium-java/libs KeyboardAndMouseInput.java

Run
/usr/bin/java KeyboardAndMouseInput.java

