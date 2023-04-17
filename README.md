# EMNIST-CNN-Kernel-training-test
Training a CNN with the EMNIST Balanced dataset with different kernel matrix sizes and evaluating accuracy

In this python notebook, the model layers are printed after training to get a better look on the inner workings of a Convolutional Neural Network:
![image](https://user-images.githubusercontent.com/83359345/193330394-b62ab85a-806a-48e2-9817-e5b4240c0cbd.png)

Kernel sizes tested:
- 8
- 16
- 24
- 64 + 128


Also a simple dense layer instead of the convolutional layer was tested, which resulted in overfitting:
![image](https://user-images.githubusercontent.com/83359345/193330485-97f70625-3ea7-4538-a5bb-418436242b17.png)


Same test was done for a few Chinese characters, just to assess how it would work with something different:
![image](https://user-images.githubusercontent.com/83359345/193330941-4519807f-c390-4fbe-b324-20eceba0d831.png)
