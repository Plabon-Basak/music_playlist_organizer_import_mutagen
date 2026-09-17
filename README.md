# Music Playlist Organizer

A command-line tool that scans a music folder, reads tag metadata with `mutagen`, and organizes tracks into an `Artist/Album` folder structure. It also writes a JSON summary of the metadata.

## Features

- Recursively scans for `.mp3`, `.flac`, and `.wav` files
- Extracts title, artist, album, and genre using `mutagen`
- Moves files into `Artist/Album` folders
- Saves a `music_summary.json` with all extracted metadata

## Usage

```bash
pip install mutagen
python app.py
```

It will ask for:

1. **Music directory** - the folder to scan
2. **Output directory** - where organized folders are created

## Requirements

- Python 3.x
- `mutagen`

## License

This project is provided for educational purposes.