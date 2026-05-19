# Personal note
I created this application because it solves a personal problem with the Spotify roster, where things like in-game songs, niché remixes or instrumentals simply aren't available on the app for the most part.
Other than that i just did it because i love developing apps and websites.
AI was used in the proccess of making this project as it's efficient and the Javascript is quite complex.

# Spotify Directory Audio Utility

A desktop application designed to fetch audio streams from Youtube and SoundCloud (for now) and save them into a local directory. 

Built with Electron, this utility automates the process of downloading media, parsing metadata, and writing ID3 tags to the output files.

## Features

- **Single Track Processing:** Downloads individual tracks and parses available metadata and cover art.
- **Batch Playlist Processing:** Accepts playlists up to 100 tracks to automate consecutive downloads.
- **Title and Artist Parsing:** Separates "Artist - Title" strings and removes specified text strings such as "(Official Video)" or "[Clean]".
- **Metadata Editing:** Allows modification of track titles, artists, or cover art images prior to saving.
- **ID3 Tagging:** Writes metadata directly into the MP3 audio buffer before file creation.

## Installation and Usage

1. Navigate to the Releases section of this repository.
2. Download the installer executable.
3. Run the installer to complete the setup process.

> **Note on Windows SmartScreen:** Because this installer is unsigned and bundles the yt-dlp binary, Windows Defender or web browsers may flag the file as unrecognized or untrusted. Users must select "More Info" and then "Run Anyway" to proceed with the installation.

## Technical Specifications

- **Framework:** Electron, Node.js, HTML, CSS, JavaScript
- **Dependencies:** yt-dlp, browser-id3-writer
## License
This project is proprietary. See the [LICENSE](LICENSE.txt) file for usage terms.
