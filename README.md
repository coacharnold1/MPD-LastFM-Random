# MPD-LastFM-Random
A sript to run from the command line that will query LAST-FM and add like files based on the currently playing artiist and genre

The feature missing from all the mpd clients ive tried … something to generate playlists based on a query to last-fm based on the currently playing track. It’s a feature of lyrion (sort of) that i am missing since playing with MPD. so I spent some time with my good friend Gemeni-AI and came up with this … instructions listed first, then python script.

Need this python library, reguests install usinnf PIP - pip install requests

Important: How to get and add your Last.fm API Key to the script

To make the random-like-track.py script work, you’ll need your own Last.fm API key. This helps manage usage and ensures the script functions correctly for everyone.

Here’s how to get yours:

Go to the Last.fm API Account Creation page:
https://www.last.fm/api/account/create

If prompted, log in with your Last.fm account (or create a new one).

Fill out the "Create an API account" form. You can use any name and description you like for your "application" (e.g., "MPD Track Suggester Script"). You generally do not need to provide a Callback URL for this script, as it's not a web application.

After submitting, you'll be presented with your unique API Key (a long string of letters and numbers). Copy this key.

Open the random-like-track.py script in a text editor.

Find the line that looks like this:
Python

LASTFM_API_KEY = "YOUR_LASTFM_API_KEY_HERE" # <<< Your actual Last.fm API Key

Replace "YOUR_LASTFM_API_KEY_HERE" with the API key you copied from the Last.fm website. Make sure to keep the quotation marks around your key!

Save the script, and you’re all set!

I’m not going to post the script here, as i think it will mess with the forum editor … … I’m making a shared google doc of it … here: look below for updated script

My goal is to add a button or something to Cantata, that will trigger this to run. Make sure it’s saved on the computer where MPD lives, it uses mpc comands. This has added an important functionality for me, I;m sure it will need updates to get it just right. Time … thoughts here are welcome excpessially if you have a different solution for this.
