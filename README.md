sitePass
=========
sitePass is a sort of password manager. You give it the url of a site (say, google.com) and a password (say, password). It combines them using a one-way SHA-256 hash, then uses the encrypted output of that to generate a secure, unique password. Give it a different site (or a different iteration number, if you need to reset a password periodically) and the same base password, and you get an entirely different secure password. This allows you to remember only one password, but give unique and hard-to-break ones to all of your sites. It only uses Javascript on your machine, so your base password never leaves your computer, keeping you safe and secure!

For more information, see whentheresawill.net/about-sitePass