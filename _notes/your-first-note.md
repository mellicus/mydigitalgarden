---
title: Your first seed
---

### Welcome!

*Consciousness* is at once the most certain of all realities and the grandest unknown and sublime mystery of our existence, apart perhaps from only our existence itself. Why does it feel something to be alive? Why does existing have a _taste?_ Humanity has wrestled so much with this conundrum that in philosophy it is now known through an unequivocal nickname: the [[_hard problem_]]. The hard problem of consciousness is the problem of explaining why and how some organisms have phenomenal experiences—how and why it is that some internal states are _felt_, such as heat or cold, the quality of deep blue, or the sensation of a musical note. How can we explain why there is something it is like to entertain a thought or to have an emotion? Even if one accepts that experience arises from a physical basis, it is still unclear why and how it so arises. The question asked is not only how it is possible that we are conscious but _why_ is there something that it is like to be us, in the first place?Answering this question may uncover all sorts of horror about the nature of our very existence and of the universe in general. For often, questions about consciousness necessarily lead us to gaze at the abyss that is the _fundamental_—_and cosmic_—_question of metaphysics:_ why is there something instead of nothing? Self-interrogations about why I am conscious, reflections (both literal and metaphorical) in front of a mirror on the strange semantics of words like ‘I’, ‘me’—why is this me? How come this is me? Or general awe at the concept of subjectivity, of ‘I-ness,’ of being a self—naturally bring about the even harder question of ‘why do I exist’?

For Martin Heidegger, it was only through _Dasein_ that the problems of being and existence could be posed, that is to say that it is only through consciousness that existence presents problems. The horror of consciousness is the horror of existence. And consciousness has a horrific, weird component (as does existence), or better, to put it in Mark Fisher’s words, it contains a profoundly _eerie_ component. The feeling of the eerie is concerned with the inexplicability of certain agencies: when there are traces and signs of an agency that shouldn’t be there or there is a lack of signs and traces of an agency that is there, we feel that something eerie is going on. And the phenomenon of consciousness is precisely this: the existence of an agency that shouldn’t be there, it is not even close to clear why some bare flesh, organic wet matter, should give rise to the world of most beautiful endless forms that is our inner life. So consciousness is a phenomenon that we can’t even hope to explain and that we don’t fully comprehend; and yet that consciousness is us, the same entity that it is posing the problem. 

**Subjects are the very aliens to themselves, and subjectivity is eerie.**

### Link syntax

To link to another note, you can use multiple syntaxes. The following four use the "double-bracket" notation ([view the Markdown source file](https://github.com/maximevaillancourt/digital-garden-jekyll-template/blob/master/_notes/your-first-note.md#link-syntax) to see the underlying syntax).

- Using the note title: [[a note about cats]]
- Using the note's filename: [[cats]]
- Using the note's title, with a label: [[A note about cats|link to the note about cats using the note title]]
- Using the note's filename, with a label: [[cats|link to the note about cats using the note's filename]]

You can organize notes in subdirectories and link them normally. For example, the links above all point to the `_notes/animals/cats.md` file. Here's another example: [[tigers]].

Non-latin languages are supported too: [[안녕하세요]].

Dashes and underscores in file names are supported, and may be omitted in the bracket link syntax. As an example, the `your-first-note.md` file can be linked to with [[your first note]] or [[your-first-note]], or even [[yOuR-FiRsT Note]].

In all cases, if the double-bracket link does not point to a valid note, the double brackets will still be shown, like this: [[there is no note that matches this link]].

Alternatively, you can use regular [Markdown syntax](https://www.markdownguide.org/getting-started/) for links, with a relative link to the other note, like this: [this is a Markdown link to the note about cats](/cats){: .internal-link}. Don't forget to use the `.internal-link` class to make sure the link is styled as an internal link (without the little arrow).

Since the Web is all about HTML, you can always use plain HTML if you want, like this: <a class="internal-link" href="/cats">This is a link to the note about cats with HTML</a>.

Of course, you can also link to external websites, like this: [this is a link to Wikipedia](https://wikipedia.org/). Again, you can use plain HTML if you prefer. Footnotes are also supported and will be treated like internal links.[^1] You can point to other notes in your footnotes.[^2]

[^1]: This is a footnote. For more information about using footnotes, check out the [Markdown Guide](https://www.markdownguide.org/extended-syntax/#footnotes).
[^2]: This is another footnote that links to the note about [[cats]]. You may also point to [[notes that do not exist]] if you wish.

### Tweet embedding

Note: This behavior is disabled by default for privacy reasons. See "Site configuration" section below to enable it.

You may include a tweet URL on its own line (like below), and it would be replaced with an official Twitter embed if the site configuration demands it.

https://twitter.com/jack/status/20

### Site configuration

Some behavior is configurable by tweaking the `_config.yml` file.

**`use_html_extension`**: if you use a static host that doesn't support URLs that don't end with `.html` (such as Neocities), try changing the `use_html_extension` value to `true` in the `_config.yml` file and restart the Jekyll server (or re-build the site). This adds a `.html` extension to note URLs and may resolve issues with links. If you're still having trouble, I recommend using Netlify to host your digital garden: it's free, easy to use, and fully supports this template's features out of the box.

**`open_external_links_in_new_tab`**: when set to `true`, this makes external links open in new tabs. Set to `false` to open all links in the current tab.

**`embed_tweets`**: when set to `true`, tweet URLs on their own lines will be replaced with a Twitter embed. Default value is `false`.

### Automatic bi-directional links

Notice in the "Notes mentioning this note" section that there is another note linking to this note. This is a bi-directional link, and those are automatically created when you create links to other notes.

### Link previews

If you're on a device with mouse support, try hovering your mouse on internal links to preview the notes: [[a note about cats]].

### Images and other Markdown goodies

Finally, because you have the full power of Markdown in this template, you can use regular Markdown syntax for various formatting options.

Lists work as expected:

- List element A
- List element B
- List element C

1. List element
2. List element
3. List element

If you'd like to quote other people, consider using quote blocks:

> Lorem ipsum dolor sit amet

And of course, images look great:

<img src="/assets/image.jpg"/>

You can also ==highlight some content== by wrapping it with `==`.

### Code syntax highlighting

You can add code blocks with full syntax color highlighting by wrapping code snippet in triple backticks and specifying the type of the code (`js`, `rb`, `sh`, etc.):

```js
// Here's a bit of JavaScript:
console.log('hello!')
```

```rb
# And now some Ruby
def foo(bar)
  "baz"
end
```

```sh
$ cat /dev/urandom | grep "the answer to life" # shell scripts look nice too
```


### Next steps

This digital garden template is free, open-source, and [available on GitHub here](https://github.com/maximevaillancourt/digital-garden-jekyll-template).

The easiest way to build your own digital garden based on this template is to read this [step-by-step guide explaining how to set this up from scratch](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll).

Go forth, have fun, and learn new something every day! ✌️
