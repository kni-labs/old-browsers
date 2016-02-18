# old-browsers
<img src="https://raw.githubusercontent.com/kni-labs/old-browsers/master/preview.jpg">
To be served (via conditional comments) when the user doesn't have an updated browser. Like [browsehappy.com](http://browsehappy.com), but locally.

### Usage
Place this directly under body tag:
``` html
<!--[if IE 8]><style media="screen">.old-browsers{position:relative;background:#fff;width:100%;height:100%;color:#000;font-family:sans-serif;font-size:20px;text-align:center;padding:0;margin:0}.old-browsers h2{padding:20px 0}.old-browsers p,.old-browsers ul{margin:0 auto}.old-browsers p{max-width:700px;padding-bottom:50px;line-height:1.4em}.old-browsers ul li{display:inline-block;padding:0 25px}.old-browsers ul li img{width:115px; border: 0;}.old-browsers ul li p{padding-top:15px;color:#249AE1}body{margin:0;padding:0}</style><div class="old-browsers"> <h2>Browser out of date.</h2> <p>It appears you're running on a very old web browser that we're unable to support. If you would like to view the site you'll need to update your browser. Please choose from any of the following modern browsers. Thanks!</p> <ul> <li> <a href="https://www.google.com/intl/en/chrome/browser/desktop/index.html#brand=CHMB&utm_campaign=en&utm_source=en-ha-na-us-sk&utm_medium=ha"> <img src="https://raw.githubusercontent.com/alrra/browser-logos/master/chrome/chrome_128x128.png" alt="Google Chrome"> <p>Google Chrome</p> </a> </li> <li> <a href="https://www.mozilla.org/en-US/firefox/new/"> <img src="https://raw.githubusercontent.com/alrra/browser-logos/master/firefox/firefox_128x128.png" alt="Mozilla Firefox"> <p>Mozilla Firefox</p> </a> </li> <li> <a href="https://support.apple.com/downloads/safari"> <img src="https://raw.githubusercontent.com/alrra/browser-logos/master/safari/safari_128x128.png" alt="Safari"> <p>Safari</p> </a> </li> <li> <a href="http://windows.microsoft.com/en-us/internet-explorer/download-ie"> <img src="https://raw.githubusercontent.com/alrra/browser-logos/master/internet-explorer/internet-explorer_128x128.png" alt="Internet Explorer"> <p>Internet Explorer</p> </a> </li> </ul></div><![endif]-->
```
> [**View Codepen**](http://codepen.io/dbox/pen/gaoraM)

**Note:** npm install method is currently outdated. New one in the works..
