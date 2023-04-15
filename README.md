# DLS23_MINI_PROJECT
This is the NYU deep learning course mini-project for using ResNet Architecture to detect the CIFAR-10 set

### Names:

- Chen Yang
- Yanliang Chen
- Zhisheng Hua

### Overview:

This project aims to train a ResNet model that can obtain high performance of over 90% accuracy with under 5 million trainable parameters. We explored various finetuning techniques from the aspects of architecture and training process to achieve this goal. Specifically, we tried to find a combination of parameter-related hyperparameters as well as a proper architecture that led to a good performance. In the training process, we applied techniques of learning rate decay and data augmentation to further improve the performance. For evaluation, we used our model to perform the classification task on the CIFAR-10 dataset.

### Results:

Our final model achieved a test accuracy of 92% after 50 training epochs and had 4,918,602 trainable parameters.

Train Loss|Test Loss|Train Acc.(%)|Test Acc.(%) 
--------|---------|---------|---------
0.24391|0.24993|91.54|92.04
