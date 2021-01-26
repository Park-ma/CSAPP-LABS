
1.  bitXor - x^y using only ~ and & .

用 `~` 和 `&` 实现 `^`：
通过如下图所示：
![s ](../image/Venn.svg)
`x^y = x|y-x&y`  已知  `a-b=a&(~b)` 所以可得

`x^y = (x|y)&~(x&y)`

又通过德摩根律，可得

`x^y=~(~x&~y)&~(x&y)`


