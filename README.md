# Using NPU with OpenVINO

This project demonstrates how to utilize the Neural Processing Unit (NPU) with OpenVINO for various tasks such as image classification, image segmentation, and running a chatbot. The project includes several Jupyter notebooks that guide you through the process of downloading models, compiling them for the NPU, and running inference.

## Table of Contents
- [Installation](#installation)
- [Notebooks](#notebooks)
  - [Image Classification](#image-classification)
  - [Image Segmentation](#image-segmentation)
  - [Async API](#async-api)
  - [TinyLLamaChat](#tinyllamachat)
  - [NPU Properties](#npu-properties)
  - [Convert OpenVINO](#convert-openvino)
- [Requirements](#requirements)
- [License](#license)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/alessandropalla/intel_npu_openvino_examples.git
    cd intel_npu_openvino_examples
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Start Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

## Notebooks

### NPU Properties

The [NPU Properties](NPU%20properties.ipynb) notebook provides information about the properties and capabilities of the NPU. It includes steps to query and display various properties of the NPU.

### Image Classification

The [Image Classification](Image%20Classification.ipynb) notebook demonstrates how to perform image classification using a pre-trained MobileNet model. It includes steps to download the model, compile it for the NPU, and run inference on an image.

### Image Segmentation

The [Image Segmentation](Image%20Segmentation.ipynb) notebook shows how to perform image segmentation using a pre-trained model. It includes steps to download the model, compile it for the NPU, and run inference to segment an image.

### Async API

The [Async API](AsyncAPI.ipynb) notebook demonstrates how to use the asynchronous API of OpenVINO for video processing. It includes steps to download a video, compile a model for the NPU, and run inference in both synchronous and asynchronous modes.


### Convert OpenVINO

The [Convert OpenVINO](ConvertOpenvino.ipynb) notebook demonstrates how to convert a PyTorch model to OpenVINO format. It includes steps to load a PyTorch model, convert it to OpenVINO format, and compile it for the NPU.

### TinyLLamaChat

The [TinyLLamaChat](TinyLLamaChat.ipynb) notebook shows how to run a chatbot using the TinyLlama model. It includes steps to load the model, compile it for the NPU, and interact with the chatbot.


## Requirements

- Python 3.11
- OpenVINO
- PyTorch
- Transformers
- OpenCV
- Jupyter

For a complete list of dependencies, see the [requirements.txt](requirements.txt) file.

## License

This project is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for details.