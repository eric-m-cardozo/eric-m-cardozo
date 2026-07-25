# Eric M. Cardozo

I'm Eric, a physics graduate who turns mathematical theory into software infrastructure. While I'd love to dive into the physics here, this space is dedicated to showcasing the open-source software tools and engineering projects I build and maintain.

## Python Developer Tools

*Originally built as proofs of concept while exploring architectural patterns and domain-driven design (DDD), these libraries have evolved into practical, lightweight utilities for day-to-day development. Published on PyPI.*

* **[PyDepends](https://github.com/eric-m-cardozo/PyDepends):** A lightweight, type-annotated dependency injection framework designed for immediate, out-of-the-box ease of use.
* **[PyMsgbus](https://github.com/eric-m-cardozo/PyMsgbus):** An event-driven messaging framework for pub/sub architectures. *(Read the [Documentation](https://eric-m-cardozo.github.io/PyMsgBus/))*
* **[TorchSystem](https://github.com/eric-m-cardozo/TorchSystem):** A modular toolkit built to cleanly separate pure ML model logic from messy infrastructure in PyTorch. *(Read the [Documentation](https://eric-m-cardozo.github.io/TorchSystem/))*

## The Tannic Framework

*Currently working on the Tannic Framework: a pure C++ machine learning ecosystem.*

The ML landscape moves so fast that mainstream frameworks have become bloated with compilers, domain-specific sub-languages, and hardcoded CUDA kernels in strings. They often end up harder to use and maintain than plain C++ codebases. Furthermore, Python's interpreter overhead and memory unpredictability make deployment a nightmare. The bottleneck in production is no longer writing code, it's fighting Python.

Tannic is my attempt to address this. By moving core machine learning logic back into pure C++, the goal is to reduce these friction points through a modular, predictable tensor and inference ecosystem built entirely from scratch.

### Repositories

* **[Tannic](https://github.com/eric-m-cardozo/Tannic):** The core C++23 tensor library. I am currently rewriting its execution model in C++26 through computational graphs to address some design flaws and further optimize performance and memory predictability. *(Read the [Documentation](https://eric-m-cardozo.github.io/Tannic/))*
* **[Tannic-NN](https://github.com/eric-m-cardozo/Tannic-NN):** The neural network inference library (Documentation in progress). See it in action through these implementation examples:
  * **[ConvNet on MNIST](https://github.com/eric-m-cardozo/cnn-server-example):** A classic image classification model demonstrating the framework's core 2D convolutional operations.
  * **[Vision Transformer (ViT)](https://github.com/eric-m-cardozo/vit-server-example):** Showcases the framework's ability to handle self-attention mechanisms and modern transformer architectures.
  * **[Llama 3 Inference Server](https://github.com/eric-m-cardozo/Llama3-cpp):** An end-to-end LLM inference server featuring custom POSIX socket networking to run Llama 3 models natively.
* **[PyTannic](https://github.com/eric-m-cardozo/PyTannic):** Python utilities bridging PyTorch and Tannic via network communication, including tools to serialize PyTorch models into Tannic's custom format. *(Read the [Documentation](https://eric-m-cardozo.github.io/PyTannic/))*

## Connect

If you'd like to discuss software architecture, C++ machine learning, Python tooling, or open-source development, feel free to reach out.

- **Email:** <eric.cardozo@gmail.com>
- **LinkedIn:** [eric-c](https://www.linkedin.com/in/eric-c-660099185/)
