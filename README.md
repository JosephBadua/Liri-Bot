# LIRI Bot

LIRI is a Language Interpretation and Recognition Interface. 


### Overview

LIRI is like iPhone's SIRI. However, while SIRI is a Speech Interpretation and Recognition Interface, LIRI is a _Language_ Interpretation and Recognition Interface. LIRI will be a command line node app that takes in parameters and gives you back data.


### Challenge

Use Node JS to create a LIRI bot, like iPhone's SIRI, but takes in commands through Language vs Speech using the following commands:

   * `concert-this`

   * `spotify-this-song`

   * `movie-this`

   * `do-what-it-says`
   
   
### Tech used

- GitHub - file repository
- Visual Studio Code - text editor

- Node.js

* APIs:

  * Spotify (https://developer.spotify.com/)
  * OMDB (http://www.omdbapi.com) 
  * Bands In Town (http://www.artists.bandsintown.com/bandsintown-api)

* NPM Packages:

  * [Node-Spotify-API](https://www.npmjs.com/package/node-spotify-api)
  * [Axios](https://www.npmjs.com/package/axios)
  * [Moment](https://www.npmjs.com/package/moment)
  * [DotEnv](https://www.npmjs.com/package/dotenv)

   
### Prerequisites

- Node.js - Download the latest version of Node (https://nodejs.org/en/).

- Make a new GitHub repository called liri-node-app and clone it to your computer.

- Send requests using the `axios` package to the Bands in Town, Spotify and OMDB APIs.

  
### What Each Command Does

LIRI will search Bands in Town for concerts, Spotify for songs, and OMDB for movies.

1. `node liri.js concert-this '<artist/band name here>`

   * Searches the Bands in Town Artist Events API for an artist and renders the following information about each event to the terminal:

     * Name of the venue

     * Venue location

     * Date of the Event (using the format "MM/DD/YYYY")

2. `node liri.js spotify-this-song '<song name here>'`

   * This will show the following information about the song in your terminal/bash window

     * Artist(s)

     * The song's name

     * A preview link of the song from Spotify

     * The album that the song is from

   * If no song is provided then your program will default to "The Sign" by Ace of Base.

3. `node liri.js movie-this '<movie name here>'`

   * This will output the following information to your terminal/bash window:

     ```
       * Title of the movie.
       * Year the movie came out.
       * IMDB Rating of the movie.
       * Rotten Tomatoes Rating of the movie.
       * Country where the movie was produced.
       * Language of the movie.
       * Plot of the movie.
       * Actors in the movie.
     ```

   * If the user doesn't type a movie in, the program will output data for the movie 'Mr. Nobody.'

4. `node liri.js do-what-it-says`

     * Runs `spotify-this-song` for "I Want it That Way".






     



