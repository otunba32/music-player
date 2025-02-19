# Music Player

A simple JavaScript-based music player that allows users to play, pause, skip, shuffle, and delete songs from a playlist.

## Features

1.  Play and pause songs

2.  Skip to the next or previous song

3.  Shuffle the playlist

4.  Delete songs from the playlist

5.  Reset the playlist

6.  Displays the currently playing song title and artist

## Installation

No additional installation is required. Simply include the JavaScript file in an HTML file with the necessary elements and run it in a browser.

## Usage

Add the necessary HTML elements with corresponding IDs:

playlist-songs for the list of songs

play, pause, next, previous, and shuffle buttons

player-song-title and player-song-artist for displaying the current song

Include the JavaScript file in your project.

Open the project in a web browser and interact with the player.

## Customization

To change the song list, update the allSongs array with new song objects containing:

1.  {
    id: <number>,
    title: "<song title>",
    artist: "<artist name>",
    duration: "<duration>",
    src: "<audio file URL>"
    }

2.  Modify button styles and layout in your CSS file.

3.  Extend functionality by adding new event listeners for volume control, progress bar, etc.

## Dependencies

This project does not require any external dependencies; it is built using vanilla JavaScript.

## License

This project is open-source and free to use and modify.
