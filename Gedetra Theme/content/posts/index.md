---
title: "Enhanced Markdown Example"
date: 2024-04-09
math: true
draft: true
tags: ["Great", "Markdown", "Example"]
---


_I am a rather elderly man._ The nature of my avocations for the last thirty years has brought me into more than ordinary contact with what would seem an interesting and somewhat singular set of men, of whom as yet nothing that I know of has ever been written:—I mean the law-copyists or scriveners. I have known very many of them, professionally and privately, and if I pleased, could relate divers histories, at which good-natured gentlemen might smile, and sentimental souls might weep. But I waive the biographies of all other scriveners for a few passages in the life of Bartleby, who was a scrivener of the strangest I ever saw or heard of. While of other law-copyists I might write the complete life, of Bartleby nothing of that sort can be done. I believe that no materials exist for a full and satisfactory biography of this man. It is an irreparable loss to literature. Bartleby was one of those beings of whom nothing is ascertainable, except from the original sources, and in his case those are very small. What my own astonished eyes saw of Bartleby, that is all I know of him, except, indeed, one vague report which will appear in the sequel.

---
__Advertisement :)__

- __[pica](https://nodeca.github.io/pica/demo/)__ - high quality and fast image
  resize in browser.
- __[babelfish](https://github.com/nodeca/babelfish/)__ - developer friendly
  i18n with plurals support and easy syntax.

You will like those projects!

---

When $a \ne 0$, there are two solutions to $(ax^2 + bx + c = 0)$ and they are
$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$

# h1 Heading 8-)
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


## Horizontal Rules

___

---

***


## Typographic replacements

Enable typographer option to see result.

(c) (C) (r) (R) (tm) (TM) (p) (P) +-

test.. test... test..... test?..... test!....

!!!!!! ???? ,,  -- ---

"Smartypants, double quotes" and 'single quotes'


## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~


## Blockquotes


> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.


## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar


## Code

Inline `code`

==Indented code==

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Tables


| Option | Description |
| ------| -----------|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |


## Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)

## Regular Blockquote
> Ere introducing the scrivener, as [he first appeared to me](http://nodeca.github.io/pica/demo/ "title text!"), it is fit I make some mention of myself, my employees, my business, my chambers, and general surroundings; because some such description is indispensable to an adequate understanding of the chief character about to be presented.
>
>\- Doug Engelbart, 1961

## Callouts
{{< callout info "Information" >}}
This is an important piece of information that you should know about.
{{< /callout >}}

{{< callout warning "Warning" >}}
Be careful about this particular aspect.
{{< /callout >}}

{{< callout note "Note" >}}
Just a quick note about something.
{{< /callout >}}

## Images with Captions

![Alt text](ima.jpg)

{{< figure
    src="ima.jpg"
    alt="Description of image"
    source="Author last name, First name. Image Title. Year. Format. Institution Name, City."
>}}

## Regular Markdown Still Works
- List item 1
- List item 2
  - Nested item
  - Another nested item
    1. Numbered sub-item
    2. Another numbered sub-item


Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Nulla quis diam. In dapibus augue non sapien. Pellentesque sapien. Aenean fermentum risus id tortor. Aliquam ante. Etiam posuere lacus quis dolor. Maecenas ipsum velit, consectetuer eu lobortis ut, dictum at dui. Etiam neque. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aliquam ante. Etiam neque. Integer imperdiet lectus quis justo. Nullam justo enim, consectetuer nec, ullamcorper ac, vestibulum in, elit.

Maecenas libero. Praesent vitae arcu tempor neque lacinia pretium. Nullam sit amet magna in magna gravida vehicula. Morbi scelerisque luctus velit. Nulla non lectus sed nisl molestie malesuada. Nunc dapibus tortor vel mi dapibus sollicitudin. Curabitur bibendum justo non orci. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Integer imperdiet lectus quis justo. Nam sed tellus id magna elementum tincidunt. Etiam dictum tincidunt diam. In dapibus augue non sapien.

![ImageBank](https://www.finance-watch.org/wp-content/uploads/2023/11/AdobeStock_201553243-scaled.jpeg)

Suspendisse sagittis ultrices augue. Nullam lectus justo, vulputate eget mollis sed, tempor sed magna. Phasellus rhoncus. Duis sapien nunc, commodo et, interdum suscipit, sollicitudin et, dolor. Pellentesque sapien. Fusce wisi. Aenean fermentum risus id tortor. Etiam quis quam. In enim a arcu imperdiet malesuada. Nulla est. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos hymenaeos. Duis pulvinar. Vestibulum fermentum tortor id mi. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos hymenaeos. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum. Phasellus enim erat, vestibulum vel, aliquam a, posuere eu, velit.

Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos hymenaeos. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Etiam egestas wisi a erat. In convallis. Aliquam in lorem sit amet leo accumsan lacinia. Nulla accumsan, elit sit amet varius semper, nulla mauris mollis quam, tempor suscipit diam nulla vel leo. Maecenas aliquet accumsan leo. Nunc dapibus tortor vel mi dapibus sollicitudin. Aliquam ante. Maecenas aliquet accumsan leo. Nullam at arcu a est sollicitudin euismod. Pellentesque ipsum. Nullam feugiat, turpis at pulvinar vulputate, erat libero tristique tellus, nec bibendum odio risus sit amet ante. Duis ante orci, molestie vitae vehicula venenatis, tincidunt ac pede. Etiam commodo dui eget wisi.
