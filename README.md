# YouTube Playback Speed Bookmarklets

This repository contains simple bookmarklets for changing YouTube playback speed. The bookmarklets live in `bookmarklets.txt` and can be copied into a browser bookmark URL field.

## Available bookmarklets

### Playback at 3x
```
javascript:(()=>{document.querySelector('video').playbackRate=3.00})()
```

### Playback at a prompted speed (default 2.75x)
```
javascript:(()=>{document.querySelector('video').playbackRate=parseFloat(prompt('Video%20Playback%20Speed','2.75'))})()
```

## Usage
1. Copy a bookmarklet URL from `bookmarklets.txt` or this README.
2. Create a new bookmark in your browser and paste the URL into the location/URL field.
3. While watching a YouTube video, click the bookmark to change playback speed.

## Maintenance
- Update `bookmarklets.txt` when adding or modifying bookmarklets.
- Keep this README in sync with any changes to the bookmarklets.
