# bounded-zipf
Bounded Zipf generator ported from Go:

https://github.com/golang/go/blob/master/src/math/rand/zipf.go

```python
from bounded_zipf import Zipf

z = Zipf(1.0001, 10, 100000)
num = z.get()
```
