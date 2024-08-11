# A BSOD-Inspired 404 Error Page

A 404 error page that takes inspiration from the classic Windows Blue Screen of Death (BSOD). Crafted entirely by hand using just HTML and CSS, this project is a playful homage to the dreaded BSOD, reimagined as a quirky and functional web design element.

## How This Idea Clicked Me?

Ever clicked on a broken link only to be greeted by a dull, generic 404 error page? Recently, I faced the issue leading to a Windows BSOD, and an idea struck me – why not replicate this iconic screen as a 404 webpage? And finally, here it is! With this, you can give your users a pleasant surprise (or a mild flashback to their Windows days) when they stumble upon a missing page. The design captures the essence of the original BSOD, albeit with some modifications and a dash of humor in the error messages. It’s a simple yet effective way to add personality to your website while maintaining a professional appearance.

## How to Get It Personalized for You?

1. **Fork this repository** onto your GitHub profile.
2. **Perform the following edits:**
    1. **index.html**
        - Amend **line 9** in case you want to use your desired font.
        - Amend **lines 11 to 28** if you want to use your desired favicon(s).
        - In **line 45**, edit a certain part of the `src` URL of the image, e.g., the existing URL `https://qrcode.tec-it.com/API/QRCode?data=https%3a%2f%2fwww.mridungupta.eu.org&errorcorrection=H&backcolor=%23ffffff&dpi=600&size=Large` leads to a QR code that, when scanned, redirects to `www.mridungupta.eu.org`. Simply remove it and update it with your desired URL, or better yet, refer to the [documentation](https://qrcode.tec-it.com/en) for the Tec-it QR Code Generator API.
    2. **style.css**
        - Amend **lines 26 and 27** with your desired `font-family`.
    3. **main.js**
        - In **line 1**, edit the existing timer duration (`10`) to your desired time after which redirection will start.
        - In **line 12**, edit the existing URL to your desired destination where the page should redirect.
        - In **line 16**, edit the time in milliseconds to match the one set in **line 1** of `main.js`.
3. **Host it** using any tools you prefer (e.g., Vercel, Netlify, GitHub Pages, etc.).

---

Enjoy surprising your users with a bit of nostalgia and a lot of creativity with this project!