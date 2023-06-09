# Images, Color, Text

### HTML Media

What is a real world use case for the alt attribute being used in a website?

> alt is used to provide alt-text that can be used for screen reader users to have a description of what the image is, it's also great in case the image doesn't load or takes awhile to load so that they have a description of what's supposed to be there. Overall, it's good to use it for accessibility.

How can you improve accessibility of images in an HTML document?

> use alt text! don't use titles unless you're XKCD! Use figcaption!

Provide an example of when the figure element would be useful in an HTML document.

> Figure elements are great to use if you want an image with a caption and have it be all in one block. Great for citing image sources or providing additional info about an image, or maybe even just a snarky comment to help drive your point home.

Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.

> Alright, so, a GIF is an image with multiple frames, almost like a mini video. SVG is a vector image, which means if you make the image bigger or smaller, it will scale all of the dimensions based on the size, so if you make it REALLY big, it doesn't look grainy and bad as you go past it's original size. It can be any size!

What image type would you use to display a screenshot on your website and why?

> I would use an PNG file, as it's an efficient size and has good color depth. jpegs can be too lossy when the compression is applied, PNG files are truer to their original form post-compression. It's also a widely accessible file-type, unlike some other filetypes that might be better quality.

### CSS

Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.

> Foreground color is the color of the content, like text. Background color is the color behind it, the box that it might be in, or a color around the text that looks like it has been highlighted.

Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?

> I would use CSS to make any changes to the HTML of the page, first and foremost. I would perhaps add a soft color for the background and a bold color with higher contrast for the text. Probably like a light blue with black text, while bringing in other color to more decorative elements like borders around sections, or perhaps if there's a navigation bar I would use a different color to differentiate it from the main content.

What should you consider when choosing fonts for an HTML document?

> You should consider what most browsers will support when choosing a font, but also what sort of broad vibe you're going for, like if you want a serif font or a sans-serif font. The important thing seems to be to provide multiple options in a font-family in case a browser doesn't have your first choice, or even possibly second choice. Most of it is for accessibility, especially when considering older devices and older versions of browsers.

What do font-size, font-weight, and font-style do to HTML text elements?

> These three attributes will change the size, boldness, or italicized-ness of the text element. So if you wanted it to be real big, real bold, and italicized, you could set font-size to 3rem, font-weight to bold, and font-style to italic or oblique and get what you're looking for.

Describe two ways you could add spacing around the characters displayed in an h1 element.

> You could change the letter-spacing or word-spacing properties to add more space between letters or words, respectively. Another option if you're looking to move the whole text inside the h1 tag is to add some padding.
