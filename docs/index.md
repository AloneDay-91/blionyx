# Homepage

For full documentation visit [Blionyx.com](https://blionyx.com)

## Code annotation examples

### Codeblocks

Some `code` goes here

### Plain codeblock

A plain codeblock :
```
Some code here
def myfunction()
//some content
```

#### Code for a specific language

Some more code with the `py` at the start:

``` py
import tensorflow as tf
def whatever()
```

#### with a title

``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items)-1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### with line numbers

``` py linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items)-1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### with Highlighting lines

``` py hl_lines="2 3 4"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items)-1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

## Icons and Emoji

:smile:
:fontawesome-brands-twitter:{ .twitter }
:octicons-heart-fill-24:{ .heart }