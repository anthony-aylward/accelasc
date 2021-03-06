# accelasc

Implementation of the `accel_asc` algorithm for integer partitions. See
[this stackoverflow post](https://stackoverflow.com/questions/10035752/elegant-python-code-for-integer-partitioning)
and [Jerome Kelleher's website](http://jeromekelleher.net/category/combinatorics.html).
See also the paper by Kelleher and O'Sullivan: [Generating All Partitions: A Comparison Of Two Encodings](https://arxiv.org/abs/0909.2331).

## Installation
```sh
pip3 install accelasc
```
or
```sh
pip3 install --user accelasc
```

## Usage

```python3
from accelasc import accel_asc
tuple(accel_asc(5))
```
```python3
([1, 1, 1, 1, 1], [1, 1, 1, 2], [1, 1, 3], [1, 2, 2], [1, 4], [2, 3], [5])
```
