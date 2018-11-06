# chrome-kisok-mode
Bookmarklet to open the current site at your browser in a new window with minimal clutter like chromes kiosk mode.

Drop the following link to your Bookmarkbar and use it to open any page in new window:

[kiosk-mode](javascript:(function()%7Bwindow.open(window.location.href%2C%20'_blank'%2C%20'toolbar%3D0%2Clocation%3D0%2Cmenubar%3D0')%7D)());

Source:  
``` javascript
window.open(window.location.href, '_blank', 'toolbar=0,location=0,menubar=0');
```
