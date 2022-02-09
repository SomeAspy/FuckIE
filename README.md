# FuckIE
Fuck Internet Explorer, Redirect users to a page explaining why its bad.

I have a strong dislike for internet explorer. People still use it!

This results in a lot of basic web implementations breaking if you have a user that comes to your site using Internet Explorer.

For a full list of features Internet Explorer is lacking, see https://caniuse.com/?compare=ie+11&compareCats=all#results

Instead of using outdated garbage code, this repos files will redirect to a site explaining in a user friendly way why Internet Explorer is bad, and offer alternatives.

By default, if you just copy paste the JS file in this repo, it will direct users to https://www.aspy.dev/internal/IE

You are welcome to use my site to serve as a CDN to serve this webpage.

The easiest way to use this system is to copy paste the contents of the JS file. you can also just put

`<script src="https://aspy.dev/scripts/redirectIE.js"></script>` in your html.

I would recommend self hosting however, as you get to keep the the warning page on your own domain, and your site will still work in the event my site goes down.

you can do this like you would any other html page and js file, and just change the redirect url in the js file to fit your needs.
![7pDm](https://user-images.githubusercontent.com/33640860/153212360-752996a0-8df8-41e1-8a3c-0c66108c34e5.png)
