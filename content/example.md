---
title: "Example"
date: 2018-08-20T11:12:59-04:00

menu:
  main:
    name: Example 📃
    weight: 3

---

# An h1 header

Paragraphs are separated by a blank line.

2nd paragraph. *Italic*, **bold**, and `monospace`. Itemized lists
look like:

  * this one
  * that one
  * the other one

Note that --- not considering the asterisk --- the actual text
content starts at 4-columns in.

Use 3 dashes for an em-dash. Use 2 dashes for ranges (ex., "it's all
in chapters 12--14"). Three dots ... will be converted to an ellipsis.
Unicode is supported. ☺

{{% quote author="Victor Hugo" %}}
Le soleil couchant est jaloux de la lune qui se lève
{{% /quote %}}

## An h2 header

Here's a numbered list:

 1. first item
 2. second item
 3. third item

Note again how the actual text starts at 4 columns in (4 characters
from the left side). Here's a code sample:

    # Let me re-iterate ...
    for i in 1 .. 10 { do-something(i) }

As you probably guessed, indented 4 spaces. By the way, instead of
indenting the block, you can use delimited blocks, if you like:

~~~
define foobar() {
    print "Welcome to flavor country!";
}
~~~

(which makes copying & pasting easier). You can optionally mark the
delimited block for Pandoc to syntax highlight it:

~~~python
import time
# Quick, count to ten!
for i in range(10):
    # (but not *too* quick)
    time.sleep(0.5)
    print i
~~~



### An h3 header ###

Now a nested list:

 1. First, get these ingredients:

      * carrots
      * celery
      * lentils

 2. Boil some water.

 3. Dump everything in the pot and follow
    this algorithm:

        find wooden spoon
        uncover pot
        stir
        cover pot
        balance wooden spoon precariously on pot handle
        wait 10 minutes
        goto first step (or shut off burner when done)

    Do not bump wooden spoon or it will fall.

Notice again how text always lines up on 4-space indents (including
that last line which continues item 3 above).

## Links and Footnotes

Here's a link to [a website](http://foo.bar), to a [local
doc](local-doc.html), and to a [section heading in the current
doc](#an-h2-header). Here's a footnote [^1].

[^1]: Footnote text goes here.

## Tables

Tables can look like this:

size |  material   |   color
-----|-------------|---------
9    | leather     | brown
10   | hemp canvas | natural
11   | glass       | transparent

***

size |  material   |   color
-----|-------------|---------:
9    | leather     | brown
10   | hemp canvas | natural
11   | glass       | transparent

Table: Shoes, their sizes, and what they're made of

(The above is the caption for the table.) Pandoc also supports
multi-line tables:

A horizontal rule follows.

***

and images can be specified like so:

![example image](../uploads/montreal.jpg "An exemplary image")

## That's it

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Totam commodi eos consequatur id expedita cum accusamus nam fugiat a perferendis qui numquam quia ipsam aperiam quam consectetur, aspernatur asperiores quod.