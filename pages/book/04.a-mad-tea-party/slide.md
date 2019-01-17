---
title: A Mad Tea-Party
style:
  color: '#eee8d5'
  background-color: '#5dcddf'
---

[style-justify-content=center]

## A Mad Tea-Party

There was a table set out under a tree in front of the house, and the March Hare and the Hatter were having tea at it: a Dormouse was sitting between them, fast asleep, and the other two were using it as a cushion, resting their elbows on it, and talking over its head. ‘Very uncomfortable for the Dormouse,’ thought Alice; ‘only, as it’s asleep, I suppose it doesn’t mind.’

[notes]

This slide uses a `style-justify-content` set to `center` to align content in the middle vertically.

[/notes]

---

The table was a large one, but the three were all crowded together at one corner of it: ‘No room! No room!’ they cried out when they saw Alice coming. ‘There’s *plenty* of room!’ said Alice indignantly, and she sat down in a large arm-chair at one end of the table.

> ‘Have some wine,’ the March Hare said in an encouraging tone.

Alice looked all round the table, but there was nothing on it but tea. ‘I don’t see any wine,’ she remarked.

[notes]

When synchronizing, and the GET-parameter `admin` is set to `yes`, you are [controlling the presentation](./?admin=yes&showNotes=true). Commands are sent from the browser-window that controls the presentation to any other browser-window accessing it normally.

For this to actually have an effect the `sync`-option in the plugin's settings must be set.

[/notes]

---

> ‘There isn’t any,’ said the March Hare.

> ‘Then it wasn’t very civil of you to offer it,’ said Alice angrily.

> ‘It wasn’t very civil of you to sit down without being invited,’ said the March Hare.

> ‘I didn’t know it was *your* table,’ said Alice; ‘it’s laid for a great many more than three.’

[notes]

If `sync` is set to `browser`, commands are only shared between windows in the same browser - so you'd open a new window and drag it to another screen.

If `sync` is set to `poll`, the presentation can be controlled remotely. When viewing the presentation, the slides are controlled by checking with the website if they have changed.

[/notes]

---

![A Mad Tea Party](https://vignette4.wikia.nocookie.net/disney/images/c/c0/Tea-party-in-wonderland.jpg/revision/latest/scale-to-width-down/1280?cb=20140907031444 "A Mad Tea Party")

[notes]

Commands are logged in the browser's console, which you can open using the browser's developer tools. If using the `poll`-mode, a notification will be displayed to the user asking them to reload the window, if the connection to the server is lost.

[/notes]