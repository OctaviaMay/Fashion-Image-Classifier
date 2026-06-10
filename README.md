# \# Fashion MNIST Image Classifier

# Comparing a Simple Feedforward Neural Network and a Convolutional Neural Network (CNN) on the Fashion MNIST dataset.

# 

# \## Problem

# Clothing images are visually similar — a T-shirt, a Shirt, and a Pullover can look nearly identical in low-resolution grayscale. The goal of this project is to build and compare two neural network architectures to correctly classify 28×28 grayscale images of clothing into 10 categories, and to understand where and why each model fails.

# 

# \## Dataset

# \- \*\*Source\*\*: `tensorflow.keras.datasets.fashion\_mnist`

# \- \*\*Image size\*\* : 28 × 28 pixels, grayscale

# \- \*\*Training samples\*\*: 60,000

# \- \*\*Test samples\*\* : 10,000

# \- \*\*Numbers of Classes\*\*: 10 class

# 

# \## Approach

# \- \*\*Model 1 — Simple Feedforward Neural Network\*\*

# A baseline dense network that flattens the image into a 784-dimensional vector before classification.

# \- \*\*Model 2 — Basic Convolutional Neural Network (CNN)\*\*

# A CNN that learns spatial feature maps through convolutional and pooling layers before classification.

# 

# \## Results

# | Metric                 |Feedforward NN      | Basic CNN            |

# |------------------------|--------------------|----------------------|

# | Test Accuracy          |\~88%                | \~91%                 |

# | Weakest class          |Shirt (55.7% recall)| Shirt (70.5% recall) |

# | Most confused pair     |Shirt ↔ T-shirt/top | Shirt ↔ T-shirt/top  |



