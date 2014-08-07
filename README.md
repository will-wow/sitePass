sitePass
=========
Like most folks on the internet these days, I have more logins than I can
possibly remember. Usually, that means people are going to use the same password
for a bunch of different sites. The problem, of course, is that if one site's
database of passwords is compromised, you're vulnerable. You can use a password
management tool, but then you have to either keep it with you on a flash drive
or trust one site with all of your passwords (and lose access when you don't 
have an internet connection).

sitePass is another solution. It works best as a Chrome extension that lives in
your browser, though you can also use the web version. You give it the url of a
site (say, google.com), a password (say, password). It combines them using a 
one-way SHA-256 hash, then uses the encrypted output of that to generate a 
secure, unique password. Give it a different site (or a different iteration 
number, if you need to reset a password periodically) and the same base 
password, and you get an entirely different secure password. This allows you to
remember only one password, but give unique and hard-to-break ones to all of 
your sites. Or you could use multiple passwords, and use sitePass to make them 
more secure. It only uses Javascript on your machine, so your base password 
never leaves your computer, keeping you safe and secure!

You can use the web version anywhere (including your smartphone or tablet), 
install the extension (which pulls the url from your current tab) for your 
personal computers, or install the Android app for offline use.

[For more information](http://whentheresawill.net/about-sitePass)  
[Chrome Extension](https://chrome.google.com/webstore/detail/sitepass/knipommgdbefafccijppfjoiokhcedgn)  
[Android App](https://play.google.com/store/apps/details?id=net.whentheresawill.sitepass)  
[Web Version](http://whentheresawill.net/sitePass)  
