# Special Notes for Level 7 stuff

Well, this level is very complex and has a lot of things going on. So I decided to create a special file for the things I found in the level.

## Level 7

The code is:
```html
<html>
    <head>
        <title>Ik ben Brits, weet je nog...</title> 
        <link type="text/css" rel="stylesheet" href="../style.css">
        <audio src="../stuff/mayscrm01.mp3" autoplay loop></audio>
        <!-- <audio src="./mayscrm01a.mp3" autoplay loop></audio> -->
    </head>
    <body>
        <img src="screen7a.jpg" usemap="#incredible">
        <map name="incredible">
            <area alt="How dare you touch my sausage!" href="/levels/incredible"
                coords="417,150,427,206,443,276,469,362,492,454,518,554,541,607,576,631,594,644,605,645,618,641,627,643,633,626,640,617,655,608,659,579,663,523,647,439,630,354,563,180,538,128,513,99,477,84,438,93,417,115"
                shape="poly">
        </map>
        <!--
            See the real file to see all the comments
            -->
    </body>
</html>
```

The title of this level is "I'm British, remember..." so, is the following staff related?

There are so many images that I'm kinda lost. The sausages images have a highlighter that fade in. At the end of the train of images, there is a text that says:
```txt
What it everything you expected? You can stop looking now...
No really, that wasn't cryptic. This is actually the end of the image train.
```
But, as the last image text suggest, there is an extra image. A weird sausage man with a sausage in its hand.

At the middle of the train (not exactly the middle but anyway) is a keyboard image. That reveals a url. To reveal the url follow the comments in the body of the html that indicates [row]["column" number] on the keyboard. The url is `tick.htm`. That sends you to lvl 7bis.

### The last image

About this image, I just have no words. I just found [this](https://www.youtube.com/watch?v=mt5_zxOwkJk) video. What the hell is that????

### Other

Idk if this is actually related to he level, but there is an artist called Aitch ([see](https://en.wikipedia.org/wiki/Aitch_(rapper))) that is Brithish (as the title of the page suggest!).

## Level 7bis

In this level the html code is just very simple to "think" that is something hidden:
```html
Ah great! You've cracked the code. So what? This isn't the end. Get <i>down</i> to business!
<br />
<span style="color: #fafafa;">
    00:00:00s
    00:00:24s
</span>
```
What do the numbers mean? Actually more than you can guess. If you look carefully into the level 7 html code, you will see that there is a second audio file. That file contains *["Dr. Martin Luther King Jr. August 28, 1963. Lincoln Memorial in Washington D.C."](http://analytictech.com/mb021/mlk.htm)* What is that? Shortly speaking is like a very large and political (I guess) speech in which they give the rights to black people.

But the weird part is that the audio itself has 27 seconds of duration and the artist is "You're a fucking wizard." So... What the hell that means?
