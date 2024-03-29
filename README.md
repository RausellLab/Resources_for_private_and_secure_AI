# Compilation of learning ressources and libraries for private and secure AI

We provide here a first non-exhaustive list of learning ressources and libraries for **private and secure IA** applications. **Differential privacy, federated learning and fully homomorphic encryption** are covered. We will be populating it in the next months with regular updates. You may follow us in Twitter for further news: https://twitter.com/AntonioRausell

================================
##  Introductory reviews 

- Secure, privacy-preserving and federated machine learning in medical imaging (2020):
https://www.nature.com/articles/s42256-020-0186-1

- Data privacy in the age of personal genomics (2019):
https://www.nature.com/articles/s41587-019-0271-3

- Machine learning and genomics: precision medicine vs.  patient privacy (2018):
https://arxiv.org/pdf/1802.10568.pdf

## Introductory blogs to private and secure AI:

- Privacy Preserving Deep Learning – PySyft Versus TF-Encrypted
https://blog.exxactcorp.com/privacy-preserving-deep-learning-pysyft-tfencrypted/

- Machine Learning on Encrypted Data: No Longer a Fantasy
https://medium.com/intuit-engineering/machine-learning-on-encrypted-data-no-longer-a-fantasy-58e37e9f31d7

- Why you care about homomorphic encryption
https://codingossip.github.io/2020/machine-learning-with-homomorphic-encryption/

- A friendly, non-technical introduction to differential privacy
https://desfontain.es/privacy/friendly-intro-to-differential-privacy.html

## Itroductory videos to private and secure AI:

- Privacy Preserving AI (Andrew Trask) | MIT Deep Learning Series
https://www.youtube.com/watch?v=4zrU54VIK6k&t=1582s


## Udacity course 
Differential Privacy, Federated Learning and Encrypted Computation (Based on PyTorch and PySyft):
https://www.udacity.com/course/secure-and-private-ai--ud185

## Privacy Preserving Machine Learning - Course by Aurélien Bellet
Slides and Jupyter notebooks (in Python) from the course taught by Aurélien Bellet, Master 2 Data Science, University of Lille
http://researchers.lille.inria.fr/abellet/teaching/private_machine_learning_course.html

============================================
## State-of-the-art machine learning libraries for private AI from two main programing ecosystems:

### PySyft-based ecosystem for private AI:

