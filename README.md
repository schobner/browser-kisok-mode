# chrome-kisok-mode
Bookmarklet to open the current site at your browser in a new window with minimal clutter like chromes kiosk mode.

Drop the following link to your Bookmarkbar and use it to open any page in new window:

[kiosk-mode](https://www.schobner.rocks);

Source:  
``` javascript
window.open(window.location.href, '_blank', 'toolbar=0,location=0,menubar=0');
```
