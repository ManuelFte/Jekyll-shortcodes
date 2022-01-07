# Jekyll shortcodes 

Collection of shortcodes I use to insert stuff in my Jekyll blogs.

## List

+ [audio.html](./audio.html) - Embeds an audio clip. ([DEMO](https://manuel.life/holophonics-3d-sounds/))
  
    `{% include audio.html src="/path/to/audio.mp3" %}`

+ [googledoc.html](./googledoc.html) - Embeds a file (not uploaded to Google Docs) using Google Docs' viewer. ([DEMO](https://mini.manuel.life/ilusiones-opticas/))
  
    `{% include googledoc.html file="/path/to/file.pdf" %}`

+ [video.html](./video.html) - Embeds a video file using HTML5. ([DEMO](https://mini.manuel.life/agatha-all-along/))

    `{% include video.html src="/path/to/video.mp4" poster="/path/to/image.jpg" %}`

+ [youtube.html](./youtube.html) - Embeds a YouTube video. ([DEMO](https://mini.manuel.life/how-to-pick-up-a-cat/))

     `{% include youtube.html id="video-id" %}`