# Selenium Automation using Selenium IDE and JAVA 
Example of using Selenium to test a web application using Javascript 
 

 ////////////////////////////// 
	Selenium IDE setup on ubuntu 
 ////////////////////////////// 
  
 #Install Chrome Driver required to run automated test cases.  
sudo apt-get update 
sudo apt-get install chromium-chromedriver 
sudo ln -s /usr/lib/chromium-browser/chromedriver /usr/local/share/chromedriver 

#Install Firefox version 52 required for Selenium IDE  
sudo apt-get purge firefox 
sudo apt-get update 
wget http://ftp.mozilla.org/pub/firefox/releases/52.5.0esr/linux-x86_64/en-US/firefox-52.5.0esr.tar.bz2 
sudo tar -xjf  firefox-52.5.0esr.tar.bz2 
sudo rm -rf /opt/firefox52 
sudo mv firefox /opt/firefox52 
sudo mv /usr/bin/firefox /usr/bin/firefoxold 
sudo ln -s /opt/firefox52/firefox /usr/bin/firefox 
firefox  

#Go to Firefox menu ->  Tools - Addons - Search - Selenium IDE - select and install.  
#Open Selenium IDE, record and play the test cases. 
  
  Open firefox - and open following url: 
  https://addons.mozilla.org/en-US/firefox/addon/selenium-ide/ 
  Click on Add to Firefox -> Install -> Restart firefox 
  Goto -> Tools -> Selnium IDE -> 
  You can Record/Play/Export the test cases with Selenium IDE. 
  
  
  
 ////////////////////////////// 
	Running Selenium Test Cases project 
 ////////////////////////////// 
   
Clone this project 
mvn clean compile install 
 
 
//////////////////////////////////////// 
	 
Selenium Video Tutorials: 
https://www.youtube.com/watch?v=bFFcbB0AJDM 
https://www.youtube.com/watch?v=-DrCWCjTKBk 
Selenium for Node: https://www.youtube.com/watch?v=YlS9saA3A5U 
	 
	 
Selenium Tutorials: 
http://toolsqa.com/selenium-tutorial/ 
http://www.seleniumhq.org/download/ 
https://www.npmjs.com/package/selenium-webdriver	 
http://www.software-testing-tutorials-automation.com/p/learn-selenium-ide.html 
https://github.com/dineshmetkari/CucumberSeleniumTestExample.git 
