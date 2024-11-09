# Album Review Website "**discog.**"
## Beau Albritton


### Summary

This program uses Spotify's Web API for Developers and Flask API for python to create a dynamically rendered webpage that displays artists and their relevant albums, based on user input. For each individual album an artist has, there is album art, tracklist, and reviews displayed to the user. User can cycle through Albums by clicking the "Next Album" button, and can submit reviews to the relevant album.

### Languages

This mainly uses Python, and integrates it with html files that are rendered to the flask app. It communicates directly with html files to dynamically render relevant data. Other languages included: javascript (light) css(not my best).


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

### To Run
After installing the dependencies, route to your installed directory. Run the `main.py` via the command line using `python main.py`.
Your machine will serve as a basic webserver that routes the client to different pages.
Visit the localhost given in the terminal. From there, enter an artist to search their discography.
The process from there should be relatively straightforward.


### Known Bugs

On redirect after a submission, the index page is not called. Can still reroute, but manually. 
