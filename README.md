# Eric M. Cardozo

I'm Eric, a physics graduate who likes to turn mathematics and physics into software. While I'd love to dive into the physics here, this space is dedicated to show the open-source software tools I build and maintain.

## Python Developer Tools

*Originally built as proofs of concept while exploring architectural patterns and domain-driven design (DDD), these libraries have evolved into utilities for development. Published on PyPI.*

* **[PyDepends](https://github.com/eric-m-cardozo/PyDepends):** A lightweight, dependency injection framework designed for ease of use.
* **[PyMsgbus](https://github.com/eric-m-cardozo/PyMsgbus):** An event-driven messaging framework for pub/sub architectures. *(Read the [Documentation](https://eric-m-cardozo.github.io/PyMsgBus/))*
* **[TorchSystem](https://github.com/eric-m-cardozo/TorchSystem):** A modular toolkit built to cleanly separate logic from messy infrastructure in PyTorch. *(Read the [Documentation](https://eric-m-cardozo.github.io/TorchSystem/))*

## The Tannic Framework

*Currently working on the Tannic Framework: a pure C++ machine learning ecosystem.*

The ML landscape moves so fast that mainstream frameworks have become bloated with compilers, domain-specific sub-languages, and hardcoded CUDA kernels in strings. They often end up harder to use and maintain than plain C++ codebases. Furthermore, Python's interpreter overhead and memory unpredictability make deployment a nightmare. The bottleneck in production is no longer writing code, it's fighting Python.

Tannic is my attempt to address this. By moving machine learning logic back into C++ the goal is to reduce these friction points through a predictable inference ecosystem built from scratch.

### Repositories

* **[Tannic](https://github.com/eric-m-cardozo/Tannic):** The core C++23 tensor library. I am currently rewriting its execution model in C++26 to address some design flaws and further optimize performance and memory predictability. *(Read the [Documentation](https://eric-m-cardozo.github.io/Tannic/))*
* **[Tannic-NN](https://github.com/eric-m-cardozo/Tannic-NN):** The neural network inference library. See it in action through these implementation examples:
  * **[ConvNet on MNIST](https://github.com/eric-m-cardozo/cnn-server-example):** A classic image classification model demonstrating the framework's 2D convolutional operations.
  * **[Vision Transformer (ViT)](https://github.com/eric-m-cardozo/vit-server-example):** Show the framework's ability to handle modern transformer architectures.
  * **[Llama 3 Inference Server](https://github.com/eric-m-cardozo/Llama3-cpp):** A LLM inference server built with  POSIX sockets to run Llama 3 models locally.
* **[PyTannic](https://github.com/eric-m-cardozo/PyTannic):** Python utilities bridging PyTorch and Tannic via network communication, including tools to serialize PyTorch models into Tannic's custom format. *(Read the [Documentation](https://eric-m-cardozo.github.io/PyTannic/))*

## Connect

If you are interested in my work, feel free to contact me.

- **Email:** <eric.m.cardozo@gmail.com>
- **LinkedIn:** [eric-c](https://www.linkedin.com/in/eric-c-660099185/)
