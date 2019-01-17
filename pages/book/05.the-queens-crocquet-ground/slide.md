---
title: 'The Queen’s Croquet-Ground'
style:
  color: '#eee8d5'
  background-color: '#3d879c'
---

## The Queen’s Croquet-Ground

![Croquet](https://vignette3.wikia.nocookie.net/disney/images/0/02/Alice-disneyscreencaps_com-7401.jpg/revision/latest/scale-to-width-down/1280?cb=20140424035629 "Croquet")

[notes]

Any content that Grav can render, can generally be used with the plugin. For example [other Shortcodes](https://github.com/getgrav/grav-plugin-shortcode-core) or [embedded media](https://learn.getgrav.org/content/media). If you need to add specific assets like CSS or JavaScript to the presentation, use the `presentation`-group when adding them through the [Asset Manager](https://learn.getgrav.org/themes/asset-manager#options), or extend the `presentation.html.twig`-template in your theme.

[/notes]

---

> ‘Idiot!’ said the Queen, tossing her head impatiently; and, turning to Alice, she went on, ‘What’s your name, child?’

‘My name is Alice, so please your Majesty,’ said Alice very politely; but she added, to herself, ‘Why, they’re only a pack of cards, after all. I needn’t be afraid of them!’

The Queen turned crimson with fury, and, after glaring at her for a moment like a wild beast, screamed ‘Off with her head! Off —’

[notes]

There are many ways of using or extending the Plugin, see its [homepage](https://github.com/OleVik/grav-plugin-presentation#extending) for details.

[/notes]

---

[data-background-image=https://vignette3.wikia.nocookie.net/disney/images/8/8a/Alice-disneyscreencaps_com-7771.jpg/revision/latest/scale-to-width-down/1280?cb=20110525015050]
[data-background-size=contain]
[style-background-color=transparent]

[notes]

This slide uses `data-background-*` shortcodes that correspond to the Reveal.js [options for Slide Backgrounds](https://github.com/hakimel/reveal.js/#slide-backgrounds), yielding an image as the background for the slide.

Note how `style-background-color=transparent` is used to unset the color that are applied to all slides within this Page, to make sure it does not block out the video.

[/notes]

---

[data-background-video=https://dl3.webmfiles.org/big-buck-bunny_trailer.webm]
[data-background-video-loop=true]
[data-background-video-muted=true]
[data-background-size=contain]
[style-background-color=transparent]

[notes]

This slide uses `data-background-*` shortcodes, yielding a video as the background for the slide. In this instance, it is a short excerpt from the Open Source 2008 short [Big Buck Bunny](https://en.wikipedia.org/wiki/Big_Buck_Bunny).

[/notes]