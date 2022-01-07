# Jekyll shortcodes 

Collection of shortcodes I use to insert stuff in my Jekyll blogs.

## List

+ [audio.html](./audio.html) - Embeds an audio clip. ([DEMO](https://manuel.life/holophonics-3d-sounds/))
  
    `{% include audio.html src="/path/to/audio.mp3" %}`

+ [googledoc.html](./googledoc.html) - Embeds a file (not uploaded to Google Docs) using Google Docs' viewer. ([DEMO](https://mini.manuel.life/ilusiones-opticas/))
  
    `{% include googledoc.html file="/path/to/file.pdf" %}`

+ [link.html](./link.html) - Allows to share an article from a website while including certain information like a thumbnail and a description, akin to a social media embed. ([DEMO](https://mini.manuel.life/solar-meets-100-per-cent-of-south-australia-demand-for-first-time/))
  
    ```
    {% include link.html
    title="Title of the article (Optional. If not specified, it'll take the title of the post it's embedded in)"
    url="https://example.com"
    author="Author of the linked article"
    site="Name of the linked site"
    image="/path/to/thumbnail.jpg (Optional. If not specified, it'll take the thumbnail of the article it's embedded in."
    %}
    ```

+ [spotify.html](./spotify.html) - Embeds a Spotify song. ([DEMO](https://mini.manuel.life/eagles-waiting-in-the-weeds/))

    `{% include spotify.html id="song-id" %}`

+ [video.html](./video.html) - Embeds a video file using HTML5. ([DEMO](https://mini.manuel.life/agatha-all-along/))

    `{% include video.html src="/path/to/video.mp4" poster="/path/to/image.jpg" %}`

+ [youtube.html](./youtube.html) - Embeds a YouTube video. ([DEMO](https://mini.manuel.life/how-to-pick-up-a-cat/))

     `{% include youtube.html id="video-id" %}`