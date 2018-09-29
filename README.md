# Selenium Smoke Test script
It will open all the menu pages and copy the title of the page. The copied title is displayed in eclipse console page. </br>

Installation steps for selenium:</br>
1) Install Java Software Development Kit (JDK) 9http://www.oracle.com/technetwork/java/javase/downloads/index.html</br>
2) Download eclipse and Install http://www.eclipse.org/downloads/ </br>
3) Download selenium java (http://seleniumhq.org/download/) </br>
4) Open Eclipse and import the dowloaded file from Github MarketBase.zip  (https://github.com/TSQAteam/Selenium-Market-Base-Smoke-Test-script) </br>
5) Right click Project and click Properties </br>
6) Add Library files Properities > Java build path > Libraries > Add External Jars </br>
7) Browse selenium downloaded extracted file path and import the jars. (All jars inside the selenium folders) </br>
8) Double click the DevUnitTest.java file in Market base > src > AutomationFramework </br>
9) Set the system property in System.setProperty("webdriver.gecko.driver", "E:\\Selenium\\geckodriver-v0.17.0-win64\\geckodriver.exe"). geckodriver exe file was uploaded in github. pls download and  set the path like this. </br>
10) Enter the user name and password in sendkeys("") below the code //user name and //Password </br>
11) Update the 5000ms for all Thread.sleep(5000); </br>
12) Click Run button (Top left - Green play button) </br>
13) Output will be printed in Eclipse > console </br>

Refer the website for selemium installation guide: https://www.guru99.com/installing-selenium-webdriver.html </br>

Java Development Kit (JDK). http://www.oracle.com/technetwork/java/javase/downloads/index.html </br>
Eclipse IDE - http://www.eclipse.org/downloads/ </br>
Java Client Driver - http://seleniumhq.org/download/ </br>
