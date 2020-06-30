# CUDA_Device_Attribute_generation
Automatically generate a C++ header file including Cuda device-specific parameters


## Getting Started

### Prerequisites

This project is tested on Linux, for Windows users, please refer to [cuda-samples](https://github.com/NVIDIA/cuda-samples) for additional instructions. Download and install the [CUDA Toolkit 11.0](https://developer.nvidia.com/cuda-downloads) for your corresponding platform.
For system requirements and installation instructions of cuda toolkit, please refer to the [Linux Installation Guide](http://docs.nvidia.com/cuda/cuda-installation-guide-linux/), and the [Windows Installation Guide](http://docs.nvidia.com/cuda/cuda-installation-guide-microsoft-windows/index.html).

### Getting the tool

Using git clone the repository of CUDA_Device_Attribute_generation using the command below.
```
git clone https://github.com/BDHU/CUDA_Device_Attribute_generation.git
```
## How to Build

Simply run
```
make
```
It is only tested on Linux. To testing it on Windows, please refer to [cuda-samples](https://github.com/NVIDIA/cuda-samples) for guidances. The Makefile is modified to include header files in current directory instead of the original -I../../Common.
