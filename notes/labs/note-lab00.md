# Note of Lab 00

Lab00 is the introduction of the tools recommended from the class planners.

- Colab link of the Lab00: http://fsdl.me/lab00-colab

## Tools 
### ML pipeline
- Framework
    - [Meta Pytorch](https://pytorch.org/):offers GPU-accelerated array math with automatic differentiation, plus special neural network primitives and architectures.
        - [Pytorch Lightning](https://pytorch-lightning.readthedocs.io/en/stable/): A high-level framework for training or any of a number of related engineering tasks, like metric calculation or model checkpointing
    - [Google JAX](https://github.com/google/jax)
        - [flax](https://github.com/google/flax): Flax is a neural network library for JAX that is designed for flexibility. 

- Training resources
    - [Cloud GPU Comparison](https://fullstackdeeplearning.com/cloud-gpus/)
    - [Google Colab](https://colab.research.google.com): Colab Pro ($10/mo.) and Colab Pro+ ($50/mo.) 

- Training tracking 
    - [Weights & Biases](https://docs.wandb.ai/): experiment and artifact tracking platform.
    - [MLflow](https://github.com/mlflow/mlflow):an open-source library that provides similar features to W&B, but the experiment and artifact tracking server must be self-hosted
    - [Tensorboard](https://www.tensorflow.org/tensorboard):  Basic experiment tracking can also be done using Tensorboard, and shared using tensorboard.dev, but Tensorboard does not provide artifact tracking. 

- Inference
    - [TorchScript](https://pytorch.org/docs/stable/jit.html):A dialect of Torch, it drops the training engineering code and produces an artifact that is executable in C++ or in Python.

### Demo used
- Frontend 
    - [Gradio](https://gradio.app/): A python package support building a ML demo apps 
    - [Streamlit](https://streamlit.io/) 
- Backend
    - [AWS Lambda](https://aws.amazon.com/tw/lambda/): AWS serveless service
        - [A good intro of serveless](https://sst.dev/chapters/what-is-serverless.html)
    - [Docker](https://docker-curriculum.com/): A container technology to wrap the code and its dependency to make applications easier to develop/deploy.
    - [kubernetes](https://kubernetes.io/): A tool for orchestrating Docker containers
    - [AWS Elastic Container Registry](https://aws.amazon.com/tw/ecr/): A sort of "GitHub for Docker" on AWS 

### Other
- [miro](https://miro.com/): whiteboard tool