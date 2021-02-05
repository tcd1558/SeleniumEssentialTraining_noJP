
https://www.jetbrains.com/help/idea/creating-and-running-your-first-java-application.html

Requires the Selenium Java packages:

https://selenium.dev/downloads
	Selenium Client & WebDriver Language Bindings
	Language:Java;  use the green 'Download'

In the project create a directory selenium_java
move the downloaded file into the directory selenium_jave and extract in there
Right click the project and select 'Reload from Disk'

org.openqa.selenium.* 
Add all jar files with 
	Highlight the Project (01_04)
	File > Project Structure (or CMD+;)
	Project Setting > Libraries > click on the '+' in the middle pannel
	New Project Library > Java
	An explorer window pops up. Navigate to selenium-java
	Select all *.jar libs/*.jar files, click on [open], click on [ok]
	When all of them are listed, click on [ok]

Click on the green run triangle 
	Run TestSample.java.main{}

https://stackoverflow.com/questions/16742085/adding-jar-files-to-intellijidea-classpath

It's 2018. It's a better idea to use a dependency manager like Maven and externalize your dependencies.
