How do you serve a page with content in multiple languages?

Use lang (or xml:lang for XHTML) in tags. Also metadata and Content-Language HTTP header can be used.
--------

To serve a page with content in multiple languages, there are four steps:

1.You must have translated/localized pages on the server for each language you intend to support.
2.Your server must recognize the browser’s language request.
3.You must carefully name the files for the localized pages, so the server has a systematic way of locating them.
4.You need a method for serving a generic page when you don’t have the requested language.

The browser writes a value for the Accept-Language request header field that it sends to the web server. You can set this value in Preferences (Mozilla) or Internet Options (Internet Explorer). If you choose multiple languages, they are sent to the server as a comma-delimited list in your preferred order.