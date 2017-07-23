---
layout: post
title:  "Ruby Data Gem"
date:   2017-07-23 21:54:42 +0000
---


So, it took me a while to complete my first project with Flatiron, the data gem cli to be exact. I decided to make a data gem that pulled the latest financial news but when I started to attempt to scrape some of my favorite news websites, I learned how disasterious some of their source code was. I tore the project apart about 20 times and even thought about changing my project completely but I wanted to scrape a financial news website and it took about 5 days of frustration to do so. I was finally about to scrape theatlantic.com, their code was a little more clean and it was a little more clear how much better I can pull the data I needed from the website. 

The purpose of the gem was to extract the latest financial news headlines from the website, this included the publish date, author name, a short one sentence summary from the article and the link to the article if someone desired to read more. 


Below you can see how it picks lays out the news article in an ordered list style, you select the number of the article you wish to read and press enter.

![](http://imgur.com/a/EfHw9)

Once you've selected the number of the article you wish to read, it will bring the article up. It displays the article's title, date published, author, a one sentence summary of the article and the link to read more.

![](http://imgur.com/a/c4VZ9)

One other major issue that I was running into was regarding installing the gem and publishing it. I've had a lot of issues with using rubygems.org via the terminal since it was introduced in the lessons. A long web search and several hours of reading on stackoverflow let me know I wasn't alone. Some were saying you could be behind a firewall or some other proxy. I tried any fix I could including updating ruby, uninstalling rubygems as a source, uninstalling bundler and then going back in fresh and re-installing everything. Nothing seemed to work. I restored my MacBook back to factory settings and this helped a little but I am still not about to install some of the gems from rubygems.org and I cannot publish my gem to their directory. If someone has encountered this issue and has made it out successfully on the other side, please let me know




