# CastVideos-chrome
===============================

This Google Cast demo app shows how to cast various media e.g. video, movies, TV show, music and photo from a Chrome browser using Cast Chrome Sender SDK. It highlights metadata types listed here: https://developers.google.com/cast/docs/reference/chrome/chrome.cast.media.MetadataType and how metadata get sent to and handled by the Cast default receiver app.

This app also illustrates various auto join policy settings that define how sessions can be retrieved.

## Setup Instructions

# Pre-requisites
 1. Get a Chromecast device
 2. Install appropriate Chrome browser
 3. Install appropriate Chrome Cast extension

 See the developer guide and release notes at https://developers.google.com/cast/ for more details.
 
# Steps:
 1. Put all files on your own server
 2. Use the default media receiver app hard coded in media.js: chrome.cast.media.DEFAULT_MEDIA_RECEIVER_APP_ID 
 4. Open a browser and point to your page at http://[YOUR_SERVER_LOCATION]/CastMedia-chrome/

##Documentation
* Cast APIs: http://developers.google.com/cast/docs/chrome_sender

## References and How to report bugs
* Cast APIs: http://developers.google.com/cast/docs/reference/chrome
* Cast media namespace data structures: https://developers.google.com/cast/docs/reference/messages
* If you find any issues, please open a bug here on GitHub

How to make contributions?
Please read and follow the steps in the CONTRIBUTING.md

License
See LICENSE.md

## Google+
 Google Cast Developers Community on Google+ [http://goo.gl/TPLDxj](http://goo.gl/TPLDxj)
