# Web_scrapping_walkthrough
Basic web scrapping resources .

I am basically following this blog for guideline:https://medium.com/analytics-vidhya/web-scraping-in-python-a-beginners-guide-5fdec8c1c775
As I wanted to know more about selenium, I followed this: https://www.youtube.com/watch?v=Xjv1sY630Uc



Selenium is a framework that can grab source code informations from any website and make easy interaction possible which leads to creation of bots,filling up forms,using search field and so on.

* to install : pip install selenium
  check if import selenium showing error or not. ( showing error may indicate the package is not installed in right python interpretor)

* Chrome webdriver installation:
  follow the link: https://sites.google.com/a/chromium.org/chromedriver/downloads
  find out the version of existing google chrome from > help > about google chrome > version will be there.
  Download the corresponding version from web driver.
  **REMEMBER THE FILE PATH.**
  
<h1> Opening a webpage <h1>
  
  Now to work with selenium and web driver, write 
  from selenium import webdriver
  PATH= "path where webdriver is on your machine/chromewebdriver.exe"
  choose driver by writing driver= webdriver.Chrome - other options like firefox phantom js all are available there.
  inside that, assign path variable defined above and it look like driver= webdriver.Chrome(PATH).
  Using Driver.get() method we will open any page that allows webscrapping.Pass url as parameter.Run the code and the page will be loaded in the browser.
  


