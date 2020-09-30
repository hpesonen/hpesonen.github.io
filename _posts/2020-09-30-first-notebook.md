---
title: First notebook
date:  2020-09-30 15:55
categories: elfi
---

```python
import elfi
```


```python
from elfi.examples import ma2
```


```python
m = ma2.get_model()
rej = elfi.Rejection(m['d'], batch_size=10)
rejsample = rej.sample(1000, bar=False)
```


```python

```
