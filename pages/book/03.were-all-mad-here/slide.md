---
title: We're all mad here
---

## We're all mad here

The Cat only grinned when it saw Alice. It looked good- natured, she thought: still it had *very* long claws and a great many teeth, so she felt that it ought to be treated with respect.

[notes]

Unlike the previous slides, this Page does not set any universal styles, so it uses the theme from Reveal.js. By default, the plugin has `theme: moon` set.

[/notes]

---

![Alice speaks to Cheshire Cat](https://vignette2.wikia.nocookie.net/disney/images/8/82/Alice-disneyscreencaps_com-4540.jpg/revision/latest/scale-to-width-down/1280?cb=20120226191734 "Alice speaks to Cheshire Cat")

[notes]

Notes are written within an opening and a closing `notes`-shortcode, and can also contain any Markdown.

[/notes]

---

[style-color=#eee8d5]
[style-background-color=#9C3D94]
[data-textsize-scale=1.25]
[data-textsize-modifier=0.75]

## Talking to the Cat

### Alice


> ‘Would you tell me, please, which way I ought to go from here?’

### The Cat

> ‘That depends a good deal on where you want to get to,’

### Alice

> ‘I don’t much care where —’

### The Cat

> ‘Then it doesn’t matter which way you go’

[notes]

This slide uses the `data-textsize-scale` and `data-textsize-modifier` shortcodes. If Textsizing is enabled in the plugin, this can be used to dynamically change the size of the headers relative to the body text.

The `data-textsize-modifier`-shortcode proportions the base pixel size for the slide by multiplying with it, whilst `data-textsize-scale` sets the rhythm to apply to headings. The higher the number the scale is, the more distance there will be between header font sizes and the base font size. `1.125` is also known as the Major Second in musical terms, otherwise expressed as "8:9", and yields this particular distance between the headers and the block text.

Base font sizes are determined by the `breakpoints`-option, which matches the breakpoint using `bigger than or equal to` width of the browser's viewpoint, and sets the base font size from the given value.

[/notes]

---

## Finding her way

[style-color=#eee8d5]
[style-background-color=#9C3D94]
[data-textsize-scale=1.25]
[data-textsize-modifier=0.75]

> ‘— so long as I get *somewhere* ,’

Alice added as an explanation.

> ‘Oh, you’re sure to do that,’

said the Cat,

> ‘if you only walk long enough.’

Alice felt that this could not be denied, so she tried another question. 

> ‘What sort of people live about here?’

To which the Cat replied, waving its paws round,

> ‘In *that* direction, lives a Hatter: and in *that* direction, lives a March Hare. Visit either you like: they’re both mad.’

[notes]

The plugin treats content just as Grav does: Using [Parsedown](https://github.com/erusev/parsedown) to render Markdown content, and Pages to create slides. When a Page contain sections, create by horizontal rules in HTML, it is split up in slides as well.

This and the previous slide has `data-textsize-modifier` set to `0.75`, which means 75% of normal base font size will be applied.

[/notes]