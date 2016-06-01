# web_scraping_and_web_automation_project
#Web Scraping and Web Automation Project#

**Installation**

![Screen Shot] (https://github.com/RayNieva/web_scraping_and_web_automation_project/blob/master/WebScrapingProjects1.png)

Starting with 32 bit install of Scrapy on Windows 7 64 bit.  All the installation recommendations seem convoluted.
Some recommend mucking about in the registry to redefine Windows on Windows paths etc...
All require installing each component piece (lxml, twisted, Openssl, zope etc...) separately from various distribution sources. This is unlike the more modern pip install methodology used in Linux distributions.
What I found seems to work is using pip2.7.exe after installing the VC++ compiler for Python 2.7 and explicitly defining the executable C:\Python27-32bit\Python in commands. This is to get around  multiple versions of Python on the machine and a large system path variable (that you do not want to mess with especially if large programs at start up are installed that break easily like Spiceworks and Visual Studio)
