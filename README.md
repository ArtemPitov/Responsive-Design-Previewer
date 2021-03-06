# Responsive Web Design Previewer / Simulator / Tester v1.0.3

## A tool to help test responsive layouts across many device resolutions

Upload preview.php and run in your browser.

Go directly to any URL by adding **?url=http://somesite.com/whatever.html**

**Demo - https://www.xcartmods.co.uk/preview.php?url=https://getbootstrap.com**

---

- To simulate touch events, open your browser inspector
- If an entered URL doesn't work, check your browser console
- You can easily add more devices / breakpoints if you wish
- You can manually resize the preview using the bottom right handle
- The minimum custom width / height is 320px

---

Ensure the http protocols are the same for preview.php and the preview URL.

---

The 'refresh' and 'close' buttons will only function if the parent and preview URLs are from the same domain.

---

External URLs with 'X-Frame-Options' set to 'sameorigin' may not be previewable.

https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options
  
**Apache .htaccess override code...**

```
Header set X-Frame-Options DENY
Header set X-Frame-Options "ALLOW-FROM https://site.com"
```

---

**X-Cart v4.x Stores** - If it doesn't work, in config.php, check FRAME_NOT_ALLOWED is set to FALSE

(Change back to TRUE after you have done your testing)

https://help.x-cart.com/index.php?title=X-Cart:Config.php#Blocking_IFRAME_.2F_FRAME_calls

---

https://github.com/xcartmods/Responsive-Design-Previewer

&copy; 2018 https://www.xcartmods.co.uk

**Enjoy!**
