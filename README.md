# FuckIE
Fuck Internet Explorer, Redirect users to a page explaining why it's bad.

I have a strong dislike for Internet Explorer. People still use it!

This results in a lot of basic web implementations breaking if you have a user that comes to your site using Internet Explorer.

For a full list of features Internet Explorer is lacking, see https://caniuse.com/?compare=ie+11&compareCats=all#results

Instead of using outdated garbage code, these repos files will redirect to a site explaining in a user-friendly way why Internet Explorer is bad, and offer alternatives.

By default, if you just copy and paste the JS file in this repo, it will direct users to https://ie.aspy.dev

You are welcome to use my site to serve as a CDN to serve this webpage.

The easiest way to use this system is to copy and paste the contents of the JS file. You can also just put

`<script src="https://ie.aspy.dev/redirectIE.js"></script>` in your HTML.

I would recommend self-hosting, however, as you get to keep the warning page on your own domain, and your site will still work in the event my site goes down.

You can do this like you would any other HTML page and JS file, and just change the redirect URL in the JS file to fit your needs.
![img](https://user-images.githubusercontent.com/33640860/153212360-752996a0-8df8-41e1-8a3c-0c66108c34e5.png)
