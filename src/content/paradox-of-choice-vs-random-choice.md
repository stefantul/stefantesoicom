---
templateKey: blog-post
title: "Paradox of Choice vs. Random Choice"
date: "2018-05-12"
description: >-
  Paradox of Choice vs. Random Choice
featuredpost: false
featuredimage: /img/Selection_028.png
tags:
  - paradox of choice
  - random choice
---

**The Paradox of Choice** occurs in situations when you have to chose between multiple options that have similar levels of appeal. For example, it's easy to chose between three flavors of ice cream but when you have to chose between thirty flavors of ice cream you are most likely to succumb to the paradox of choice, you weight the pros and cons of choosing a flavor over another one  and this makes your choice much harder.

If you are like me and have an open mind, have an expanded horizon and various subjects you are interested in, you might be faced with the paradox of choice when it comes to selecting the next activity you should do. For example, I have a file with various things that I'm interested in and like to do, each one of these things written on a line: reading, playing chess, learning foreign languages, writing and so on. So when I'm feeling bored and lacking the inspiration on knowing what to do next, I look into this file and select something to do. The problem is, sometimes multiple options are equally attractive and I get into an analysis paralysis and I end up doing nothing.

So I wrote a script as a solution for these types of situations, a simple script in Python that reads the file containing the random activities and interests and randomly prints out one of them in the console. That's it. I only see one option and go with it. Does this solution work? It works for me. I outsource my decision making process to a simple script that does all the work for me.

> import random
> 
> f = open('randoms', 'r') randoms = f.readlines() f.close()
> 
> print(random.choice(randoms))
> 
> * * *

![Paradox of Choice Vs. Random Choice python script](https://stefantesoi.com/wp-content/uploads/2018/05/Selection_028.png)

Python even has one neat function called choice. **Random choice**. A good solution to the Paradox of Choice.
