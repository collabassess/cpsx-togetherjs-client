# cpsx-togetherjs-client
TogetherJS-client side application, for custom modifications for the CPSXBlock

location: https://cpsx-togetherjs-client.herokuapp.com/

To create heroku app
<pre>
git clone <this-repo>
heroku login
heroku apps:create "your app name"
git push heroku master
</pre>

That's it, it would be uploaded and running on the url given by heroku!
Use this url as the base_url in togetherjs.min.js files in your CPSXBlock, or anywhere you want to import custom togetherjs.

In order to update the repo on heroku
<pre>
git add .
git commit -m "message"
git push heroku master
</pre>

Note: ignore the html and php files, these are just added to be able to upload the static content as an app on heroku free of cost