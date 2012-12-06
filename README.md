Tidy CSS
========

I use a hybrid CSS formatting scheme. It's a mix between multi-line format and single-line format with tabbing (see [CSS Tricks](http://css-tricks.com/different-ways-to-format-css/) for more info). This style allows me to quickly browse the selectors on the left as you can with inline, and it also allows me to see the properties in order on the right without having to scroll horizontally. 

Tidy CSS is a JavaScript based formmatter that automatically formats css. You can [use it](http://reallyseth.com/tidy-css/), contribute, or just copy for your own purposes.

*NOTE: There are some issues with comments inside curly braces. But comments outside of the curlies will be ignored and left alone.*

## Before
```CSS
a[href^="mailto"]:hover { color: #cc0000; }

h2, .ms-rteElement-H2{ 
  color: #cc0000;
  font-size: 12px;
  font-weight: bold;
  margin-bottom: 0;
  margin-top: 4px; 
}
```

## After
```CSS
a[href^="mailto"]:hover                          { color: #cc0000; }

h2,
.ms-rteElement-H2                                { color: #cc0000;
                                                   font-size: 12px;
                                                   font-weight: bold;
                                                   margin-bottom: 0;
                                                   margin-top: 4px; }
```
