# The World's Tweets on a 3D Globe

This is just a demo of the Twitter Firehose api where you can catch tweets as they happen in real time. Using the url bar, you can put a search term and if that term is used in a tweet that was made, it will appear on the globe where it was tweeted.

# Running It

To run the project, first you must navigate to the `globe` directory in the terminal. Next, you have to run a webserver in the that directory you've just navigated to. I use [serve](https://www.npmjs.com/package/serve) to host a local file directory like we're doing here. Using serve we can use a command like `serve .`. This will run the directory on my localhost. Finally, using a browser navigate to localhost, then to our tweetGlobe.html page. <br><br>

Your commands should look something like this! <br><br>

Navigate to the directory: <br>
```
cd ~/.../eatingEarth/globe
```
where the ... is for your local route to the project.<br><br>

Run Serve: <br>
```
serve .
```

Open a brower to this url:
```
http://localhost:5000/tweetGlobe.html?
```
Anything after the `?` will be a search term. For example:
```
http://localhost:5000/tweetGlobe.html?trump
```
will return all tweets containing the word `trump`.

