

```
def d_t(n):
    k = n[0]*n[1]
    e = n[1] - 1
    return (k,e)
```





```
def f_d(f_ns):
    d_ns = list(map(lambda f_n: d_t(f_n),f_ns))
    return list(filter(lambda d_n: d_n[0] != 0, d_ns))
```







```
function test() {
  console.log("notice the blank line before this function?");
}
```
mnelson:myproject mnelson$ git branch
  master
* my-new-branch


