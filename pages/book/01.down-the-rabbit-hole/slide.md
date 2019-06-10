---
title: Down the Rabbit-Hole
textsize:
  scale: '1.25'
---

## Down the Rabbit-Hole

Alice was beginning to get very tired of sitting by her sister on the bank, when suddenly a White Rabbit with pink eyes ran close by her.

[notes]

Like Alice, look downwards and notice the navigational arrows. Reveal.js let's you navigate vertically, as well as horizontally. When presenting, the linear progression is to go downwards, then to the right when there are no more slides below.

You can, however, navigate freely between the slides using the Overview, by pressing `esc` or `o` on your keyboard.

[/notes]

---

[style-color="white"]
[style-font-weight="bold"]
[style-background-image="dress-color.png"]

There was nothing so *very* remarkable in that; nor did Alice think it so *very* much out of the way to hear the Rabbit say to itself, 

> ‘Oh dear! Oh dear! I shall be late!’ 

The Rabbit actually *took a watch out of its waistcoat-pocket* , and looked at it, and then hurried on...

[notes]

These pages are structured like this:

```
/user/pages/book
├── presentation.md
├── 01.down-the-rabbit-hole
│   └── slide.md
├── 02.advice-from-a-caterpillar
│   └── slide.md
├── 03.were-all-mad-here
│   └── slide.md
├── 04.a-mad-tea-party
│   └── slide.md
├── 05.the-queens-crocquet-ground
│   └── slide.md
├── 06.postscript
└───└── slide.md
```

Each slide.md uses `---` to create thematic breaks for vertical slides.

This slide uses shortcodes to declare a custom text color, font weight, and background image.

[/notes]

---

[class="skinny"]

![White Rabbit checking watch](https://vignette1.wikia.nocookie.net/disney/images/c/c9/Tumblr_mvvwp4QVau1qhcrb0o1_1280.jpg/revision/latest/scale-to-width-down/1280?cb=20131108181614 "White Rabbit checking watch")

[notes]

This slide uses a shortcode to change the class of the slide to `skinny`. You can create any customizations you want in your theme by creating `/user/themes/MYTHEME/css/custom.css`, in which you add your own classes. The plugin automatically looks for that file and loads it if found.

[/notes]

---

Alice started to her feet, for it flashed across her mind that she had never before seen a rabbit with a waistcoat-pocket, and burning with curiosity, she ran across the field after it, just in time to see it pop down a large rabbit-hole under the hedge.

In another moment down went Alice after it, never once considering how in the world she was to get out again.

[notes]

The plugin, through Reveal.js, can handle varying amounts of text on each slide. The plugin uses some custom CSS -- and as we shall see later, some extra logic -- to enhance the Reveal.js defaults.

[/notes]