# FuckIE

This repository provides a JavaScript file that redirects users who access your website using Internet Explorer to a page explaining why it's not recommended, and offer alternative browsers.

It's important to note that Internet Explorer lacks many modern web features and can cause issues with web implementations.

For a full list of limitations of Internet Explorer, you can check out this link: https://caniuse.com/?compare=ie+11&compareCats=all#results

By default, the JS file in this repository redirects users to the website https://ie.aspy.dev, which provides a user-friendly explanation and alternative browser suggestions.
You can use this website as a CDN to serve the redirect page or self-host the page to have better reliability.

To use the redirection script, you can include the following script tag in your HTML:
```html
<script src="https://ie.aspy.dev/redirectIE.js"></script>
```

Alternatively, you can copy and paste the contents of the JS file and host it on your own domain.
You can also customize the redirect URL in the JS file to fit your needs.

![preview](https://files.catbox.moe/qjfitw.png)
