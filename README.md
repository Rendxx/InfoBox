# Customized Information Box
Enable user to show their customized HTML elements in the center of screen.  

- A screen cover will be created to block mouse event to the original page.
- Clicking outside the body of the info-box will close the info-box. This feature can be disabled manually.

![preview](https://raw.githubusercontent.com/Rendxx/InfoBox/master/preview.png "Preview")  

*Sample: [http://www.rendxx.com/Lib/Sample/6](http://www.rendxx.com/Lib/Sample/6 "Sample")*  
*Download: [InfoBox v3.0](https://github.com/Rendxx/InfoBox/releases/tag/3.0 "Download")*

# API
[API Document](https://github.com/Rendxx/InfoBox/blob/master/API%20Document.md)

# Preset API
Please see the note in **InfoBox.js** for more details.

# Dependency
- [jQuery][]

# Code Sample
JavaScript:

```javascript
$$.info.alert2("Alert Sample. <br />Click <b>OK</b> to close.", "ALERT", false, "rgba(0,0,0,0.6)", null);
// Create an alert window.
```

# Compatibility
- Chrome
- Fire Fox
- Safari
- Edge
- IE 9-11
- IE 7,8

[jQuery]: https://jquery.com/ "jQuery Home Page"