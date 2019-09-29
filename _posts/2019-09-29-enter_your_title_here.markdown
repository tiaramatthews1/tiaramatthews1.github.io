---
layout: post
title:      "Enter your title here"
date:       2019-09-29 10:51:01 +0000
permalink:  enter_your_title_here
---

Web scraping is used to extract or “scrape” data from any web page on the Internet.

Copying a list of contacts from a web directory is an example of “web scraping”. But copying and pasting details from a web page into an Excel spreadsheet works for only a small amount of data and it requires a significant amount of time. To gather larger amounts of data, automation is necessary and web scrapers perform exactly that function.

Web scraping is performed using a “web scraper” or a “bot” or a “web spider” or “web crawler” (words used interchangeably). A web-scraper is a program that goes to web pages, downloads the contents, extracts data out of the contents and then saves the data to a file or a database.

Origins of the word Web Scraping
The origins of the word are most likely from the term “screen scraping” which was widely used prior to the wide use of the web to integrate non-web based applications such as mainframe “green screens” (terminal applications) or native windows applications. These “screen scrapers” would “scrape” data from one application to be used to insert them into other applications – quite a bit from Mainframe to PC applications.

Scraping can be done in any programming language. In this post, we’re going to use Python for the simplicity of the language and the availability of packages that make the process easy.

When you’re accessing a site on the Internet, you’re essentially downloading HTML code, which is analyzed and displayed by your web browser. This HTML code contains all the information that’s visible to you. Therefore, the required information (like the price) can be obtained by analyzing this HTML code. You can use regular expressions to search for your needle in the haystack, or use a library to parse the HTML and get the required data.

Ex:

pip install beautifulsoup4


