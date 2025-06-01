# CTD Machine Learning Development Docs
A workspace to develop hands-on, accessible machine learning teaching materials for [Code the Dream](https://codethedream.org/). This informal space is to experiment with lesson plans, identify the most important skills, and create learning paths for Python 200. Student facing-material will ultimately be hosted separately at Code the Dream. 

## Background and motivation
Machine learning is a huge field that can cover multiple entire classes. In Python 200, we have four weeks, so we need to focus in on topics relevant to Python and data engineering. Our goal is to introduce mathematical concepts like optimization and error metrics using visualizations and intuitions, not digging into mathematics. This can be done: [Fast AI](https://www.fast.ai/) is a great model for how to do this.

## Main Workflows
After giving a general introduction to machine learning in Week 1, we will provide a hands-on introduction to ML workflows via regression before jumping into classification problems, machine vision and object detection using PyTorch. We are using PyTorch because (unlike Tensorflow and Jax) it is actively maintained across all platforms. 

- [Week 1: Hello ML](week1.md): Overview of the machine learning landscape. Hands-on with regression in scikit-learn.
- [Week 2: Classification in scikit-lern](week2.md): Classification, PCA, and pipelines using the scikit-learn library.
- [Week 3: Machine vision with PyTorch](week3.md): Classify images using torchvision. Understand metrics in vision context. 
- [Week 4: Training, transfer learning and object detection](week4.md): Train, retrain a network to identify new objects. Object detection and its metrics.