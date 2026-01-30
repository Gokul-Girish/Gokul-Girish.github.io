---
title: "Olfactory Models"
date: 2026-01-29
math: true

---
The probability of response is $P(x) = \frac{1}{1 + e^{-x}}$ as seen in `sigmoid()`

```python
def get_rate(voltage, threshold):
    # This will render in clean black and white
    return max(0, voltage - threshold)
```
