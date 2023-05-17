**[NYU]**

# Project: Comparing Segmentation models: Segment anything model (SAM) vs UNET on image segmentation

In this project, we'll reproduce the SAM project by MetaAI, we will look into the model architectures of Segment anything model and UNET which has been mostly used image segmentation, we will later fine train SAM and UNET on a dataset of medical images. 

Team member 1: Anupam Tiwari (ast9885) 

Team member 2: Ankur Aggarwal (aa10336)

[[`Report`](https://github.com/anupam-tiwari/deep_learning_final_project/tree/main/report)][[`Demo`](https://github.com/anupam-tiwari/deep_learning_final_project/tree/main/notebook)] [[`Dataset`](https://huggingface.co/datasets/nielsr/breast-cancer)]

![SAM design](https://images.prismic.io/encord/b1552393-346e-4dc2-913d-6d8100789907_univercel-segmentation-model.png?auto=compress,format)


The **Segment Anything Model (SAM)** and **UNET** produces high quality object masks from input prompts such as points or boxes, and it can be used to generate masks for all objects in an image.


## Installation

The code requires `python>=3.8`, as well as `pytorch>=1.7` and `torchvision>=0.8`. Please follow the instructions [here](https://pytorch.org/get-started/locally/) to install both PyTorch and TorchVision dependencies. Installing both PyTorch and TorchVision with CUDA support is strongly recommended.

Install Notebook

```
run it locally or on colab

```
