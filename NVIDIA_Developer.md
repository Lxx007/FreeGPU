# How to obtain free API keys for various models through the NVIDIA Developer Programme
NVIDIA NIM™, part of NVIDIA AI Enterprise, provides containers to self-host GPU-accelerated inferencing microservices for pretrained and customized AI models across clouds, data centers, and workstations. Upon deployment with a single command, NIM microservices expose industry-standard APIs for simple integration into AI applications, development frameworks, and workflows. Built on pre-optimized inference engines from NVIDIA and the community, including NVIDIA® TensorRT™ and TensorRT-LLM, NIM microservices automatically optimize response latency and throughput for each combination of foundation model and GPU system detected at runtime. NIM containers also provide standard observability data feeds and built-in support for autoscaling on Kubernetes on GPUs.

Please prepaer your NVIDIA account in advance!

Start here: https://developer.nvidia.com/developer-program. Just click, click and click following the image below to get access to the Developer Programme.

<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/NVIDIA/NVIDevelop.bmp" width="600" />
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/NVIDIA/NVISDKs.bmp" width="600" />
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/NVIDIA/NVINGC.bmp" width="600" />

After clicking on the Explore NGC button you will see the following scene. 

<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/NVIDIA/DeveloperScene.bmp" width="600" />

NVIDIA NGC has many models that can be used for free, please follow the steps below to get the API key for the model you want. For example, we want to use meta-llama-2-13b-chat. Click Learn More!

<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/NVIDIA/DetailedModel.bmp" width="600" />

Once you have read and understood the service on this page, click Get Container. NVIDIA will ask you to create an NVIDIA Developer Program account, or if you already have one, click Create Account again and you will be taken to the NVIDIA Developer Program page under your account.
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/NVIDIA/GetContainer.bmp" width="600" />

# Your NVIDIA Developer Program page
Click the Generate API Key button on the page to get your own API key.
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/NVIDIA/GetAPIKey.bmp" width="600" />

Once you have the API key, the page will tell you how to run your chosen model locally. You will need to prepare your own IDE.
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/NVIDIA/RunLocal.bmp" width="600" />

# Let's check if you can run the Model!
The environment is visual studio 2022, after getting the API Key for meta/llama-3.1-405b-instruct in NVIDIA NIM, the result is as follows：
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/NVIDIA/ShowResults.bmp" width="600" />
