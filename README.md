# bing-chat-dark-mode

This is a work in progress whose aim is to automate this.

At the moment, no official dark mode for Bing chat exists, however this list of manual steps does the trick:

- F12 (open developer console)
- Go to console tab
- Type `document.getElementsByTagName("cib-serp")[0].design.colorScheme=1;` and hit ENTER.

It will persist until the page is reloaded.
