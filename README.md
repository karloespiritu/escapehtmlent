# Escapehtmlent

A small utility to escape/unescape HTML entities

##Usage

```
 var escapehtmlent = require('escapehtmlent')
      escape = escapehtmlent.escape,
      unescape = escapehtmlent.unescape;

  var html = '<h1>The horrible conclusion which had been gradually intruding itself...</h1>',
      escaped = escape(html),
      unescaped = unescape(escaped);

  console.log('html:'+html+'|escaped:'+escaped+'|unescaped:'+unescaped);
```  