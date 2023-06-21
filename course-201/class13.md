# Local Storage and How To Use It On Websites

Why would a developer use local storage for a web application?

> Local storage allows you to cache some data so that the next time they load the page, the user doesn't have to wait as long for you to summon it from the either, it's being pulled locally instead. This also is useful for things like pages where you need to log in, as otherwise as soon as you left the page any data and memory the site had of the user would go away.

What information should not be stored in local storage?

> Don't be a dick and use it to spy on folks, for one. But you also have limited space, so images, videos, and music files are probably not ideal either. Most of the useful things seem to be data you're otherwise pulling from other pages that take longer to pull, personal data that's helpful to store for repeat visits, like login info so you remain logged into a page, and settings the user has changed so that they'll still be that way when the user returns.

Local storage can store what type of data? How would you convert it to that type before storing?

> Local storage will only store strings, but you can run JSON.stringify() to essentially convert your code to a string so you can run JSON.parse() to convert it back to code again later.
