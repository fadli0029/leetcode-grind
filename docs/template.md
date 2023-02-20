!!! Note

    Click the problem's title below to get redirected to the problem's page.

# [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/description/) 

problem description.

### Thought Process/Explanation
bla bla bla

### Solution
``` py hl_lines="4 5" linenums="1" title="Bubble Sort"
def bubble_sort(items):
    for i in range(len(items)): # (1)
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

1. testing!

Testing syntax highlighting in inline code: `#!python import torch`
