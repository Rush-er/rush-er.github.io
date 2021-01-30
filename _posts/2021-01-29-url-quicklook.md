---
title: "Dive into the internet"
layout: post
date: 2021-01-29 20:00:00 +0100
image: /assets/images/social.png
headerImage: false
tag:
- url
- internet
- blog
star: true
category: blog
author: matis
description: URL pishing/scamming
---
So this week i thinked about the internet and i came up with an idea.

Let's start with something basic and simple before digging furthermore; internet is a place where you can find a lot of thinkgs like my **Instagram profile** nickname _Wasteland_ :P
[https://instagram.com.wasteland-user-link-url-ekcj1bx9defk3r17c73hske1like7rmnc31kcec.xyz](https://instagram.com.wasteland-user-link-url-ekcj1bx9defk3r17c73hske1like7rmnc31kcec.xyz)


![](https://i.imgur.com/qWsbHBl.png)

> My personal profile

Let's start with the real thing, if you clicked on my **Instagram profile** URL you just get redirected to my blog page, let's find out why after a quick introduction to URLS.
### URL meaning and schema
URL stands for Uniform Resource Locator. A URL is nothing more than the address of a given unique resource on the Web.

Nowadays it's really easy to get fooled with URLS, this happens because people doesn't know how a URL works;
for a URL to works you need:
1. Protocol
2. Domain
3. Path to file

After this we can proced with an exemple.
Base URL [https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_URL](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_URL)
1. Protocol --> **https:**
2. Domain --> **developer[]().mozilla.org**
3. Path to file --> **/en-US/docs/Learn/Common_questions/What_is_a_URL**

Now that you know the basics of URL we can take a look on my Instagram profile URL,
this is the URL https://instagram.com.wasteland-user-link-url-ekcj1bx9defk3r17c73hske1like7rmnc31kcec.xyz, we can divide it like before:

1. Protocol --> **https:**
2. Domain --> **wasteland-user-link-url-ekcj1bx9defk3r17c73hske1like7rmnc31kcec[]().xyz**
3. Path to file --> Nothing !

In this case i manipulate my url domain to act like as a normal _Path to file_, the **instagram[]().com** domain it's just a wildcard to my real domain.
After this you may think how to find the real domain of the URL, it's really simple, just find the last --> . <-- of the URL, after that you always find a TLD like **.com**, **.it**, **.org**, etc..

The domain name we used in the first exemple is divided like this
![](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name/structure.png)

So after all this why my URL was bad ?
It's was bad because i used it to rediret whatever i liked, in that case to my website; i could redirect to a copycat page of Instagram login for the purpose of steling your info.

