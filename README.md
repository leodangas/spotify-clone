![Screenshot_1](https://user-images.githubusercontent.com/89187708/130231474-4e48fdb5-ed11-42d6-a988-1c6657edfd49.png)


# Spotify Clone

Spotify clone built using react, I tried replicating the spotify's web app design and features as closely as I could. It features all the playlists, songs
that you can find on Spotify and has a built-in search function for finding these songs/playlists easier.

NOTE: Currently you can't log in using your's Spotify account on this app.

### Try it out
[Link to website](https://another-spotify-clone.netlify.app/home)

## Table of Contents

* [Setup](#setup)
* [Built with](#built-with)
* [Features](#features)


## Setup
To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer.

From your command line:
```bash
# Clone this repository
$ git clone https://github.com/leodangas/spotify-clone

# Go into the repository
$ cd spotify-clone

# Install dependencies
$ npm install

# Go into the client's repository
& cd client

# Install dependencies
& npm install

# Go back to spotify-clone folder
& cd ..

# Run the application
& npm run dev

INSIDE SERVER.JS FILE ADD SPOTIFY'S API CLIENT ID AND CLIENT SECRET
```


## Built with

* [React](https://reactjs.org/)
* [React-Router](https://reactrouter.com/)
* [React-Spring](https://react-spring.io/)
* [Express](https://expressjs.com/)
* [Spotify-Web-Api-Node](https://github.com/thelinmichael/spotify-web-api-node)
* [SASS](https://sass-lang.com/)
* [Spotify API](https://developer.spotify.com/documentation/web-api/)

## Features

### Playlists

Navigate through hundreds of different playlists, created by Spotify

![Screenshot_3](https://user-images.githubusercontent.com/89187708/130233104-3cbf0fd9-818f-4376-90a9-e9403c3fe668.png)

### Playlist details

The playlist contains this information:

Playlist information:
* Name
* Description
* Likes
* Song total
* Duration 
* Songs

Song information:
* Name
* Artists
* Album
* Date added
* Length

![Screenshot_4](https://user-images.githubusercontent.com/89187708/130233363-2e74a159-8097-4069-9d48-b88b247d6924.png)

### Search

Find your favourite songs, playlists easier!
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/89187708/130235272-a73cbcbb-e6da-4380-a462-3e4c08d5f429.gif)

### Navigation

Built-in navigation helps you to navigate through this app easier

And no, it's not built with history.back();

![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/89187708/130236135-f37ebd54-78c6-4d9a-9ee8-a731b3783e26.gif)
