# rhythmstring

Get a rhythm string from The Echo Nest API for any Spotify track URI.

## Installation

    pip install -r requirements.txt

Register for a [The Echo Nest API](http://developer.echonest.com/) key, and set it as an environment variable by putting this in your .profile or .bash_profile file:

    export ECHO_NEST_API_KEY=[your API key]

## Usage

### From the command line

    python rhythmstring.py spotify:track:7HrzErXq3TsKOY1gmdIShB

### From python

    import rhythmstring
    rhythm = rhythmstring.get_by_spotify_track_uri('spotify:track:7HrzErXq3TsKOY1gmdIShB')
