# Learning-Priors-for-Adversarial-Autoencoders

Experimental results for learning priors for adversarial autoencoders

## Content
- [Quantitative Analysis](#quantitative-analysis)
  - [Inception Scores Evaluation](#inception-scores-evaluation-on-cifar10)
- [Image Generation](#image-generation)
- [Learning Disentangled Representations (Supervised)](#learning-disentangled-representations-supervised)
- [Learning Disentangled Representations (Unsupervised)](#learning-disentangled-representations-unsupervised)
- [Latent Space Visualization](#latent-space-visualization)

## Quantitative Analysis
### Inception Scores Evaluation on CIFAR10
|   | Proposed | Baseline |
| ------------- | ------------- | ------------- |
| Image generation  | 7.31  | 6.37 |
| Supervised  | 6.52 | 6.2 |
| Unsupervised  | 6.02  | 5.73 |

## Image Generation

### MNIST
| Proposed | Baseline |
| ------------- | ------------- |
|![mnist_ours_generation](./figure/mnist/ours_generation.png)| ![mnist_maae_generation](./figure/mnist/maae_generation.png) |

### CIFAR-10
| Proposed | Baseline |
| ------------- | ------------- |
|![cifar10_ours_generation](./figure/cifar10/ours_generation.png)| ![cifar10_maae_generation](./figure/cifar10/maae_generation.png) |

## Learning Disentangled Representations (Supervised)

### MNIST
| Proposed | Baseline |
| ------------- | ------------- |
|![mnist_ours_supervised](./figure/mnist/ours_supervised.png)| ![mnist_maae_supervised](./figure/mnist/maae_supervised.png) |

### SVHN
| Proposed | Baseline |
| ------------- | ------------- |
|![svhn_ours_supervised](./figure/svhn/ours_supervised.png)| ![mnist_maae_supervised](./figure/svhn/maae_supervised.png) |

### CIFAR-10
| Proposed | Baseline |
| ------------- | ------------- |
|![cifar10_ours_supervised](./figure/cifar10/ours_supervised.png)| ![cifar10_maae_supervised](./figure/cifar10/maae_supervised.png) |


## Learning Disentangled Representations (Unsupervised)

### MNIST
| Proposed | Baseline |
| ------------- | ------------- |
|![mnist_ours_unsupervised](./figure/mnist/ours_unsupervised.png)| ![mnist_maae_unsupervised](./figure/mnist/maae_unsupervised.png) |

### SVHN
| Proposed | Baseline |
| ------------- | ------------- |
|![svhn_ours_unsupervised](./figure/svhn/ours_unsupervised.png)| ![mnist_maae_unsupervised](./figure/svhn/maae_unsupervised.png) |

### CIFAR-10
| Proposed | Baseline |
| ------------- | ------------- |
|![cifar10_ours_unsupervised](./figure/cifar10/ours_unsupervised.png)| ![cifar10_maae_unsupervised](./figure/cifar10/maae_unsupervised.png) |

## Latent Space Visualization

### MNIST - Supervised Settings
| Proposed - Encoder | Proposed - Learned Prior | Baseline - Fixed Prior |
| ------------------ | ------------------------ | ---------------------- |
| ![](./figure/latent_space/mnist_ours_supervised/mnist_ours_supervised_enc.png) | ![](./figure/latent_space/mnist_ours_supervised/mnist_ours_supervised_gen.png) | ![](./figure/latent_space/mnist_maae_supervised/mnist_maae_supervised_enc.png) |

### CIFAR-10 - Supervised Settings
| Proposed - Encoder | Proposed - Learned Prior | Baseline - Fixed Prior |
| ------------------ | ------------------------ | ---------------------- |
| ![](./figure/latent_space/cifar10_ours_supervised/cifar10_ours_supervised_enc.png) | ![](./figure/latent_space/cifar10_ours_supervised/cifar10_ours_supervised_gen.png) | ![](./figure/latent_space/cifar10_maae_supervised/cifar10_maae_supervised_enc.png) |

### MNIST - Unsupervised Settings
| Proposed - Encoder | Proposed - Learned Prior | Baseline - Fixed Prior |
| ------------------ | ------------------------ | ---------------------- |
| ![](./figure/latent_space/mnist_ours_unsupervised/mnist_ours_unsupervised_enc.png) | ![](./figure/latent_space/mnist_ours_unsupervised/mnist_ours_unsupervised_gen.png) | ![](./figure/latent_space/mnist_maae_unsupervised/mnist_maae_unsupervised_enc.png) |

### CIFAR-10 - Unsupervised Settings
| Proposed - Encoder | Proposed - Learned Prior | Baseline - Fixed Prior |
| ------------------ | ------------------------ | ---------------------- |
| ![](./figure/latent_space/cifar10_ours_unsupervised/cifar10_ours_unsupervised_enc.png) | ![](./figure/latent_space/cifar10_ours_unsupervised/cifar10_ours_unsupervised_gen.png) | ![](./figure/latent_space/cifar10_maae_unsuperivsed/cifar10_maae_unsupervised_enc.png) |
