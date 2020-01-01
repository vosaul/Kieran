---
layout: post
description: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vitae felis vitae leo ornare auctor. Aenean nec magna elementum, euismod lectus et, commodo magna. Nunc eget urna in nisl tempor rutrum a in augue.
titles:
- Sources for markdown
- Heading One
tags: [markdown, source]
tipue_search_active: true
exclude_from_search: false
---
# Sources for markdown

https://www.markdownguide.org/cheat-sheet/

http://sangsoonam.github.io/2019/01/20/syntax-highlighting-in-jekyll.html

Style inspiration for the site layout:

https://www.jetbrains.com/help/pycharm/quick-start-guide.html

# Heading One
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vitae felis vitae leo ornare auctor. Aenean nec magna elementum, euismod lectus et, commodo magna. Nunc eget urna in nisl tempor rutrum a in augue.

Integer eu aliquet turpis. Sed ipsum diam, fermentum non leo et, imperdiet faucibus enim. Aenean fringilla ornare tortor porta auctor. Maecenas placerat purus vitae mi pulvinar, eu ornare purus gravida.

# Heading One
## Heading Two
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vitae felis vitae leo ornare auctor. Aenean nec magna elementum, euismod lectus et, commodo magna. Nunc eget urna in nisl tempor rutrum a in augue.

### Heading Three
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vitae felis vitae leo ornare auctor. Aenean nec magna elementum, euismod lectus et, commodo magna. Nunc eget urna in nisl tempor rutrum a in augue.

#### Heading Four
##### Heading Five
###### Heading Six

Unordered list
- This is a list 1
- This is a **list** 2, with some **bold** and some *italics*. And some ***bold and italics***
- This is a list 3

Ordered list
1. First item
2. Second item
3. Third item

Indented list
- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item

### Underline

Does it work?

---

Yes it does.

### Blockquotes

> Blockquotes are very handy
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote. 

- The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.
	> This is a blockquoteTo start syncing your workspace, just sign in with Google in the menu.
	
Blockquotes can be nested

> Dorothy followed her through many of the beautiful rooms in her castle.
>
>> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.

### Code with syntax highlighting

This is a test of `some inline code` and whether it formats `correctly`.

And now for blocks of code:

Ruby code
```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

Python code
```python
print("Hello World")

def f(x):
    """a docstring"""
    return x**2
```

### Tables

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|

Try again:

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3
What|is|up
What | is | up