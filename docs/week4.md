# Week 4: Transfer learning and object detection
This week introduces students to training models, as well as object detection pipelines and metrics. Students will modify and fine-tune existing models for a  image classification problem. The week concludes with demo on object detection and illustrate metrics on object detection pipelines (mAP, IoU).

## Focus
- Understand what transfer learning is and why it’s useful
- Fine-tune a pretrained model for a new classification task
- Explore object detection with a pretrained model

## Hands-On Activities
- Load a pretrained model (e.g., ResNet18 or MobileNetV2) and fine-tune it (e.g., on fashion mnist).
- Evaluate and visualize model performance using metrics from week 3. 
- Run an object detection model on custom images using pretrained models

## Learning Outcomes
By the end of this week, students will be able to:

- Explain what transfer learning is and when to use it
- Modify and fine-tune pretrained image classification models
- Evaluate performance and mitigate overfitting on small datasets
- Compare classical ML and deep learning workflows
- Run an object detection model using a pretrained network
- Explain metrics on object detection networks

## Resources

- [torchvision.models documentation](https://pytorch.org/vision/stable/models.html)
- [DeepGlue fine-tuning example](https://github.com/EricThomson/deepglue)
- Hugging Face Vision Models or YOLO demo notebooks

## Instructor Notes
Students should focus on understanding the logic of training and transfer learning rather than all the details: we are training future data engineers not data scientists. 
