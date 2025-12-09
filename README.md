# little-browser-cef

A copy of the "Little Arc" in a standalone browser.

The idea is to build up an Arc's "Little Arc" feature competitor as a
standalone browser. There are many options of what is the browser
engine should be for this "Little Browser" companion. The goal is to
have as much flexibility and features the browser will provide as
possible. For that reason I am choosing between Chromium / Blink
(https://www.chromium.org/blink/) AND the WebKit
(https://webkit.org/). 

We all know how it is 'quite hard' to build a browser over the
Chromium (https://github.com/chromium/chromium)! That struggle led me
to the WebKit. Here is the entire WebKit-based browser represented as
an Arc competitor called
[Nook](https://github.com/nook-browser/Nook). But as the real 'loyal'
macOS user I am **not** using Safari as my daily driving web browser.

Apparently I found the solution! Steam is built upon the [Chromium
Embedded Framework](https://github.com/chromiumembedded) which is a
"simple framework for embedding Chromium-based browser in other
applications. That "simple" thing could help me a lot to build up the
Chromium-based browser that renders any page like Chromium, Arc
Browser, Dia, etc. I could easily build the UI on Swift embedding the
CEF as part of the macOS application. At least, that is how I see the
surface of possibilities to build my own small browser from zero to
one today. 
