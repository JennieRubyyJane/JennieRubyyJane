# Music Library

## Description
This project is a simple music library application written in Python. It allows users to create and manage playlists, add and delete songs, search for songs by title or artist, sort songs, and play songs. Playlists can also be saved to and loaded from files.

## Features
- Create and delete playlists -> Erlind Kryeziu
- Add and delete songs from playlists -> Erlind Kryeziu
- Search for songs by title or artist -> Ketrin Xhafa
- Sort playlists by song title or artist name ->Krisjor Mema
- Play songs in the playlist (simulate play) -> Kiara Doraci
- Save playlists to a file -> Ketrin Xhafa
- Load playlists from a file -> Ketrin Xhafa

## Requirements
- Python 3.x

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/JennieRubyyJane/music-library.git
2. Navigate to the project directory:
    ```bash
    cd music-library
    ```
    python main.py

## Usage
Run the `main.py` file to start the application:
```bash

##Code

1. Classes and Functionalities:
Song: Represents a song with title and artist.
Playlist: Manages a list of songs.

2. Attributes: name, songs (list), current_song (index)
Methods:
    -add_song(title, artist): Adds a song.
    -delete_song(title, artist): Deletes a song.
    -next_song(): Moves to the next song.
    -previous_song(): Moves to the previous song.
    -play_current_song(): Plays the current song.
    -search_by_title(title): Searches for songs by title.
    -search_by_artist(artist): Searches for songs by artist.
    -sort_by_title(): Sorts songs by title.
    -sort_by_artist(): Sorts songs by artist.
    -display_songs(): Displays all songs.
    -music_library: Manages multiple playlists.

3. Attributes: playlists (dictionary)
Methods:
    -create_playlist(name): Creates a new playlist.
    -edit_playlist(name): Renames a playlist.
    -delete_playlist(name): Deletes a playlist.
    -save_playlist(name): Saves a playlist to a file.
    -load_playlist(filename): Loads a playlist from a file.

4. Algorithms and Data Structures
Algorithms:
    -Adding and deleting songs.
    -Navigating songs using indices.
    -Searching and sorting songs.

5. Data Structures:
List: To store songs in Playlist.
Dictionary: To manage multiple playlists in music_library.


