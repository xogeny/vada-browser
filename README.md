# Vada + Browser

This module provides functionality that is useful when running a
[`vada`](http://github.com/xogeny/vada) application within a browser
(vs. mobile or desktop).

The main idea here is to specify for the browser how to map URLs
patterns to `vada` routes.  Once this is done, the browser will
monitor `window.location` and submit *actions* to the application
store requesting route changes whenever a new location is requested.