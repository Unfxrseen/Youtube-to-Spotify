# Spotify Directory Audio Utility

A desktop application designed to fetch audio streams from Youtube and save them into a local directory. 

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
4. Set the target destination folder, input the URL, and execute the download.

> **Note on Windows SmartScreen:** Because this installer is unsigned and bundles the yt-dlp binary, Windows Defender or web browsers may flag the file as unrecognized or untrusted. Users must select "More Info" and then "Run Anyway" to proceed with the installation.

## Technical Specifications

- **Framework:** Electron, Node.js, HTML, CSS, JavaScript
- **Dependencies:** yt-dlp, browser-id3-writer
## License
This project is proprietary. See the [LICENSE](LICENSE) file for usage terms.
