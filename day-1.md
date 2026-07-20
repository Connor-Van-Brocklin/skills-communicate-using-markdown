# Daily Learning

## Morning Planning
- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.

## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
Relative URL to an image in the repository:

```![Mona the Octocat](myrepo/original.png)```

Absolute URL to an image on the internet:

```![Mona the Octocat](https://octodex.github.com/images/original.png)```
Simple HTML
You will often find the need to reduce the size of an image or simply place it next to some text. Regular HTML syntax provides some additional flexibility.

The alt field specifies the alternative text.

The src field specifies the source url of the image.

A width and/or height field can be used to specify the size in pixels.

The align field allows setting a position (left, right)

<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png"
width="200" align="right">
```
<img alt="Mona the Octocat" src="https://octodex.github.com/images/original.png"
width="200" align="right">
```
⌨️ Activity: Add some decoration
Our blog post is quite simple right now. Let's add some decoration.

On the start-blog branch, open the day-1.md file for editing.

Insert an image below the Morning Planning level 1 heading.
![Cloudy morning](https://octodex.github.com/images/cloud.jpg)

```![Cloudy morning](https://octodex.github.com/images/cloud.jpg)```

Use the Preview tab to check your Markdown formatting.

Notice the image is too large for our purpose.
Replace the simple markdown version with an HTML version that includes size and position info. Much better!

```<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">```
