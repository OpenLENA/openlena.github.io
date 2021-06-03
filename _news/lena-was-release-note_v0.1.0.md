---
title: "LENA WAS Release Note v0.1.0"
layout: single-news
toc: true
toc_sticky: true
---

## :fleur_de_lis: What is LENA WAS
It is Open Edition of [LENA Web Application Server](https://soltech.lgcns.com/lena). Our goal is to create an Web Application Server that users can easily install and use. The LENA CTL allows quick and easy installation and startup. If you have any questions or needs, please let us know through [WIKI](https://github.com/OpenLENA/lena-web/wiki) and [Google Groups](https://groups.google.com/g/lena-oe).

## :rainbow: Features
- Data Source Factory : The database connection information is encrypted. It is very dangerous to expose the password in the configuration file. You can protect the database more securely by encrypting access information.
- Disable Secure Cookie : Servlet filter to disable secure attribute of session cookie when set-cookie. By disabling the secure option of the session cookie, the session can be maintained even when switching from https to http. Be careful when using this feature. In general, it is recommended to use https.
- Standard Out Access Log : log writes to standard output instead of file. 
- LENA CTL : The LENA Web Application Server can be installed quickly and easily through the Command Line Interface.

## :runner: Contributors
@sleepred @sangsik @ygygood @Pinepond 