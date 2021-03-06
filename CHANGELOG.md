Changelog
=========

3.0.1
-----
-  Removed UMD support.

3.0.0
-----
-  Added support for Session Tracking
-  Added support for Single Page Application route change performances

2.3.12
-----
-  Added console timeline support
-  Added console.error notify

2.3.11
-----
-  Added request object for on before send

2.3.10
-----
-  Added grouping key support
-  Added support for options in config object.
-  Added option to report console errors

2.3.9
-----
-  Added an option to disable Real User Monitoring

2.3.8
-----
-  Fixed version number and user id integer values
-  Added uninstall support

2.3.7
-----
-  Fixed enable sourcemap type issue.
-  Removed atatus URL from stacktrace

2.3.6
-----
-  Added user support
-  Removed sourcemap file

2.3.5
-----
-  Added a map file
-  Fixed ignore errors issue

2.3.4
-----
-  Fixed callback duration.
-  Removed 70 sec check in page load performance

2.3.3
-----
-  Increased AJAX Batch Size to 25
-  Renamed AJAX Payload key name.
-  Ignored Page Load time greater than 70 sec

2.3.2
-----
-  Removed query string from AJAX URL

2.3.1
-----
-  Fixed responseText issue

2.3.0
-----
-  Added support for Ajax Monitoring
-  Added support for Transaction Monitoring

2.2.5
-----
-  Added `isConfigured` to check whether API key is configured or not

2.2.4
-----
-  Fixed bug in jQuery.event wrapping if handler not a func
-  Handle exceptions on windows phone 8 in cordova
-  Normalize Firefox's 0-based column number

2.2.3
-----
-  Add support for source map
-  Add support for application version
-  Add a `onBeforeErrorSend` callback to allow filtering of errors being sent to Atatus

2.2.2
-----
-  Don't send duplicate exceptions from the client
-  Fixed bug navigation start with 0 instead of time
-  First version available on bower and npm as atatus-js

2.2.1
-----
-  Use image tag instead of CORS to make requests, for better cross-browser support

2.2.0
-----
-  Add support for performance

1.0.0
-----
-  First public release