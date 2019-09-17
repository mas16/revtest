
# Revert Test

In this lab, we'll use `git revert` to revert a commit.

## Introduction

If you mess up or the commit history between two copies of the same repo become out of sync, you may need to revert.

## Testing the Revert

Check out this code:


```python
def function(var1):
    var1 = 'hi'
    return var1

function('bye')
```




    'hi'


