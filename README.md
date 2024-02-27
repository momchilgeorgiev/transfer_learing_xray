# Using transfer learning for medical image classification. Pros, cons and a discussion.

## About the project
This here is my project from my last course in Deep Learning (December 2023) in SoftUni.

To test it download the repo and follow the step-by-step instruction in `/main/Project2023DL.ipynb`.

The project aims and succeeds to create a DL model that classifies x-ray images of pneumonia patients. There is also a large part of analysis of the problem at hand, comparing different research in this topic and how such a model can be improved as to have better generalization and real world application.

Grad-CAM and a segmentation algorithm (LIME) has been used for model explainability:
![img1](https://i.imgur.com/BTBq5ER.png)
![img2](https://i.imgur.com/T2VaCfN.png)

**Repo structure:**
- `/content`:
  - `/logs` - tf board log files for the training process of the models
  - `/models` - dir where you will put the trained models (more info in the main notebook)
- `/data` - dir where models will be saved
- `/main` - main dir with the project's notebook
  - `/images` - image dir
- `/research_papers` - dir with notebooks that reproduce 2 research articles
