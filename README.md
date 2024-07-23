# markdown-guide

# Basic Syntax

# Headings

# Heading level 1

## Heading level 2

### Heading level 3

#### Heading level 4

##### Heading level 5

###### Heading level 6

# Alternate Syntax

Heading level 1a
==

Heading level 2a
--

# Heading Best Practices

Try to put a blank line before...

# Heading

...and after a heading

# Paragraphs

I really like using Markdown.

I think I'll use it to format all of my documents from now on.

## Paragraph Best Practices

Don't put tabs or spaces in front of your paragraphs.

Keep lines left-aligned like this.

# Line Breaks

This is the first line.  
And this is the second line.

## Line Break Best Practices

First line with two spaces after.  
And the next line.

First Line with the HTML tag after.<br>
And the next line.

# Emphsis

## Bold

I just love **bold text**.

I just love __bold text__

Love **is** bold

## Bold Best Practices

Love **is** bold

## Italic

Italicized text is the *cat's meow*.

Italicized text is the _cat's meow_.

A*cat*meow

## Italic Best Practices

A*cat*meow

## Bold and Italic

This text is ***really important***.

This text is ___really important___.

This text is __*really important*__.

This text is **_really important_**.

This is really***very***important text.

## Bold and Italic Best Practices

Markdown applications don't agree on how to handle underscores in the middle of a word. ***For compatibility, use asterisks*** to bold and italicize the middle of a word for emphasis.

# Blockquote

> Dorothy followed her through many of the beautiful rooms in her castle.

## Blockquote with Multiple Paragraphs

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade hei clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## Nested Blockquotes

> Dorothy followed her through many of the beautiful roos in her castle.
>
> > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

## Blockquotes with Other Elements


> #### The quarterly results look great!
>
> - Revenue was off the chart.
> - Profits were higher than ever.
>
> *Everything* is going according to **plan**.


## Blockquotes Best Practices

Try to put a blank line before...

> This is a blockquote

...and after a blockquote.

# Lists

## Ordered Lists

1. First item
2. Second item
3. Third item
4. Fourth item


1. First item
2. Second item
3. Third item
4. Fourth item


1. First item
2. Second item
3. Third item
4. Fourth item


1. First item
2. Second item
3. Third item
    1. 
        Indented item
    2. 
        Indented item
4. Fourth item

## Ordered List Best Practices

1. First item
2. Second item

# Undered Lists

- First item
- Second item
- Third item
- Fourth item

* First item
* Second item
* Third item
* Fourth item

+ First item
+ Second item
+ Third item
+ Fourth item

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

## Starting Unordered List Items With Numbers

- 1968\. A great year!
- I think 1969 was second best.

## Unordered List Practices

- First item
- Second item
- Third item
- Fourth item

## Adding Elements in Lists

### Paragraphs

* This is the first list item.
* Here's the second list item.

    I need to add another paragraph below the second list item.

* And here's the third list item.

### Blockquotes

* This is the first list item.
* Here's the second list item.
    > A blockquote would look great below the second list item.
* And here's the third list item.

### Code Blocks

1. Open the file.
2. Find the following code block on line 21:

        <html>
            <head>
                <title>
                    Test
                </title>
            </head>
        </html>

3. Update the title to match the name of your website.

### Images

1. open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![Tux,the Linux mascot](tux.png)

3. Close the file.

### Lists

1. First list item
2. Second list item
3. Third list item
    - Indented item
    - Indented item
4. Fourth list item

# Code

At the command prompt, type `nano`

## Escaping Backticks

``Use `code` in your Markdown file``.

## Code Blocks

    <html>
        <head>
        </head>
    </html>

# Horizontal Rules

Try to put a blank line before...

---

And after a horizontal rule.

# Links