- **PySyft** : https://github.com/OpenMined/PySyft/
is a Python library for secure and private Deep Learning. PySyft decouples private data from model training, using Federated Learning, Differential Privacy, and Encrypted Computation (like Multi-Party Computation (MPC) and  Homomorphic Encryption (HE) within the main Deep Learning frameworks like PyTorch and TensorFlow. See video tutorials therein

- **Diffprivlib v0.3**: https://github.com/IBM/differential-privacy-library
Diffprivlib is a general-purpose library for experimenting with, investigating and developing applications in differential privacy.

- Differential Privacy + Federated Learning Explained (short video Tutorial): 
https://www.youtube.com/watch?v=MOcTGM_UteM

- Google Colab Tutorial and Notebook for the Privacy in Machine Learning video from Jordan Harrod's AI 101 series
https://colab.research.google.com/drive/11jAZ5Xb4UAhO5IMVVUjuKy2zCVgcuKLi

### TensorFlow-based ecosystem for private AI:

- **TensorFlow Privacy**: https://github.com/tensorflow/privacy
Python library that includes implementations of TensorFlow optimizers for training machine learning models with differential privacy. The library comes with tutorials and analysis tools for computing the privacy guarantees provided.

- **TensorFlow Federated** (Machine Learning on Decentralized Data):https://www.tensorflow.org/federated

-- Tutorials on federated learning using TensorFlow : https://www.tensorflow.org/federated/tutorials/federated_learning_for_image_classification

-- Federated Learning Workshop using TensorFlow Federated: https://events.withgoogle.com/demostutorials-workshop-on-federated-learning-and-analytics-2020/

-- YouTube Live recording: https://www.youtube.com/watch?v=fNrVh2RWVTc&feature=youtu.be

-- Colab notebooks available at:https://events.withgoogle.com/demostutorials-workshop-on-federated-learning-and-analytics-2020/

- **TF Encrypted**: https://github.com/tf-encrypted/tf-encrypted
is a framework for encrypted machine learning in TensorFlow. It looks and feels like TensorFlow, taking advantage of the ease-of-use of the Keras API while enabling training and prediction over encrypted data via secure multi-party computation and homomorphic encryption. TF Encrypted aims to make privacy-preserving machine learning readily available, without requiring expertise in cryptography, distributed systems, or high performance computing.

### Flower ecosystem for private AI:

- **Flower**: https://github.com/adap/flower
friendly Python library for federated learning, analytics and evaluation. It supports both Pytorch and Tensorflow.

-- Tutorials on federated learning using Flower: https://flower.dev/docs/ 

-- Recording of Flower Summit 2021: https://www.youtube.com/channel/UC-6quleTjPNZdsH6uRtkMkQ

============================================
## About Differential Privacy: Introduction and libraries

- **Opacus**: https://github.com/pytorch/opacus
is a Python library that enables to train neural networks models with differential privacy. It only support Pytorch models.

- **PyDP**: https://github.com/OpenMined/PyDP
is a Python library featuring differentially private algorithms to produce aggregate statistics over private information.

- **OpenDP**: https://github.com/opendp/opendp
is a library implemented in Rust, with biding for easy use in Python. It contains a set of statistical algorithms for building privacy-preserving applications.

============================================
## About homomorphic encryption: Introduction and libraries

- **Homomorphic Encryption Standardization**
https://homomorphicencryption.org/

- The **IBM Fully Homomorphic Encryption (FHE) Toolkit** for Linux
https://github.com/IBM/fhe-toolkit-linux

- **HElib open-source library** 
https://github.com/homenc/HElib

============================================
## Reference sites and communities

- **OpenMined**, an open-source community whose goal is to make the world more privacy-preserving by lowering the barrier-to-entry to private AI technologies: https://www.openmined.org/

- **OpenMined youtube channel**:
https://www.youtube.com/c/OpenMinedOrg/videos

- **DifferentialPrivacy.org** https://differentialprivacy.org/about/
hub for the differential privacy research community and to promote the work in this area

- **Ressources highlighted at DifferentialPrivacy.org** : Books, courses, videos, workshops and code libraries:
https://differentialprivacy.org/resources/ -

- **Federated Learning One World (FLOW) Seminar** : 
https://sites.google.com/view/one-world-seminar-series-flow/home?authuser=0
FLOW seminar provides a global online forum for the dissemination of the latest scientific research results in all aspects of federated learning.

- **FLOW's talks** archive (with videos):
https://sites.google.com/view/one-world-seminar-series-flow/archive?authuser=0

============================================
## A deeper dive into differential privacy:

- **Books and publications:**

Differential Privacy: A Primer for a Non-technical Audience (2018)
https://salil.seas.harvard.edu/files/salil/files/differential_privacy_primer_nontechnical_audience.pdf

The Algorithmic Foundations of Differential Privacy. 2014. C. Dwork and A. Roth.:
https://www.cis.upenn.edu/~aaroth/privacybook.html

The Complexity of Differential Privacy. 2017. S. Vadhan.
https://salil.seas.harvard.edu/files/salil/files/manuscript_2017.pdf

The 7th BIU Winter School on Cryptography. Differential Privacy: From Theory to Practice: February 2017: 
http://cyber.biu.ac.il/event/the-7th-biu-winter-school/

- **Courses:**
Applied Privacy for Data Science
https://github.com/opendp/cs208/blob/main/spring2022/index.md



============================================
## Additional reviews and interesting papers

Advances and Open Problems in Federated Learning, 2019. Kairouz et al.
https://arxiv.org/pdf/1912.04977.pdf

Private federated learning on vertically partitioned data via entity resolution and additively homomorphic encryption
https://arxiv.org/pdf/1711.10677.pdf

Group privacy for personalized federated learning, 2022. Galli et al.
https://arxiv.org/pdf/2206.03396.pdf


