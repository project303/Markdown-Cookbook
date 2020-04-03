Embedding Youtube Videos
=====================================================
Pitifully, this is not possible till the date. However there's a little trick that allow you to create an image and redirect the user to the youtube video page.

Just replace the YOUTUBE_VIDEO_ID_HERE for the id of your video. An image will appear and will redirect automatically to the video in youtube.
```
<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE" target="_blank">
 <img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg" alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" />
</a>
```
or in pure markdown
```
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
```