My favorite search engine is [Duck Duck Go](https://duckduckgo.com).

## Adding Titles

My favorite search engine is [Duck Duck Go](https://duckduckgo.com "The best search engine for privacy").

## URLs and Email Addresses

<https://www.markdownguide.org>
<fake@example.com>

## Formatting Links

I love supporting the **[EFF](http://eff.org)**.
This is the *[Markdown Guide](https://www.markdownguide.org)*
See the section on [`code`](#code)

## Reference-style Links

### Formatting the First Part of the Link

    - [hobbit-hole][1]
    - [hobbit-hole] [1]

### Formatting the Second Part of the Link

    - [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle
    - [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"
    - [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle 'Hobbit lifestyles'
    - [1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle (Hobbit lifestyles)
    - [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"
    - [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> 'Hobbit lifestyles'
    - [1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> (Hobbit lifestyles)

### An Example Putting the Parts Together

In a hole in the ground there lived a hobbit. Not a nasty, dirty, wet hole, filled with the ends of worms and and oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to eat: it was a [hobbit-hole](https://en.wikipedia.org/wiki/Hobbit#Lifestyle "Hobbit lifestyles"), and that means comfort.

In a hole in the ground theree lived a  hobbit. Not a nasty, dirty, wet hole, filled with the ends of worms and an oozy smell, nor yet a dry, bare, sandy hole with nothing in it to sit down on or to eat: it was a [hobbit-hole][1],and that means comfort.

[1]: <https://en.wikipedia.org/wiki/Hobbit#Lifestyle> "Hobbit lifestyles"

### Link Best Practices

[link](https://www.example.com/my%20great%20page)

[a novel](https://en.wikipedia.org/wiki/The_Milagro_Beanfield_War_%28novel%29)

# Images

![The San Juan Mountains are beautiful!](san-juan-mountains.png "San Juan Mountains")

## Linking Images

[![An old rock in the desert](shiprock.png "Shiprock, New Mexico by Beau Rogers")](https://www.flickr.com/photos/beaurogers/31833779864/in/photolist-Qv3rFw-34mt9F-a9Cmfy-5Ha3Zi-9msKdv-o3hgjr-hWpUte-4WMsJ1-KUQ8N-deshUb-vssBD-6CQci6-8AFCiD-zsJWT-nNfsgB-dPDwZJ-bn9JGn-5HtSXY-6CUhAL-a4UTXB-ugPum-KUPSo-fBLNm-6CUmpy-4WMsc9-8a7D3T-83KJev-6CQ2bK-nNusHJ-a78rQH-nw3NvT-7aq2qf-8wwBso-3nNceh-ugSKP-4mh4kh-bbeeqH-a7biME-q3PtTf-brFpgb-cg38zw-bXMZc-nJPELD-f58Lmo-bXMYG-bz8AAi-bxNtNT-bXMYi-bXMY6-bXMYv)

\* Without the backslash, this would be a bullet in an unordered list.

# HTML

This **word** is bold. This <em> word </em> is italic.

## HTML Best Practices

# Extended Syntax

# Tables

| Syntax    | Description |
| --------- | ----------- |
| Header    | Title       |
| Paragraph | Text        |

## Alignment

| Syntax    | Description |   Test text |
| :-------- | :---------: | ----------: |
| Header    |    Title    | Here's this |
| Paragraph | Text &#124; |    And more |


# Fenced Code Blocks

```
{
    "firstName": "John",
    "lastName": "Smith"
    "age": 25
}
```

# Syntax Highlighting

```json
{
    "firstName": "John",
    "lastName": "Smith",
    "age": 25
}
```

# Footnotes

Here's a simple footnote, [^1] and here is a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.

    Indent paragraphs to include them in the footnote.
    
    `{ my code }`
    
    Add as many paragraphs as you like.

# Heading IDs

### My Great Heading {#custom-id}

## Linking to Heading IDs

[Heading IDs](#heading-ids)

[Heading IDs](https://www.markdownguide.org/extended-syntax#heading-ids)

# Definition Lists

First term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.

# Strikethrough

~~The world is flat.~~ We now know that the world is round.

# Task Lists

- [x] Wirte the press release
- [ ] Update the website
- [ ] Contact the media

# Emoji

## Copying and Pasting Emoji❤️

## Using Emoji Shortcodes

Gone camping! :tent: Be back soon.

This is so funny! :joy:

# Highlight

I need to highlight these ==very important words==.

I need to highlight these <mark>very important wors</mark>.

# Superscript

x^2^

x<sup>2</sup>

# Automatic URL Linking

http://www.example.com

## Disabling Automatic URL Linking

`http://www.example.com`

# Hacks

# Underline

Some of these words <ins>will be underlined</ins>

&nbsp;&nbsp;&nbsp;&nbsp;This is the first sentence of my indented paragraph.

# Center

<center>This text is centered.</center>

<p style="text-align:center">Center this text</p>

# Color

<font color="red">This text is red!</font>

<p style="color:blue">Make this text blue.</p>

# Comments

Here's a paragraph that will be visible.

[This is a comment that will be hidden.]: #

And here's another paragraph that's visible.

# Admonitions

> :warning: **worning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip** Remmber to appreciate the little things in life.

# Image Size

<img src="image.png" width="200" height="100">

## Image Captions

<figure>
    <img src="albuquerque.png" alt="Albuquerque, New Mexico">
    <figcaption>
    	A single track trail outside of Albuquerque, New Mexico
    </figcaption>
</figure>

![Albuquerque, New Mexico](albuquerque.png)
*A single track trail outside of Albuquerque, New Mexico.*

# Link Targets

<a href="https://www.markdownguide.org" target="_blank">Learn Markdown!</a>

# Symbols

 Pi (π)

 Here's a partial list of HTML entities for symbols:

 - Copyright(&copy;) --- `&copy;`
 - Registered trademark(&reg;) --- `&reg;`
 - Trademark(&trade;) --- `&trade;`
 - Euro(&euro;) --- `&euro;`
 - Left arrow(&larr;) --- `&larr;`
 - up arrow(&uarr;) --- `&uarr;`
 - Right arrow(&rarr;) --- `&rarr;`
 - Down arrow(&darr;) --- `&darr;`
 - Degree(&#176;) --- `&#176;`
 - Pi(&#960;) --- `&#960;`

# Table Formatting

## Line Breaks Within Table Cells

| Syntax    | Description                                 |
| --------- | ------------------------------------------- |
| Header    | Title                                       |
| Paragraph | First paragraph. <br><br> Second paragraph. |

## Lists Within Table Cells

| Syntax | Description                                                  |
| ------ | ------------------------------------------------------------ |
| Header | Title                                                        |
| List   | Here's a list!. <ul><li>Item one</li><li>Item two</li></ul> Second paragraph. |

## Table of Contents

#### Table of Contents

- [Underline](#underline)
- [Indent](#indent)
- [Center](#center)
- [Color](#color)

# Videos

[![Image alt text](https://img.youtube.com/vi/YOUTUBE-ID/0.jpg)](https://www.youtube.com/watch?v=YOUTUBE-ID)

[![Less Than Jake — Scott Farcas Takes It On The Chin](https://img.youtube.com/vi/PYCxct2e0zI/0.jpg)](https://www.youtube.com/watch?v=PYCxct2e0zI)
