# Model Compare

Model compare based on MNIST, FASHION MNIST and CIFAR10 dataset.

## MINIST

| Network  Type | Activation Func | Layer | Filter    | Kernels   | Epoch | Val Acc |
| ------------- | --------------- | ----- | --------- | --------- | ----- | ------- |
| cnn           | arctan          | 3     | [5,5]     | [3,3]     | 300   | 98.26   |
| cnn           | arctan          | 4     | [5,5,5]   | [3,5,3]   | 300   | 98.38   |
| cnn           | arctan          | 5     | [3,5,5,3] | [3,3,3,3] | 300   | 98.13   |
| cnn           | sigmoid         | 3     | [5,5]     | [3,3]     | 300   | 97.20   |
| cnn           | sigmoid         | 4     | [5,5,5]   | [3,5,3]   | 300   | 98.09   |
| cnn           | sigmoid         | 5     | [3,5,5,3] | [3,3,3,3] | 300   | 97.80   |
| cnn           | tanh            | 3     | [5,5]     | [3,3]     | 300   | 98.01   |
| cnn           | tanh            | 4     | [5,5,5]   | [3,5,3]   | 300   | 98.74   |
| cnn           | tanh            | 5     | [3,5,5,3] | [3,3,3,3] | 300   | 98.18   |
| fnn           | arctan          | 5     | 70        | -         | 300   | 97.47   |
| fnn           | sigmoid         | 5     | 70        | -         | 300   | 95.48   |
| fnn           | tanh            | 5     | 70        | -         | 300   | 97.37   |

## Fashion MNIST

| Network  Type | Activation Func | Layer | Filter    | Kernels   | Epoch | Val Acc |
| ------------- | --------------- | ----- | --------- | --------- | ----- | ------- |
| cnn           | arctan          | 3     | [5,5]     | [3,3]     | 300   | 88.63   |
| cnn           | arctan          | 4     | [5,5,5]   | [3,5,3]   | 300   | 88.36   |
| cnn           | arctan          | 5     | [3,5,5,3] | [3,3,3,3] | 300   | 88.40   |
| cnn           | sigmoid         | 3     | [5,5]     | [3,3]     | 300   | 86.85   |
| cnn           | sigmoid         | 4     | [5,5,5]   | [3,5,3]   | 300   | 87.90   |
| cnn           | sigmoid         | 5     | [3,5,5,3] | [3,3,3,3] | 300   | 85.73   |
| cnn           | tanh            | 3     | [5,5]     | [3,3]     | 300   | 88.96   |
| cnn           | tanh            | 4     | [5,5,5]   | [3,5,3]   | 300   | 88.81   |
| cnn           | tanh            | 5     | [3,5,5,3] | [3,3,3,3] | 300   | 87.65   |
| fnn           | arctan          | 5     | 70        | -         | 300   | 87.77   |
| fnn           | sigmoid         | 5     | 70        | -         | 300   | 87.18   |
| fnn           | tanh            | 5     | 70        | -         | 300   | 88.13   |

## Cifar10

| Network  Type | Activation Func | Layer | Filter    | Kernels   | Epoch | Val Acc |
| ------------- | --------------- | ----- | --------- | --------- | ----- | ------- |
| cnn           | arctan          | 3     | [5,5]     | [3,3]     | 300   | 49.20   |
| cnn           | arctan          | 4     | [5,5,5]   | [3,5,3]   | 300   | 49.07   |
| cnn           | arctan          | 5     | [3,5,5,3] | [3,3,3,3] | 300   | 43.91   |
| cnn           | sigmoid         | 3     | [5,5]     | [3,3]     | 300   | 48.73   |
| cnn           | sigmoid         | 4     | [5,5,5]   | [3,5,3]   | 300   | 46.66   |
| cnn           | sigmoid         | 5     | [3,5,5,3] | [3,3,3,3] | 300   | 40.00   |
| cnn           | tanh            | 3     | [5,5]     | [3,3]     | 300   | 49.21   |
| cnn           | tanh            | 4     | [5,5,5]   | [3,5,3]   | 300   | 49.01   |
| cnn           | tanh            | 5     | [3,5,5,3] | [3,3,3,3] | 300   | 45.26   |
| fnn           | arctan          | 5     | 70        | -         | 300   | 49.40   |
| fnn           | sigmoid         | 5     | 70        | -         | 300   | 42.08   |
| fnn           | tanh            | 5     | 70        | -         | 300   | 48.41   |
