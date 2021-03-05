#  Images, Color, Text ...

## Images

### There are hundreds of image formats available each with a specific use case, these 3 formats together comprise of more than 95% of all images loaded on websites. However, these 3 image formats have significant differences amongst themselves thus making each of them suitable for specific use cases.

#### Uses: 
- Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth. 
- Use PNG format for any image that needs transparency or for images with text & objects with sharp contrast edges like logos. 
- Use GIF format for images that contain animations. 

### Compression
Almost all forms of data that we see on the internet — text, image, video etc. — are compressed to reduce the size of data and ensure faster transmission. 
Choosing the correct format and compression is a major factor that determines image size. 
Compression can be of two types — **lossless** and **lossy**. In lossless compression, it is possible to reconstruct the original image from the compressed image because there is no information loss during compression. 
This is not the case in lossy compression i.e. data loss in lossy compression is irreversible. Lossy compression algorithms always have a superior compression ratio (the ratio of size of compressed image to original image) as compared to lossless compression. 
However, this compression ratio comes at a cost of reduced quality that becomes more evident after zooming in on the image. 
This noticeable reduction in quality or distortion of the image is called ***compression artefact***.

* JPEG is a lossy compression specification that takes advantage of human perception. 
It can achieve compression ratios of 1:10 without any perceivable difference in quality. 

[JPEG Image](https://miro.medium.com/max/1050/1*HnECuWHjR2g4V7RAGmdmrg.jpeg)
JPEG image of Taj Mahal which is indicative of a natural scene. Size of this image is 127KB. 
Even though further compression is still possible for this image, it still is the lightest of the three formats. 
Source: http://voyage.gentside.com/taj-mahal/wallpaper

* PNG is a lossless image format using DEFLATE compression. 
No data is lost during compression and no compression artefacts are introduced in the image. 
For this reason, a PNG image would retain higher quality than an image than JPEG and would look a lot sharper, it would also occupy more space on the disk.

[PNG Image](https://miro.medium.com/max/1050/1*sD2tU56l8y1jF4BPQdWNYA.png)
PNG image of Taj Mahal which is indicative of a natural scene. Size of this image is 714KB. 
Though it looks identical to the JPEG image above, it is the largest among the three formats indicating the unsuitability of PNG for natural images. 
Source: http://voyage.gentside.com/taj-mahal/wallpaper

* GIF is also a lossless image format that uses LZW compression algorithm. 
It was favoured over PNG for simple graphics in websites in its early days because the support of PNG was still growing. 
Given that PNG is now supported across all major devices and that PNG compression is about 5–25% better than GIF compression, 
GIF images are now mainly used only if the image contains animations.

[GIF](https://miro.medium.com/max/1050/1*RC1_APSn_bNGP4dYpR9MJw.gif)
GIF image of Taj Mahal. If you look closely, there is a lot of noise around the right most tree top and the sky. 
The size of this image is 230KB. Source: http://voyage.gentside.com/taj-mahal/wallpaper

### Transparency
In a simple form, transparency indicates something that is completely invisible. 
Logos and icons often need to be placed on backgrounds with variable colours. 
Hence it is desirable, that the background of these logos and icons is made transparent so that a single image can be used over multiple background variations.

JPEG images don’t support transparency and are hence not usable for such cases.
PNG images support transparency in two ways — inserting an alpha channel that allows partial transparency or by declaring a single colour as transparent (index transparency). 
GIF images support transparency by declaring a single colour in the colour palette as transparent (index transparency). GIF is unsuitable for images with transparent backgrounds.

### Colours
There is a significant difference in the number of colours that can be supported by these 3 formats:

JPEG images can support around 16 million colours. 
This is what makes them suitable for storing images of natural scenes.

PNG images mainly have two modes — PNG8 and PNG24: 
PNG8 can support upto 256 colours whereas PNG24 can handle upto 16 million colours like a JPEG image. 
Use PNG8 for simple shapes with fewer colours and PNG24 for high quality, complex logos and shapes with rounded corners on a transparent background.

GIF images are limited to 256 colours. 
If index transparency is used, then one of these 256 colours is assigned as transparent and the remaining 255 are used for other colours.

### Animation
Animation, in this case, refers to any change or movement in the image. 
It doesn’t necessarily have to have frame rates like an animated video, but essentially a part or the entire image changes with time.
Of these 3 formats, only GIF supports animation. This capability makes GIF format suitable for delivering engaging ads and banners. 
Of late, with the advent of companies Tumblr, 9Gag, Giphy etc. the use of GIF format for memes has picked up.
[Omemes :cat2:](https://giphy.com/gifs/silicon-valley-l0K4jMNck0La1a7aU?utm_source=iframe&utm_medium=embed&utm_campaign=Embeds&utm_term=https%3A%2F%2Fcdn.embedly.com%2F)




