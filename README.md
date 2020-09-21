# Local Storage

## INTRODUCING HTML5 STORAGE

### So what is HTML5 Storage? Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). It is implemented natively in web browsers, so it is available even when third-party browser plugins are not.

### Which browsers? Well, the latest version of pretty much every browser supports HTML5 Storage… even Internet Explorer!
### From your JavaScript code, you’ll access HTML5 Storage through the localStorage object on the global window object. Before you can use it, you should detect whether the browser supports it.
