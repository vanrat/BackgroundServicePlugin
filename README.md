# Background Service Plugin for Phonegap #

A plugin (and framework code) that allows the development and operation of an Android Background Service.

The example MyService Background Service will write a Hello message to the LogCat every minute.  The MyService is designed as sample code.

## Cordova Versions ##

Folders used for different Cordova versions:

* /2.2.0 - For use with Cordova 2.2.0
* /2.3.0 - For use with Cordova 2.3.0
* /2.4.0 - For use with Cordova 2.4.0
* /2.5.0 - For use with Cordova 2.5.0
* /2.6.0 - For use with Cordova 2.6.0
* /2.7.0 - For use with Cordova 2.7.0
* /2.8.0 - For use with Cordova 2.8.0
* /2.8.1 - For use with Cordova 2.8.1
* /2.9.0 - For use with Cordova 2.9.0
* /3.0.0 - For use with Cordova 3.0.0
* /3.1.0 - For use with Cordova 3.1.0

## Depreciated Versions ##

Over time I will no longer maintain older versions.  These will be listed here.  The code will still be available in the source, but may not compile or build without work.

* /1.8.1 - For use with Cordova 1.8.1 - Depreciated 21st August 2013
* /2.0.0 - For use with Cordova 2.0.0 - Depreciated 21st August 2013


## Change Log ##

* 4th September 2013 - Fixes for NullPointerException (see https://github.com/Red-Folder/Cordova-Plugin-BackgroundService/issues/7)
* 27th August 2013 - Added TimerMilliseconds to returned JSONObject (see Issue 5)
* 12th May 2013 - Updated to handle service being restarted by OS (version 2.2+)
* 14th November 2012 - Fix for service not stopping if the app has been closed then re-opened

## Further Information ##

Further information on the plugin can be found at:

* http://red-folder.blogspot.co.uk/2012/09/phonegap-android-background-service.html
* http://red-folder.blogspot.com/2012/09/phonegap-android-background-service_11.html

The below is a tutorial to create your own Twitter service:

* http://red-folder.blogspot.com/2012/09/phonegap-service-tutorial-part-1.html
* http://red-folder.blogspot.com/2012/09/phonegap-service-tutorial-part-2.html
* http://red-folder.blogspot.com/2012/09/phonegap-service-tutorial-part-3.html

Please let me know your thoughts and comments.

## Source Code ##

This repository uses jar files for the main logic.  Due to the complexity of the code, I've found this is the easiest method to distribute it.

Should you be interested in the underlying source, it is available in this repository -> https://github.com/Red-Folder/Cordova-Plugin-BackgroundService-Source

## Spread the love ##

If you find the Background Service Plugin useful then spread the love.

All the work I do on the Plugin is done in my spare time - time I would otherwise be spending taking my wife out for a nice meal or helping my lad find vinyl records (he's currently very much into The Smiths, Fleetwood Mac and Kate Bush).

The Plugin is free and will always remain free.  I will continue to develop, maintain and distribute the Plugin under the MIT License.

https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=E64TCFQ3NLHZ8

## Licence ##

The MIT License

Copyright (c) 2013 Red Folder Consultancy Ltd

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

