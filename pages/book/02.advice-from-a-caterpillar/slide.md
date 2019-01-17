---
title: Advice from a Caterpillar
style:
  color: '#eee8d5'
  background-color: '#be281b'
---

## Advice from a Caterpillar

[notes]

The following slides belong to the same Page in Grav, which has declared the following FrontMatter:

```yaml
style:
  color: '#eee8d5'
  background-color: '#be281b'
```

Because the Page declares this, all slides within the Page have the same styles applied.

[/notes]

---

It was the White Rabbit, trotting slowly back again, and looking anxiously about as it went, as if it had lost something; and she heard it muttering to itself

> The Duchess! The Duchess! Oh my dear paws! Oh my fur and whiskers! She’ll get me executed, as sure as ferrets are ferrets! Where *can* I have dropped them, I wonder?

[notes]

Like with [normal Markdown](https://daringfireball.net/projects/markdown/basics), Grav -- and hence the Plugin -- supports a syntax that is easy to read and write as normal text.

[/notes]

---

[fragment=highlight-current-red]The Caterpillar and Alice looked at each other for some time in silence: at last the Caterpillar took the hookah out of its mouth, and addressed her in a languid, sleepy voice.[/fragment]

[fragment=highlight-current-red]> ‘Who are *you* ?’ said the Caterpillar.[/fragment]

[notes]

This slide uses [fragments](https://github.com/hakimel/reveal.js/#fragments), which highlight individual elements on a slide. Each fragment must be wrapped in a `fragment`-shortcode, with no newlines within it -- the syntax does not allow for this currently. You can also pass a fragment-style in as the parameter.

[/notes]

---

![Alice meets the Caterpillar](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8a/John_Tenniel_-_Illustration_from_The_Nursery_Alice_%281890%29_-_c06543_03.jpg/737px-John_Tenniel_-_Illustration_from_The_Nursery_Alice_%281890%29_-_c06543_03.jpg "Alice meets the Caterpillar")

[notes]

Normal images are rendered as Grav would, but the Plugin centers them automatically.

[/notes]