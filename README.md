# Quantum benchmarking
Benching code and results on Quantum Algorithm.

Designed to compare the performance of two powerful devices in one specific area.

### Participants

1. MacBook Pro 16-inch model with 10+16 M1 Pro chip, 16 GB Ram and 512 GB ROM
2. PC runs windows with i7-13700k CPU, Nvidia 3090 Ti GPU, 64 GB DDR5 RAM (6400 MHz) and 1TB ROM.

### Software version:

1. Python
2. TensorFlow: 

### Simple QAOA (TensorFlow, on CPU, with JIT)

Average time consuming in seconds.

Variance is the real variance multiply by 100.

| Scaling factor | Time - Mac | Var - Mac | Time - PC | Var - PC |
| :------------: | :--------: | :-------: | :-------: | :------: |
|       2        |   2.8382   |  2.7189   |           |          |
|       3        |   6.0729   |   6.619   |           |          |
|       4        |  12.0794   | 12.04465  |           |          |
|       5        |   21.259   |   13.02   |           |          |
|       6        |  36.8139   |  46.618   |           |          |
|       7        |  61.4226   |  13.3817  |           |          |
|       8        |  87.7903   |  666.091  |           |          |
|       9        |  127.0566  | 378.7215  |           |          |

### Simple QAOA (TensorFlow, on CPU, without JIT)

| Scaling factor | Time - Mac | Var - Mac | Time - PC | Var - PC |
| :------------: | :--------: | :-------: | :-------: | :------: |
|       2        |  33.7466   |  94.1256  |           |          |
|       3        |  87.1125   | 103.3088  |           |          |
|       4        |  180.3128  | 726.0712  |           |          |
|       5        |  312.7019  | 2592.7605 |           |          |
|       6        |  504.8649  |   2.757   |           |          |

