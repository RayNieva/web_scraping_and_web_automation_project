# web_scraping_and_web_automation_project
#Web Scraping and Web Automation Project#

First two intended tools to be utilized are Python's Scrapy and next Ruby's Nokogiri

**Scrapy Installation**

![Screen Shot] (https://github.com/RayNieva/web_scraping_and_web_automation_project/blob/master/WebScrapingProjects1.png)

![test](https://github.com/RayNieva/web_scraping_and_web_automation_project/blob/master/WebScrapingProjects1.png)

Starting with 32 bit install of Scrapy on Windows 7 64 bit.  All the installation recommendations seem convoluted.
Some recommend mucking about in the registry to redefine Windows on Windows paths etc...
All require installing each component piece (lxml, twisted, Openssl, zope etc...) separately from various distribution sources. This is unlike the more modern pip install methodology used in Linux distributions.
What I found seems to work is using pip2.7.exe after installing the VC++ compiler for Python 2.7 and explicitly defining the executable C:\Python27-32bit\Python in commands. This is to get around  multiple versions of Python on the machine and a large system path variable (that you do not want to mess with especially if large programs at start up are installed that break easily like Spiceworks and Visual Studio)

Actually you might need to muck in the registry a little. As it turns out as my system path variable was very large (could not edit in control panel). I had to use an alternative. Powershell COULD NOT navigate the registry to HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Session Manager\Environment.... So had to directly modify in the registry editor by replacing c:\python34 and below  to c:\python27-32bit.. which still placed it behind the Anaconda install (Python 3.4 64bit version) but it worked.

![Screen Shot] (https://github.com/RayNieva/web_scraping_and_web_automation_project/blob/master/WebScrapingProjects1a.png)

Also system will look for win32api, but can again use pip2.7 install
![Screen Shot] (https://github.com/RayNieva/web_scraping_and_web_automation_project/blob/master/WebScrapingProjects2.png)

**Running Scrapy**
After creating project and running code.

![Screen Shot] (https://github.com/RayNieva/web_scraping_and_web_automation_project/blob/master/ezgif.com-gif-maker(3).gif)

**Will Yield an HTML File**

![Screen Shot] (https://github.com/RayNieva/web_scraping_and_web_automation_project/blob/master/WebScrapingProjects5.png)
