# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

##  Code Annotation Examples

### Codeblocks
    
    Some `backticks` goes here!

### Plain codeblock
``` python linenums="1" title="Bubble_sort.py" hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

### Icons and Emojis
:smile:

:fontawesome-brands-twitter:
