# lintcode
LintCode Practice &amp; Answer

### 1. Write a function that add two numbers A and B. You should not use + or any arithmetic operators.
> There is no need to read data from standard input stream. Both parameters are given in function aplusb, you job is to calculate the sum and return it.

```python
class Solution:
    """
    @param: a: An integer
    @param: b: An integer
    @return: The sum of a and b
    """
    def aplusb(self, a, b):
        # write your code here
        assert isinstance(a, int) and isinstance(b, int)
        return sum([a, b])
```
