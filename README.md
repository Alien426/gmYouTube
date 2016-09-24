# gmYouTube
Replacing the large style sheets using Greasemonkey.

The video site YouTube (http://www.youtube.com) is one of these modern sites with excessive HTML nesting and over 4.000 CSS style rules (on a video page; more excessive on the home page). This is not only adding traffic, but also taxes the hardware.

Can't do much about the first problem, but by blocking the .css file and inserting custom styles via the Firefox extension Greasemonkey (https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/) one can cut down on this unnecessary crap.

It should be noted that the script is not (yet) able to reproduce the full functionality of the site. Its main goal is to make searching and watching videos possible. Uploading videos and commenting will probably always require to load the site with the adblocker and Greasemonkey disabled.

I'm not very happy with this script yet. The styles are often copied from YouTube just so it works.


How to use the script:

1. Block the CSS files by adding "||s.ytimg.com/yts/cssbin/*" to an adblocker (or your router).
2. Add the Greasemonkey script gmYouTube.js.
