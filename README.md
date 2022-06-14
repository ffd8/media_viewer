# media_viewer
v0.2  
cc [teddavis.org](https://teddavis.org) 2020 – 22  
 
just a simple tool to help you glitch file formats.   
works by refreshing media at given rate w/o cache to see changes.  
use any image/audio/video/font format that can be viewed in the browser.  
**media file MUST sit in same folder as media_viewer.html**

### install
- download/clone package
- drag + drop `media_viewer.html` into directory of media

### usage
- drag + drop `media_viewer.html` web browser

- drag + drop your media file into browser window   
optional, manually select media type first (prevents auto guessing)  
optional, mute if audio/video

- adjust refresh rate as needed  
click refresh box to manually reload

- open media file in hexeditor + have fun glitching!

### issues
- *no changes or disappeared?!*  
you probably broke the file..  
↪ undo + save a few times

- *file won't load?!*  
check that `media_viewer.html` IS within same folder as your media file...  
check media type above (disable auto)  
check console.log for file info   
↪ search for js lib to support media type