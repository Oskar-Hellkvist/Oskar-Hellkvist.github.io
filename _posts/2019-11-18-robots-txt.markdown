---
layout: post
title:  "Robots.txt"
date:   2019-11-18 23:22:33 +0100
categories: robots txt 
comments: true
---

I chose to have it open for everything and allow everything since it will probably be the solution that the least in the way during this project.
I don't really have anything to keep away from bots on the site so this will do just fine.
```
User-Agent: *
Disallowed:
```
## What is robots.txt used for?
The robots.txt file is a file that the webmaster creates in order to tell web crawlers how to navigate the website and what is allowed and what isn't.
### User-Agent field
The user-agent field is used to tell web crawlers what user-agents that are allowed on certain parts of the website.
### Disallowed field
The disallowed field indicates what parts of the website robots are not allowed to traverse. This could be some internal parts of the website that should not be indexed on the internet. In the disallowed field you specify the URL in string format.
