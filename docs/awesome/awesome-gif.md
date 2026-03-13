<div class="github-widget" data-repo="davisonio/awesome-gif"></div>
## Awesome GIF [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

> A curated list of awesome [GIF](https://en.wikipedia.org/wiki/GIF) resources.

A list of tools, scripts, libraries, examples & other resources related to the Graphics Interchange Format (GIF).


<!--lint disable awesome-toc-->

## General Tools

- [FFmpeg](https://www.ffmpeg.org)
- [ImageMagick](https://imagemagick.org/script/index.php)
- [GraphicsMagick](http://www.graphicsmagick.org/) - Usually faster than ImageMagick.
- [MoviePy](https://zulko.github.io/moviepy/) - Python module for video editing.

## Utilities

- [Gifgen](https://github.com/lukechilds/gifgen) - Simple high quality GIF encoding.
- [Gifify](https://github.com/jclem/gifify) - Convert screen recording into GIF.
- [Screengif](https://github.com/dergachev/screengif) - Create animated GIF screencasts.
- [Gifline](https://github.com/zehfernandes/gifline) - Chrome extension to put GIFs in your emails.
- [Tty2gif](https://github.com/z24/tty2gif) - Record scripts and their outputs into both binary and GIF formats.
- [Gifit](https://github.com/takempf/GIFit) - Chrome extension to make a GIF from a YouTube video.
- [Ccapture.js](https://github.com/spite/ccapture.js) - Capture animations created with HTML5 canvas.
- [Kap](https://getkap.co/) - Beautiful open-source app to capture your screen and export to GIF.
- [gifski](https://github.com/ImageOptim/gifski) - High-quality GIF encoder based on libimagequant.
- [Gifcurry](https://github.com/lettier/gifcurry) - Open-source, Haskell-built editor for GIF makers.

## Libraries

### C++

- [Gif-h](https://github.com/charlietangora/gif-h) - C++ one-header library for the creation of animated GIFs.
- [msf_gif](https://github.com/notnullnotvoid/msf_gif) - C/C++ single-header library for creating animated GIFs.

<h3 id="c-sharp">C#</h2>

- [dot-screencap](https://github.com/Speiser/dot-screencap) - A simple libary to record your screen and save it as animated GIF.
- [WpfAnimatedGif](https://github.com/XamlAnimatedGif/WpfAnimatedGif) - A simple library to display animated GIF images in WPF.
- [XamlAnimatedGif](https://github.com/XamlAnimatedGif/XamlAnimatedGif) - A simple library to display animated GIF images in XAML apps (WPF, WinRT, Windows Phone).
- [AnimatedGif](https://github.com/mrousavy/AnimatedGif) - A high performance .NET library for reading and creating animated GIFs.

### Haxe

- [Gif](https://github.com/snowkit/gif) - Haxe GIF encoder.

### Java

- [Android-gif-drawable](https://github.com/koral--/android-gif-drawable) - Views and Drawable for displaying animated GIFs on Android.
- [GifImageView](https://github.com/felipecsl/GifImageView) - Android ImageView that handles animated GIF images.
- [Gif-animation](https://github.com/extrapixel/gif-animation) - Processing library to play and export GIF.
- [Android-gif-encoder](https://github.com/nbadal/android-gif-encoder) - Animated GIF encoder for Android.

### JavaScript

- [Gif.js](https://github.com/jnordberg/gif.js) - Create GIF from the DOM.
- [Omggif](https://github.com/deanm/omggif) - GIF 89a encoder and decoder.
- [Animated_GIF](https://github.com/sole/Animated_GIF) - JavaScript library for creating animated GIFs.
- [Gifffer](https://github.com/krasimir/gifffer) - JavaScript library that prevents the autoplaying of the animated GIFs.
- [Gifplayer](https://github.com/rubentd/gifplayer) - JQuery plugin to play and stop animated GIFs.
- [node-gify](https://github.com/tj/node-gify) - JavaScript convert videos to GIFs using FFmpeg and gifsicle.
- [Gifencoder](https://github.com/eugeneware/gifencoder) - Server side animated GIF generation for Node.js.

### PHP

- [GifCreator](https://github.com/Sybio/GifCreator) - PHP class that creates animated GIF from multiple images.
- [GifFrameExtractor](https://github.com/Sybio/GifFrameExtractor) - PHP class that separates all the frames of an animated GIF.

### Objective-C

- [FLAnimatedImage](https://github.com/Flipboard/FLAnimatedImage) - GIF engine for iOS by FlipBoard.

### Swift

- [SwiftyGif](https://github.com/alexiscreuzot/SwiftyGif) - High performance & easy to use Gif engine.
- [Gifu](https://github.com/kaishin/gifu) - Animated GIF support for iOS in Swift.

## GUI

- [Qgifer](https://sourceforge.net/projects/qgifer/)

## Hosting

- [Imgur](https://imgur.com) - Maximum file upload is 50MB.

## Online Tools

- [EzGif](https://ezgif.com/) - Online GIF maker and image editor.
- [Giflr](https://giflr.com/) - A web app for making or remixing animated GIFs.
- [GIF Frame Extractor](https://giftoframes.org/) - Convert animated GIFs into individual frames online.

## Community

- [Giphy.com](https://giphy.com)
- [/r/educationalgifs](https://www.reddit.com/r/educationalgifs/)

## Scripts

### Frames to GIF

FFmpeg
```bash
ffmpeg -f image2 -i image%d.jpg animated.gif
```

ImageMagick
```bash
magick -delay 20 -loop 0 frames*.png animated.gif
```
Bash script (```frames2gif.sh```) for GraphicsMagick, ImageMagick, FFmpeg
```bash
#!/bin/bash
if [ $# -ne 5 ]; then
    echo "please provide the moviename and directory where to store the frames"
    echo "./frames2gif.sh [directory] [movie.mp4] [filename.gif] [gm|im|ffmpeg] [png|jpg]"
    exit 1
fi
    if [ "png" == "$5" ]; then
        suffix="png"
    else
        suffix="jpg"
    fi

    CONVERT=$(which magick)
    GM=$(which gm)
    FFMPEG=$(which ffmpeg)
    FFPROBE=$(which ffprobe)
    FPS=$($FFPROBE -show_streams -select_streams v -i "$2"  2>/dev/null | grep "r_frame_rate" | cut -d'=' -f2 | cut -d'/' -f1)
    echo "FPS: ${FPS}"
if [ "im" == "$4" ]; then # use imagemagick
    FPS=$(echo "1 / ${FPS} * 100" |bc -l)
    $CONVERT "$1/*.${suffix}"  -delay ${FPS} -loop 0 "$3"
elif [ "gm" == "$4" ]; then # use graphicsmagick
    FPS=$(echo "1 / ${FPS} * 100" |bc -l)
    $GM convert "$1/*.${suffix}"  -delay ${FPS} -loop 0 "$3"
else # use crappy gif-algorithm from ffmpeg
    $FFMPEG -f image2 -framerate ${FPS} -i "$1/%08d.${suffix}" "$3"
fi
```
From [DeepDreamVideo](https://github.com/graphific/DeepDreamVideo), [source](https://github.com/graphific/DeepDreamVideo/blob/master/frames2gif.sh)


### GIF to frames

```bash
ffmpeg -i video.mpg image%d.jpg
```
```bash
magick animated.gif -coalesce image%05d.png
```

### High quality GIF

with FFmpeg / based on this [article](http://blog.pkh.me/p/21-high-quality-gif-with-ffmpeg.html)

- Generate a palette :

```bash
#!/bin/sh
start_time=30
duration=3
ffmpeg -y -ss $start_time -t $duration -i input.avi \
-vf fps=10,scale=320:-1:flags=lanczos,palettegen palette.png
```
- Output the GIF using the palette :

```bash
#!/bin/sh
start_time=30
duration=3
ffmpeg -ss $start_time -t $duration -i input.avi -i palette.png -filter_complex \
"fps=10,scale=320:-1:flags=lanczos[x];[x][1:v]paletteuse" output.gif
```

### Optimize GIF

```bash
magick output.gif -layers Optimize output_optimized.gif
```

### Lossy GIF Compressor

```bash
./gifsicle -O3 --lossy=80 -o lossy-compressed.gif input.gif

```
[Lossy Gif](https://kornel.ski/lossygif)


### Making GIF from video

```python
from moviepy import VideoFileClip

clip = (VideoFileClip("input.avi")
        .subclipped((4,00.00),(5,00.00))
        .resized(0.3))
clip.write_gif("output.gif")

```
<!--lint ignore double-link-->
[article](http://zulko.github.io/blog/2014/01/23/making-animated-gifs-from-video-files-with-python/#converting-a-video-excerpt-into-a-gif)

### Cinemagraphs

Freezing a region

```python
from moviepy import VideoFileClip, vfx

clip = (VideoFileClip("input.avi")
        .subclipped((4,00.00),(5,00.00))
        .resized(0.3)
        .with_effects([vfx.FreezeRegion(outside_region=(170, 230, 380, 320))]))
clip.write_gif("output.gif", fps=15)
```
<!--lint ignore double-link-->
[article](http://zulko.github.io/blog/2014/01/23/making-animated-gifs-from-video-files-with-python/#freezing-a-region)

```bash
ffmpeg \
-ss ${starttime} -t ${duration} -i ${vidfile}                         `# body of loop` \
-ss TODO ${starttime} MINUS ${duration} -t ${fadetime} -i ${vidfile}  `# lead-in for crossfade` \
-loop 1 -i ${stillfile}                                               `# masked still image` \
-filter_complex "
  [0:v]setpts=PTS-STARTPTS[vid];                                      `# speed adjustment - not needed here, so noop`
  color=white,scale=3840x2160,fade=in:st=0:d=${fadetime}[alpha];      `# crossfade alpha, double length ahead of speed change`
  [1:v][alpha]alphamerge[am];                                         `# apply alpha to lead-in`
  [am]setpts=PTS+(${duration}-${fadetime})/TB[layer2];                  `# speed adjustment and offset for lead-in`
  [vid][layer2]overlay[oo];                                           `# overlay for crossfade`
  [oo][2:v]overlay=shortest=1[out1];                                  `# overlay still image`
  [out1]crop=w=${cropfactor}*iw:h=${cropfactor}*ih:y=${yoffset}*ih,scale=${outputwidth}:-1, `# crop and scale`
  eq=gamma=${gamma}:contrast=${contrast}:saturation=${saturation},unsharp                   `# final adjustments`
" -an output.mp4
```

### Perfect Loop

```python
from moviepy import VideoFileClip
from moviepy.video.tools.cuts import FramesMatches

clip = VideoFileClip("input.avi").resized(0.3)
scenes = FramesMatches.from_clip(clip, 10, 3)

selected_scenes = scenes.select_scenes(2, 1, 4, 0.5)
selected_scenes.write_gifs(clip.resized(width=450), "./outputs_directory")

```
[article](http://zulko.github.io/blog/2015/02/01/extracting-perfectly-looping-gifs-from-videos-with-python-and-moviepy/)

### YouTube video to GIF

- Download it via yt-dlp and then convert it.

```bash
yt-dlp https://www.youtube.com/watch?v=V2XpsaLqXc8
```

[yt-dlp](https://github.com/yt-dlp/yt-dlp)

## Miscellaneous

- [Why is the GIF I created so slow?](https://superuser.com/questions/569924/why-is-the-gif-i-created-so-slow/569967) - Using ImageMagick to solve problems concerning GIF speed.

## Use

The best ways to use this list are:

- By browing the [contents](#contents).
- By using <kbd>command</kbd> + <kbd>F</kbd> to search the contents

## Credits

By [Craig Davison](https://davison.io) and contributors.

Based on a [recovered list](https://github.com/sindresorhus/awesome/issues/872) by [Ismail Baaj](https://ismailbaaj.fr).
