# Compilation of learning ressources and libraries for private and secure IA

We provide here a first non-exhaustive list of learning ressources and libraries for **private and secure IA** applications. **Differential privacy, federated learning and fully homomorphic encryption** are covered. We will be populating it in the next months with regular updates. You may follow us in Twitter for further news: https://twitter.com/AntonioRausell

================================
##  Introductory reviews 

- Data privacy in the age of personal genomics:
https://www.nature.com/articles/s41587-019-0271-3

- Secure, privacy-preserving and federated machine learning in medical imaging:
https://www.nature.com/articles/s42256-020-0186-1

## Introductory blogs to private and secure IA:

- Privacy Preserving Deep Learning – PySyft Versus TF-Encrypted
https://blog.exxactcorp.com/privacy-preserving-deep-learning-pysyft-tfencrypted/

- Machine Learning on Encrypted Data: No Longer a Fantasy
https://medium.com/intuit-engineering/machine-learning-on-encrypted-data-no-longer-a-fantasy-58e37e9f31d7

- Why you care about homomorphic encryption
https://codingossip.github.io/2020/machine-learning-with-homomorphic-encryption/

## Udacity course 
Differential Privacy, Federated Learning and Encrypted Computation (Based on PyTorch and PySyft):
https://www.udacity.com/course/secure-and-private-ai--ud185

============================================
## State-of-the-art machine learning libraries for private IA from two main programing ecosystems:

### PySyft-based ecosystem for private IA:

- **PySyft** : https://github.com/OpenMined/PySyft/
is a Python library for secure and private Deep Learning. PySyft decouples private data from model training, using Federated Learning, Differential Privacy, and Encrypted Computation (like Multi-Party Computation (MPC) and  Homomorphic Encryption (HE) within the main Deep Learning frameworks like PyTorch and TensorFlow. See video tutorials therein

- **Diffprivlib v0.3**: https://github.com/IBM/differential-privacy-library
Diffprivlib is a general-purpose library for experimenting with, investigating and developing applications in differential privacy.

- Differential Privacy + Federated Learning Explained (short video Tutorial): 
https://www.youtube.com/watch?v=MOcTGM_UteM

- Google Colab Tutorial and Notebook for the Privacy in Machine Learning video from Jordan Harrod's AI 101 series
https://colab.research.google.com/drive/11jAZ5Xb4UAhO5IMVVUjuKy2zCVgcuKLi

### TensorFlow-based ecosystem for private IA:

- **TensorFlow Privacy**: https://github.com/tensorflow/privacy
Python library that includes implementations of TensorFlow optimizers for training machine learning models with differential privacy. The library comes with tutorials and analysis tools for computing the privacy guarantees provided.

- **TensorFlow Federated** (Machine Learning on Decentralized Data):https://www.tensorflow.org/federated
Tutorials on federated learning usingTensorFlow : https://www.tensorflow.org/federated/tutorials/federated_learning_for_image_classification

- **TF Encrypted**: https://github.com/tf-encrypted/tf-encrypted
is a framework for encrypted machine learning in TensorFlow. It looks and feels like TensorFlow, taking advantage of the ease-of-use of the Keras API while enabling training and prediction over encrypted data via secure multi-party computation and homomorphic encryption. TF Encrypted aims to make privacy-preserving machine learning readily available, without requiring expertise in cryptography, distributed systems, or high performance computing.

============================================
## About homomorphic encryption: Introduction and libraries

- **Homomorphic Encryption Standardization**
https://homomorphicencryption.org/

- The **IBM Fully Homomorphic Encryption (FHE) Toolkit** for Linux
https://github.com/IBM/fhe-toolkit-linux

- **HElib open-source library** 
https://github.com/homenc/HElib

============================================
## OpenMined community

- **OpenMined**, an open-source community whose goal is to make the world more privacy-preserving by lowering the barrier-to-entry to private AI technologies: https://www.openmined.org/

- **OpenMined youtube channel**:
https://www.youtube.com/c/OpenMinedOrg/videos

============================================
## Additional interesting papers

Private federated learning on vertically partitioned datavia entity resolution and additively homomorphic encryption
https://arxiv.org/pdf/1711.10677.pdf
