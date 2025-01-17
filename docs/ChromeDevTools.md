# Chrome & Firefox DevTools. HTTP Protocols & WebSockets
- [ChromeDevTools](#chromedevtools)
- [Firefox DevTools](#firefox-devtools)
- [Other Tools](#other-tools)
- [HTTP Protocols](#http-protocols)
	- [HTTP Status Codes](#http-status-codes)
	- [HTTP/2](#http2)
	- [HTTP/3](#http3)
	- [HTTP Structured Fields](#http-structured-fields)
- [WebSockets](#websockets)

## ChromeDevTools
- [devtools.chrome.com](https://devtools.chrome.com)
- [Port of Firefox's JSON Viewer](https://chrome.google.com/webstore/detail/json-viewer/efknglbfhoddmmfabeihlemgekhhnabb)
- [twitter.com/ChromeDevTools](https://twitter.com/ChromeDevTools)
- In @ChromeDevTools Network, the Copy menu is powerful for replaying network requests. Copy as Fetch API code, cURL and a Node.js fetch that includes cookie data:
- [digitalocean.com: How To Debug Node.js with the Built-In Debugger and Chrome DevTools](https://www.digitalocean.com/community/tutorials/how-to-debug-node-js-with-the-built-in-debugger-and-chrome-devtools)
- [dev.to: My 12 Favorite Chrome Extensions as a Web Developer](https://dev.to/otomer/my-12-favorite-chrome-extensions-as-a-web-developer-56eg)

<center>
[![Jenkins Is The Way](images/chrome_devtools_replay_network_request.jpg)](https://twitter.com/addyosmani) 
</center>

## Firefox DevTools
- [Firefox DevTools](https://developer.mozilla.org/en-US/docs/Tools/Tools_Toolbox)
- Tip: Firefox has a really nice JSON viewer built in. Transforms JSON files (and API responses) into an easy to browse & search tree.

<center>
[![firefox viewer built in](images/firefox_json_viewer_built_in.jpg)](https://developer.mozilla.org/en-US/docs/Tools/Tools_Toolbox)
</center>

## Other Tools
- [jsontoolbox.com](https://jsontoolbox.com/)

## HTTP Protocols
### HTTP Status Codes
- [wikipedia: List of HTTP status codes](https://en.wikipedia.org/wiki/List_of_HTTP_status_codes)
- [slideshare: Http Status Code Errors in SEO](http://www.slideshare.net/AdelaRoger/http-status-code-errors-in-seo)
- [http.cat 🌟](https://http.cat) 

### HTTP/2
- [Wikipedia: HTTP/2](https://en.wikipedia.org/wiki/HTTP/2)
- [SPDY & HTTP 2 with Akamai CTO Guy Podjarny](https://www.youtube.com/watch?v=WkLBrHW4NhQ)
	- [cURL mantainer: http2 explained 🌟](http://http2-explained.haxx.se/)
	- [cURL mantainer: curl and HTTP/2 by default](http://daniel.haxx.se/blog/2015/12/14/curl-and-http2-by-default/)
	- [cURL mantainer: A 2015 retrosprective](http://daniel.haxx.se/blog/2015/12/20/a-2015-retrospective/)
	- [http2.github.io HTTP/2 🌟](https://http2.github.io)
	- [http2.github.io HTTP/2 Frequently Asked Questions 🌟](https://http2.github.io/faq/)
	- [HTTP/2 resources](https://pinboard.in/u:rmurphey/t:http2/)
	- [A Simple Performance Comparison of HTTPS, SPDY and HTTP/2 🌟](https://blog.httpwatch.com/2015/01/16/a-simple-performance-comparison-of-https-spdy-and-http2/comment-page-1/)
	- [blog.cloudflare.com - Tools for debugging, testing and using HTTP/2](https://blog.cloudflare.com/tools-for-debugging-testing-and-using-http-2/)
	- [blog.cloudflare.com - HTTP/2 For Web Developers](https://blog.cloudflare.com/http-2-for-web-developers/)
- [HTTP/2 With JBoss EAP 7 - Tech Preview](http://blog.eisele.net/2015/11/http2-with-jboss-eap-7.html)
	- [Dzone - HTTP/2 With JBoss EAP 7: Tech Preview](https://dzone.com/articles/http2-with-jboss-eap-7-tech-preview)
- [simple-talk.com: Script Loading between HTTP/1.1 and HTTP/2](https://www.simple-talk.com/dotnet/asp.net/script-loading-between-http1.1-and-http2/)
- [5 Tips to Boost the Performance of Your Apache Web Server](http://www.tecmint.com/apache-performance-tuning/)
- [DZone: How HTTP/2 Is Changing Web Performance Best Practices](https://dzone.com/articles/how-http2-is-changing-web-performance-best-practic-2) For people who write code for the web, transitioning to HTTP/2 isn’t always straightforward, and a speed boost isn’t automatically guaranteed. This article is an introduction to HTTP/2 and how it changes web performance best practices.

### HTTP/3
- [Wikipedia: HTTP/3](https://en.wikipedia.org/wiki/HTTP/3)

### HTTP Structured Fields
- [Improving HTTP with structured header fields 🌟](https://www.fastly.com/blog/improve-http-structured-headers)
- [http-sfv: HTTP Structured Field Values in Python](https://pypi.org/project/http-sfv/)

## WebSockets
- [WebSocket](https://en.wikipedia.org/wiki/WebSocket)
- [The State of Real-Time Web in 2016](https://banksco.de/p/state-of-realtime-web-2016.html)
- [SPDY and WebSocket Support at Akamai](https://blogs.akamai.com/2012/07/spdy-and-websocket-support-at-akamai.html)
- [spring.io: YMNNALFT: Websockets](https://spring.io/blog/2021/01/25/ymnnalft-websockets) Welcome to another installment of You May Not Need Another Library For That (YMNNALFT)! 
- [blog.bitsrc.io: Deep Dive into WebSockets](https://blog.bitsrc.io/deep-dive-into-websockets-e6c4c7622423) Understand the important attributes of WebSockets that every developer should know

---
<center>
<iframe src="https://www.youtube.com/embed/WkLBrHW4NhQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe src="https://www.youtube.com/embed/yGTtzcfHcdo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">❤️ the Performance Monitor in <a href="https://twitter.com/ChromeDevTools?ref_src=twsrc%5Etfw">@ChromeDevTools</a>. Gives you a real-time view of CPU use, JS heap size, JS event listeners, style recalcs &amp; more: <a href="https://t.co/tc6CyTya3O">https://t.co/tc6CyTya3O</a> <a href="https://t.co/BWSi8klGkE">pic.twitter.com/BWSi8klGkE</a></p>&mdash; Addy Osmani (@addyosmani) <a href="https://twitter.com/addyosmani/status/1280403679380561920?ref_src=twsrc%5Etfw">July 7, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
</center>

