# media_viewer
cc [teddavis.org](https://teddavis.org) 2020  
 
just a simple tool to help you glitch random formats.   
works by refreshing media at rate w/o cache to see changes.  
use any image/audio/video/font format that can be viewed in the browser.  
media file MUST sit in same folder as media_viewer.html

### install
- download/clone package
- drag + drop `media_viewer.html` into browser

### usage
- copy media file into `media_viewer` folder

- drag + drop media file into browser  
optional, manually select media type first (prevents auto guessing)  
optional, mute if audio/video

- adjust refresh rate as needed  
click refresh box to manually reload

- open media file in hexeditor  
have fun glitching!

### issues
- *no changes or disappeared?!*  
you probably killed the file..  
↪ undo + save a few times

- *file won't load?!*  
check media type above (disable auto)  
check console.log for file info  
↪ search for js lib to support media type