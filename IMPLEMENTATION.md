To extract first paragraph for each article I used scraping on python with the library BeautifulSoup. However, it will create several problems.


1 - every web journal has its own HTML structure for websites. It means that when we want to extract paragraphs, we will end up
    having different results for different webpages.
    Solution - on such case it is better to write code for each web journal, as one web journal will most likely have the same HTML structure 
    for each web article. Or, we can use python library newspaper, but it also creates the following problem:
    
2 - not every web journal allows scrapping. End even if it does, it may not allow access paragraphs (due to security or basically because 
    the journal is not free). For example, WIRED does not allow to copy part of the article. Unfortunatelly, after trying to find the solution 
    to this problem, I still do not know how to deal with that. I assume that there exist some tools which allow you to scrape freely. 
    
    
To ensure that the data is complete, I manually inserted first paragraph where it was possible. 
