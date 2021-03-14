Read: 11 - Assorted Topics | Readings : Audio, Video, Images

# Audio
HTML5 provides a new standard for embedding an audio file on a web page.
You can embed an audio file to a page using the <audio> element:
<audio controls>
<source src="file.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio>
  
# Video
You can embed also a video to a webpage using the <video> element:
<video width="500" height="700" controls>
<source src="video.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
  
# Using `<video>` and `<audio>` element to display
audio/video content
Use the HTML or <audio> element to embed video/audio content in a document. The video/audio element contains
one or more video/audio sources. To specify a source, use either the src attribute or the <source> element; the
browser will choose the most suitable one.
  
Audio tag example:
<!-- Simple video example -->
<video src="videofile.webm" autoplay poster="posterimage.jpg">
Sorry, your browser doesn't support embedded videos,
but don't worry, you can <a href="videofile.webm">download it</a>
and watch it with your favorite video player!
  
</video>
<!-- Video with subtitles -->
<video src="foo.webm">
<track kind="subtitles" src="foo.en.vtt" srclang="en" label="English">
<track kind="subtitles" src="foo.sv.vtt" srclang="sv" label="Svenska">
</video>
<!-- Simple video example -->
<video width="480" controls poster="https://archive.org/download/WebmVp8Vorbis/webmvp8.gif" >
<source src="https://archive.org/download/WebmVp8Vorbis/webmvp8.webm" type="video/webm">
<source src="https://archive.org/download/WebmVp8Vorbis/webmvp8_512kb.mp4" type="video/mp4">
<source src="https://archive.org/download/WebmVp8Vorbis/webmvp8.ogv" type="video/ogg">
Your browser doesn't support HTML5 video tag.
  
</video>
Audio tag example:
<!-- Simple audio playback -->
<audio src="http://developer.mozilla.org/@api/deki/files/2926/=AudioTest_(1).ogg" autoplay>
Your browser does not support the <code>audio</code> element.
</audio>

<!-- Audio playback with captions -->
<audio src="foo.ogg">
<track kind="captions" src="foo.en.vtt" srclang="en" label="English">
<track kind="captions" src="foo.sv.vtt" srclang="sv" label="Svenska">
</audio>


# Creating an image
To add an image to a page, use the image tag.
Image tags (img) do not have closing tags. The two main attributes you give to the img tag are src, the image source
and alt, which is alternative text describing the image.

<img src="images/hello.png" alt="Hello World">
You can also get images from a web URL:
<img src="https://i.stack.imgur.com/ALgZi.jpg?s=48&g=1" alt="StackOverflow user Caleb Kleveter">
Note: Images are not technically inserted into an HTML page, images are linked to HTML pages. The <img> tag

creates a holding space for the referenced image.
It is also possible to embed images directly inside the page using base64:
<img src="data:image/png;base64,iVBOR..." alt="Hello World">
Tip: To link an image to another document, simply nest the <img> tag inside <a> tags.

# Choosing alt text
Alt-text is used by screen readers for visually impaired users and by search engines. It's therefore important to
write good alt-text for your images.

The text should look correct even if you replace the image with its alt attribute. For example:
<!-- Incorrect -->
<img src="anonymous.png" alt="Anonymous user avatar"/> An anonymous user wrote:
<blockquote>Lorem ipsum dolor sed.</blockquote>
<a href="https://google.com/"><img src="edit.png" alt="Edit icon"/></a> /
<a href="https://google.com/"><img src="delete.png" alt="Delete icon"/></a>



