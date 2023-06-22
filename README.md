# Quantum benchmarking
Benching code and results on Quantum Algorithm.

Designed to compare the performance of two powerful devices in one specific area.

### Participants

1. MacBook Pro 16-inch model with 10+16 M1 Pro chip, 16 GB RAM and 512 GB ROM
2. PC runs windows with i7-13700k CPU, Nvidia 3090 Ti GPU, 64 GB DDR5 RAM (6400 MHz) and 1TB ROM.

### Software version:

1. Python: 3.10.10
2. TensorFlow: 2.12.0

### Simple QAOA (TensorFlow, on CPU, with JIT) [🔗](./code/simple_QAOA.ipynb)

Average time consuming in seconds.

Variance is the real variance multiply by 100.

| Scaling factor | Time - Mac | Time - PC |
| :------------: | :--------: | :-------: |
|       2        |    2.83    |           |
|       3        |    6.07    |           |
|       4        |   12.07    |           |
|       5        |   21.25    |           |
|       6        |   36.81    |           |
|       7        |   61.42    |           |
|       8        |   87.79    |           |
|       9        |   127.05   |           |
|       10       |   246.84   |           |
|       11       |   310.25   |           |
|       12       |   436.29   |           |
|       13       |   627.16   |           |
|       14       |   805.34   |           |
|       15       |  1108.87   |           |

### Simple QAOA (TensorFlow, on CPU, without JIT) [🔗](./code/simple_QAOA.ipynb)

| Scaling factor | Time - Mac | Time - PC |
| :------------: | :--------: | :-------: |
|       2        |   33.74    |           |
|       3        |   87.11    |           |
|       4        |   180.31   |           |
|       5        |   312.70   |           |
|       6        |   504.86   |           |
|       7        |   869.24   |           |
|       8        |  1257.36   |           |
|       9        |  1731.85   |           |
|       10       |  2602.47   |           |
