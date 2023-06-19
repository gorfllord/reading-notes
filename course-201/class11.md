# Audio, Video, Images

### Video and Audio Content

Explain how the ability to use video and audio on the web has evolved since the early 2000s.

> In the early 2000s, flash and silverlight plugins were how most people were using video, but those have since become obsolete, plus they had some security issues. Now we're into mpegs and supporting larger files and the like. The other main difference between the early 2000s and today is that now we have mobile devices to worry about, so we want to worry about not using too much bandwidth if we don't have to on smaller screens.

Describe the use of the src and controls attributes in the \<video> element.

> The src attribute is where it's pulling the video from, much like an img tag. Controls makes sure you have playback controls so the user can play/pause and adjust volume as necessary.

Why is it important to have fallback content inside the \<video> element?

> Fallback content allows for a way to view or link to the content if the initial version didn't load right or wasn't supported by the browser. You can link in a different filetype just in case or you can have it display text with an external link, for example.

Write a very short story where \<audio> and \<video> are characters.

> Once upon a time, there was an audio file and a video file. These two dreamed of one day being viewed by a fabled being called "User". In preparation for this sacred ritual, they studied and learned some contingency plans to assure a visit from the Fabled One that would allow them to be seen or heard even if the legendary chariot "Browser" was an... older model. Once the day came, they were able to convey their splendor to User because they wore the proper tags, adorned with extra incantations that summoned upon their contingency plans if the opportunity so chose. Video even found a way to change size and don a fancier look before being accessed for the contents within them.

### A Complete Guide To Grid

How does Grid layout differ from Flex?

> Grid allows you to display things in... a grid. Not to use the word in the definition, but it's pretty much right in the name. It's great! Some of the attributes are similar between the two, however Grid is geared around distinct columns to populate, thinking in two dimensions instead of just the one-dimension that flex does. They work well together if you utilize flex within cells.

Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

> Grid container is the container element where Grid is being applied. Grid items are the children of the grid container. Grid lines are the dividing lines between cells.

### Responsive Images

Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

> The biggest thing, and different screen sizes partially covers this but not completely, is accessibility for mobile devices. It allows you to adjust for both screen size and scaling down to save on bandwidth for mobile devices that might be more of a stickler for bandwidth because of those pesky ISPs and their wily ways.

Define the following \<img> attributes srcset and sizes. Write an example of how they are used.

> srcset allows you to define multiple options to display different sizes. This is especially helpful for factoring in smaller displays, or even bigger displays! You can have it be dynamic depending on their screen resolution so if it's a tiny screen it'll load a smaller image to save bandwidth, or if it's a huge screen you can have it a load a larger image to take up more space.

How is srcset more helpful for responsive images than CSS or JavaScript?

> srcset is more helpful because it handles the image situation before the image itself gets loaded, so you don't have to worry about unnecessary bandwidth usage by loading multiple images, or loading the big image for a small screen that would otherwise not get used.
