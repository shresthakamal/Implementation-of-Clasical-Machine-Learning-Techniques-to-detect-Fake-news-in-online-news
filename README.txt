1)  open

https://newsapi.org/v2/everything?sources=news-com-au&apiKey=adc35e2c9d0144f4affee4b50a239b28


2) open 
http://convertcsv.com/json-to-csv.htm


3)open

https://newsapi.org/sources

/*get the name tag of all the sources from this site and replace it the no 1) site after sources="name-tag" */

4)once you open the link 1), with your appropriate API key, and required source, you will get all the news from that site listed in the main page of the website you are looking at

5) copy the given source code from the 1) site and paste it into "Enter Data" section of no 2) site

6)Convert Json to CSV

7)Download CSV


8) to download news from multiple sites:
	a)at first you need to copy all the source code from the first website
	b) then you need to copy the source code only from {"source":{"id":.................}
	c) then you need to paste the second source code at the end of first source code }here]} or before ]} by separating it with a comma:

eg:

	FIRST_SOURCE_CODE.... is that few people have noticed.\r\n… [+4519 chars]"},{"source":{"id":"news-com-au".....SECOND_SOURCE_CODE


9)COPY THE OVERALL SOURCE CODE AND CONVERT TO CSV FILE LIKE BEFORE....

10)ENJOY!!




