# Album Review Website "Discog"
## Beau Albritton

### Dependencies
This program requires
* python3 `https://www.python.org/downloads/`
* flask `https://flask.palletsprojects.com/en/stable/`
* spotipy `https://spotipy.readthedocs.io/en/2.24.0/index.html#`
* Also see: `https://developer.spotify.com/documentation/web-api`


These can be installed via `pip` the package installer for python. This is built in to python.

Run these commands in the terminal:
`pip install flask`
`pip isntall spotipy`
before continuing with this program

### Summary

This program uses Spotify's Web API for Developers and Flask to create a dynamically rendered webpage that displays artists and their relevant albums, based on user input. For each individual album an artist has, there is album art, tracklist, and reviews displayed to the user. User can cycle through Albums by clicking "Next Album" in /

### Languages

This mainly uses Python, and integrates it with html files that are rendered to the flask app. It communicates directly with html files to dynamically render relevant data. Other languages included: javascript (light) css(not my best).

### Known Bugs

On redirect after a submission, the index page is not called. Can still reroute, but manually. Watch video for demonstration.
