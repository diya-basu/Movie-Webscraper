# Movie-Webscraper
WebScraper: The greatest movies of all time.

**What are webscrapers? **
Suppose you want some information from a website? Let’s say a paragraph on irrigation. The most intuitive way is to search it up on google and then copy and paste it to your own file. But what if you want to get large amounts of information from a website as quickly as possible? Such as large amounts of data from a website to train a Machine Learning algorithm? And that’s when you’ll need to use Web Scraping.Unlike the long and mind-numbing process of manually getting data, Web scraping uses intelligence automation methods to get thousands or even millions of data sets in a smaller amount of time. 

Empire published an article a couple of years ago, containing a list of 100 movies of all time. In an attempt to understand this deceptively complicated process of gathering data and information from a website we shall be using the Beautiful Soup module available in python which is used to derive copious amounts of data from websites by utilising the tags the data is enclosed under. 

So to derive the data from empire’s website, say the hundred greatest movies of all time, we have to first study the website itself. This part is simple: navigate to any webpage: right click on it and select Inspect. This opens up the underlying html css and javascript codes used to design the webpage. Now if navigated to the specific headers, the html tags enclosing information can be clearly seen. Now using Beautiful soup module, this information can be derived from the website to analyse and perform data processing operations. 

**Conclusion:** 
This project aims to develop a more synthetic way of deriving data from websites for processing and analysis purposes to provide a much more easier way of data collection which can be further utilised to train machine learning models. 
