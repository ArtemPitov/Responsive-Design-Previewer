# Responsive Design Previewer v1.0.2

## A tool to help test responsive layouts

Upload preview.php and run in your browser.

Go directly to a URL by adding **?url=somesite.com/whatever.html**

Demo - **https://www.xcartmods.co.uk/preview.php?url=https://getbootstrap.com**

---

- To simulate touch events, open your browser inspector
- If an entered URL doesn't work, check your browser console
- You can easily add more devices / breakpoints if you wish
- You can manually resize the preview using the bottom right handle
- The minimum custom width / height is 320px

**Enjoy!**

---

Ensure the http protocol is the same.

**X-Cart stores** - If it doesn't work, in config.php, check FRAME_NOT_ALLOWED is set to FALSE (change back to TRUE after you have done your testing)
https://help.x-cart.com/index.php?title=X-Cart:Config.php#Blocking_IFRAME_.2F_FRAME_calls

URLs with 'X-Frame-Options' set to 'sameorigin' will not be previewable
https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options
  
**Apache .htaccess override code...**

Header set X-Frame-Options DENY
Header set X-Frame-Options "ALLOW-FROM https://site.com"

https://github.com/xcartmods/Responsive-Design-Previewer

&copy; 2018 xcartmods.co.uk
