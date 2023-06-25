# Quantum benchmarking
Benching code and results on Quantum Algorithm.

Designed to compare the performance of two powerful devices in one specific area.

### Participants

1. MacBook Pro 16-inch model with 10+16 M1 Pro chip, 16 GB RAM and 512 GB ROM
2. PC runs windows with i7-13700k CPU, Nvidia 3090 Ti GPU, 64 GB DDR5 RAM (6400 MHz) and 1TB ROM.

### Software version:

1. Python: 3.10.10
2. TensorFlow: 2.12.0

### Simple QAOA (TensorFlow, on CPU, without JIT) [🔗](./code/simple_QAOA.ipynb)

Average time consuming in seconds.

Variance is the real variance multiply by 100.

| Scaling factor | Time - Mac | Time - PC |
| :------------: | :--------: | :-------: |
|       2        |   33.74    |   44.64   |
|       3        |   87.11    |  111.27   |
|       4        |   180.31   |  229.55   |
|       5        |   312.70   |  402.61   |
|       6        |   504.86   |  657.84   |
|       7        |   869.24   |  1004.45  |
|       8        |  1257.36   |  1536.35  |
|       9        |  1731.85   |  2456.36  |
|       10       |  2602.47   |           |

### Simple QAOA (TensorFlow, on CPU, with JIT) [🔗](./code/simple_QAOA.ipynb)

| Scaling factor | Time - Mac | Time - PC |
| :------------: | :--------: | :-------: |
|       2        |    2.83    |   3.43    |
|       3        |    6.07    |   7.09    |
|       4        |   12.07    |   14.20   |
|       5        |   21.25    |   25.17   |
|       6        |   36.81    |   41.99   |
|       7        |   61.42    |   65.57   |
|       8        |   87.79    |   96.06   |
|       9        |   127.05   |  136.11   |
|       10       |   246.84   |  272.54   |
|       11       |   284.70   |  270.63   |
|       12       |   436.29   |  453.55   |
|       13       |   627.16   |  947.65   |
|       14       |   805.34   |           |
|       15       |  1108.87   |           |
