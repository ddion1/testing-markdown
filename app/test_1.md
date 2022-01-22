# header 1

test 1

## header 2

test 2

### header 3

test 3

url test : [google](www.google.ca)

- un
- deux
- trois

This sentence introduces my wiki page.

- `command`

Sometimes you want to :monkey: around a bit and add some :star2: to your :speech_balloon:. Well we have a gift for you:

:zap: You can use emoji anywhere GitLab Flavored Markdown is supported. :v:

You can use it to point out a :bug: or warn about :speak_no_evil: patches. And if someone improves your really :snail: code, send them some :birthday:. People :heart: you for that.

If you're new to this, don't be :fearful:. You can join the emoji :family:. Just look up one of the supported codes.

Consult the [Emoji Cheat Sheet](https://www.emojicopy.com) for a list of all supported emoji codes. :thumbsup:

- [+ addition 1 +]
- [+ addition 2 +]
- {- deletion 3 -}
- {- deletion 4 -}

[Link to Documentation](documentation.md)

> Blockquotes help you emulate reply text.
> This line is part of the same quote.

Quote break.

> This very long line is still quoted properly when it wraps. Keep writing to make sure this line is long enough to actually wrap for everyone. You can also *add* **Markdown** into a blockquote.

>>>
...If you paste a message from somewhere else

...that spans multiple lines,

...you can quote that without having to manually prepend `>` to every line!
>>>

# Testing Header Anchor

```python
def function():
    #indenting works just fine in the fenced code block
    s = "Python code"
    print s
```

~~~python
def function():
    #indenting works just fine in the fenced code block
    s = "Python code"
    print s
~~~

# Testing Header Anchor1

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with double **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
    
    
    
A footnote reference tag looks like this: [^1]

This reference tag is a mix of letters and numbers. [^footnote-42]

[^1]: This text is inside a footnote.

[^footnote-42]: This text is another footnote.


Three or more hyphens,

---

asterisks,

***

or underscores

___


Inline-style (hover to see title text):

![alt text](../img/markdown_logo.png "Title Text")

Reference-style (hover to see title text):

# ![alt text1][logo]

[logo]: ../img/markdown_logo.png "Title Text"


<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. HTML <em>tags</em> do <b>work</b>, in most cases.</dd>
</dl>

<p>
<details>
<summary>Click this to collapse/fold.</summary>

These details <em>remain</em> <strong>hidden</strong> until expanded.

<pre><code>

1 un
2 deux
3 trois
4 quatre

</code></pre>

</details>
</p>


<details>
<summary>Click this to collapse/fold.</summary>

These details _remain_ **hidden** until expanded.

```
PASTE LOGS HERE
```

</details>


Here's a line for us to start with.

This longer line is separated from the one above by two newlines, so it is a *separate paragraph*.

This line is also a separate paragraph, but...
These lines are only separated by single newlines,
so they *do not break* and just follow the previous lines
in the *same paragraph*.

- This line links to [a section on a different Markdown page, using a "#" and the header ID](documentation.md#overview)

- This line links to [a different section on the same page, using a "#" and the header ID](#testing-header-anchor1)
- - This line links to [a different section on the same page, using a "#" and the header ID](#header-ids-and-links)
- 


- This line shows an [inline-style link](https://www.google.com)
- This line shows a [link to a repository file in the same directory](index.md)
- This line shows a [relative link to a readme one directory higher](../index.md)
- This line shows a [link that also has title text](https://www.google.com "This link takes you to Google!")

Using header ID anchors:

- This line links to [a section on a different Markdown page, using a "#" and the header ID](index.md#overview)
- This line links to [a different section on the same page, using a "#" and the header ID](#header-ids-and-links)

Using references:

- This line shows a [reference-style link, see below][Arbitrary case-insensitive reference text]
- You can [use numbers for reference-style link definitions, see below][1]
- Or leave it empty and use the [link text itself][], see below.

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org/en-US/
[1]: https://slashdot.org
[link text itself]: https://www.reddit.com
