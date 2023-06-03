# The World's Tweets on a 3D Globe

Welcome to our real-time Twitter Firehose API demo, which displays tweets from around the world on a 3D globe as they occur. You can customize your experience by adding a search term in the URL bar. Tweets containing this term will then be displayed on the globe, originating from their tweet location.

## Running the Project Locally

Follow the steps below to run this project on your local machine:

1. **Navigate to the project directory:**

   Open your terminal and navigate to the `globe` directory inside the project repository. Replace the `...` with your local route to the project.

   ```bash
   cd ~/.../eatingEarth/globe
   ```

2. **Start a local web server:**

   Inside the `globe` directory, you need to start a web server. One option is to use [serve](https://www.npmjs.com/package/serve), a static file server. You can start it with the following command:

   ```bash
   serve .
   ```

3. **Access the web page:**

   Now, open your web browser and navigate to your localhost at the designated port (default is 5000 if you use `serve`), then go to our `tweetGlobe.html` page with a `searchTerm` parameter. The updated URL is as follows:

   ```
   http://localhost:3000/tweetGlobe?searchTerm=quantum
   ```

   In this example, the `searchTerm` parameter is set to 'quantum'. As a result, the globe will display tweets that contain the word 'quantum'.

And that's it! Enjoy exploring global tweets in real-time with your chosen search term.
