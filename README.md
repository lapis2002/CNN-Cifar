# CNN-Cifar

This project aims to predict the labels of the CIFAR-10 and CIFAR100 dataset. I used Keras Sequential to implement CNN Models. Almost all the code is in the form of Jupyter notebooks.

## Dependencies

- Jupyter
- Tensorflow
- Keras
- Matplotlib

## Cifar 10

**Accuracy = 83%**

__**CNN Model**__

![CNN Model for CIFAR10](./Pictures/model_plot_cifar10.png?raw=true "CNN - CIFAR 10")


### Metric Graphs

## CNN Model

Fine tuning DenseNet201 Model to predict Cifar100

Technique used: Image Augmentation, Model Checkpoint, Early Stopping and ReduceLROnPlateau, RMSprop

**Accuracy = 83.55%**

__**Fine tuned CNN Model**__

![CNN Model for CIFAR100](./Pictures/model_plot_cifar100.png?raw=true "CNN - CIFAR 100")

### Metric Graphs
![Metric graph for CIFAR100](./Pictures/metric_graph.png?raw=true "CNN - CIFAR 100")
