# Webpage Elements Detection using Roboflow API

This project demonstrates how to perform webpage elements detection using the Roboflow API. The Roboflow API allows you to integrate computer vision models trained on your custom datasets into your applications.

## Getting Started

### Prerequisites

Before running the code, make sure you have the following dependencies installed:

- Python 3.x
- `transformers`, `torch`, `PIL`, `requests`, and `inference-sdk` Python packages
- `opencv-python-headless` and `matplotlib` Python packages for visualization

You can install the required packages using pip:

```bash
pip install transformers torch Pillow requests inference-sdk
pip install opencv-python-headless matplotlib
```
## Setting up Roboflow API

To use the Roboflow API, you need to obtain your API key from the Roboflow platform. Once you have your API key, replace `"YOUR_API_KEY_HERE"` in the code with your actual API key.

## Running the Code

1. **Import the necessary libraries and install the required packages** using the provided code.
2. **Initialize the InferenceHTTPClient** with your API URL and API key.
3. **Iterate through the images** in the contents folder and perform inference on each image using the initialized client.
4. The **detected objects and their classes** will be visualized on the images.

## License

This project is licensed under the GPL 3.0 License.
