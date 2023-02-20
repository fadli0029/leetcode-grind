!!! Note

    Click the problem's title below to get redirected to the problem's page.

# [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/description/) 

problem description.

### Thought Process/Explanation
bla bla bla

### Solution
``` python linenums="1" title="solutions/arrays_and_hashing/contains_duplicate.py"
def containsDuplicate(self, nums: List[int]) -> bool:
    data = set()
    for num in nums:
        if num in data:
            return True
        data.add(num)
    return False
```

``` cpp linenums="1" title="solutions/arrays_and_hashing/contains_duplicate.cpp"
def containsDuplicate(self, nums: List[int]) -> bool:
    data = set()
    for num in nums:
        if num in data:
            return True
        data.add(num)
    return False
```

``` c linenums="1" title="solutions/arrays_and_hashing/contains_duplicate.c"
def containsDuplicate(self, nums: List[int]) -> bool:
    data = set()
    for num in nums:
        if num in data:
            return True
        data.add(num)
    return False
```
