---
title: "Technology"
date: 2021-09-14T15:45:49+01:00
draft: true
type: page
description: Technology
menu: main
weight: 20
keywords:
author: 
tags: 
---

## Websites - what are they?
Once upon a time this question was very easy to answer. In Tim Berners-Lee's original concept it was pages of text - no images - with document structures, such has headings, paragraphs, and quotations. Later came tables and images, but essentially it remained the same thing: documents. 

Nowadays websites are many different types of things. Google maps is an application on a web browser, or running on a dedicated app on a smartphone. It doesn't represent a text documents. The complexity of what we seen in our browser windows, and on our smartphone browsers, or smartphone apps, gets increasingly sophisticated and this trend will continue. But the original idea of pages of text remains, with images, and not much else. Many sites remain just that. And that means it is still possible to build a website in purely HTML if you wished to. The problem with this approach is that of being able to maintain the content in the site without all that HTML code getting in the way. 

An answer to that problem is Wordpress, and there are thousands of sites on the web using Wordpress. But sometimes old ideas come back into popularity, and one of those is that of 'static site generators'. This is another way to separate the information in a website from the presentational HTML code.  of those is that of 'static site generators' is that of websites that are text and images to take a step back to being just pure HTMLhhh  

In many respects, Wordpress over-complicates the process. A website built in Wordpress will need to use a wordpress theme - which does help to make the process easier. But if you want to modify that theme to your own needs, and you want to be able for the theme to be updated if the developer makes changes, then your only option is to create a childtheme, and this is not at all an elegant solution to this problem. Another issue with Wordpress is that its code is old, and it can be difficult to integrate its structures. 

Wordpress is also written in the PHP language, and it needs a database server. So, somebody had the brilliant idea of creating a programme that will 'spit out' your Wordpress site into pure HTML files - a static site. Why is this a good idea? Any website that relies on running code on a webserver - accessing a database, for example, and then generating pages on the fly from templates, which is what Wordpress does, is a target for the malicious types out there who want to take advantage of criminal opportunities. When a web server has only HTML pages, there is no code to run, all it has to do is send copies of those pages to the user's browser (or app), so it is very much more difficult for criminal hackers to inject and run code on websites, that might ultimately deliver nasty software to a users computer in the browser. 

It's not that I'm against Wordpress for its own sake. It will certainly be around for a long time, and especially if you can use it to generate a static site. But why use Wordpress for that, because there are better solutions. The funny thing is that in the early days of the world wide web, web hosting companies didn't want customers to put scripts in websites, the only option was static sites. I remember being told I couldn't run some navigation code on the shared Sun Sparcstation. One way around this was something called a 'static site generator'. Sometimes ideas come around again, and maybe this one is overdue a return to widespread popularity. Certainly there are umpteen of these, and now we have 'content delivery networks - or CDNs, which only accept static HTML code there are now umpteen static site generators free to download. Not only that but some CDN companies provide tools so that users can edit a website without any need to know any HTML. So what's the hitch? If a site is primarily information, then a static site generator, such as Hugo, or Gatsby, or Jeykll, are the way to go. By all means continue using Wordpress and then use Simply Static to generate the HMTL for a CDN. 


> "Everything should be made as simple as possible, but not simpler." - Albert Einstein.
