# Built a Simple Crawler to Scrapy the Information on a Recipe Website  
## STEP 1 Get the content of webpages.  
import requests -Package use to get the content of the webpages.  
Two methods to get get the content of the webpage: Request.post  
and request.get  
Here I use request.get  

## STEP 2 Parse the webpage: Get the information we want in the web page.  
After we got the content of the page, try to get the information we want in the page.  
### Beautiful Soup
is a Python library for pulling data out of HTML and XML files. We
can use it to simply navigate, search, and modify the parse tree.
Or  
### Regular Expression  
is a sequence of characters that define a search pattern. Usually
such patterns are used by string searching algorithms for "find" or
"find and replace" operations on strings, or for input validation.

## STEP 3 ‘for loop’ or ‘while loop’ to repeat step 1 and step 2 to get all pages of the website.
Use ‘for loop’ to repeat step 1 and step 2 to get all links on the main pages.  
Once we got all the links on the main pages,
Repeat the request and parse steps to get the content of each link
and search the information we want in the content of each link.
