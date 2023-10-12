# Getting Started with Idefics and Hugging Face

This repository contains instructions/examples/tutorials for getting started with Idefics and Hugging Face libraries like [transformers](https://huggingface.co/docs/transformers/index), [datasets](https://huggingface.co/docs/datasets/index).

IDEFICS is an open-access visual language model with 80 billion parameters that can generate text based on sequences of images and text. It was created to reproduce capabilities similar to Deepmind's closed-source Flamingo or Open AI GPT-4V model using only publicly available data and models.


### Training

* [Fine-tune Idefics 9B on Amazon SageMaker](./training/sagemaker-notebook.ipynb) _coming_
* [Deploy Idefics 9B & 80B on Amazon SageMaker](./infernece/sagemaker-notebook.ipynb) 

## Requirements

Before we can start make sure you have met the following requirements

* AWS Account with quota
* [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html) installed
* AWS IAM user [configured in CLI](https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html) with permission to create and manage ec2 instances

### Commands 

```bash
watch -n0.1 nvidia-smi
```