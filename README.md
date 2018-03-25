# Spotify Lyrics app

This project contains a Spotify Lyrics app deployed on http://ec2-34-216-228-99.us-west-2.compute.amazonaws.com:3000/ using Spotify's example code given on https://github.com/spotify/web-api-auth-examples


## Installation

These examples run on Node.js. On [its website](http://www.nodejs.org/download/) you can find instructions on how to install it. 

Once installed, clone the repository and install its dependencies running:

    $ npm install

### Using your own credentials
You will need to register your app and get your own credentials from the Spotify for Developers Dashboard.

To do so, go to [your Spotify for Developers Dashboard](https://beta.developer.spotify.com/dashboard) and create your application. For the examples, we registered these Redirect URIs:

* http://localhost:8888/callback

Once you have created your app, replace the `client_id`, `redirect_uri` and `client_secret` in the examples with the ones you get from My Applications.

## Running the examples
In order to run the different examples, open the folder with the name of the flow you want to try out, and run its `app.js` file. For instance, to run the Authorization Code example do:

    $ cd appfiles
    $ node app.js

Then, open `http://localhost:8888` in a browser.
