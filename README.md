# Image-to-Image Virtual Try-On with IDM-VTON and IP-Adapter 

  

This repository contains a complete workflow for Image-to-Image virtual try-on using IDM-VTON, IP-Adapter, and custom nodes like GroundingDINO and Segment Anything (SAM). The workflow allows users to perform garment try-ons by utilizing a variety of models and deep learning techniques. 

## Project Overview 

The workflow is designed using ComfyUI and includes models like IDM-VTON and IP-Adapter. It integrates various image processing nodes to refine segmentation and pose estimation, leading to accurate virtual try-ons. 

## Prerequisites 

Before you begin, ensure you have met the following requirements: 

- **Operating System**: Windows/Linux/MacOS 

- **Python**: Version 3.9 or higher 

- **ComfyUI**: Installed and set up on your machine 

## Installation 

Follow these steps to set up the environment and run the workflow 

### Step 1: Clone this repository 

```bash 

git clone <l> 

cd Image-to-Image 

## Setup Instructions 

## ComfyUI Manager  

ComfyUI Manager provides seamless installation of models and custom nodes.  

Download link : https://github.com/ltdrdata/ComfyUI-Manager.git 

### Required Model Files  

The following models are required for this workflow but are not included in the repository due to size limitations. Please download them using the links below and place them in the appropriate directories. 

  

1. **IDM-VTON Model**: 

   - Download Link: [IDM-VTON on Hugging Face](https://huggingface.co/yisol/IDM-VTON) 

   - After downloading, place it in the `models/IDM-VTON` folder. 

  

2. **Juggernaut XL Safetensor**: 

   - Download Link: [Juggernaut XL on Civitai](https://civitai.com/models/133005/juggernaut-xl) 

   - After downloading, place it in the `models/checkpoints` folder. 

  

3. **IP-Adapter Models**: 

   - Download Link: [IP-Adapter on GitHub](https://github.com/cubiq/ComfyUI_IPAdapter_plus) 

   - Place the models in the `models/ipadapter` folder. 

 
