# How to use Free GPUs on Google Colab

Please prepare your Google account in advance!

Google Colab is a project of Google Research, a free Jupyter-based environment that allows us to create Jupyter notebooks to write and run Python (and other Python-based third-party tools and machine learning frameworks such as Pandas, PyTorch, Tensorflow, Keras, Monk, OpenCV, and others) in a web browser.
The webpage is "https://colab.research.google.com/"

When you open this website, you will see the following page.

<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/ColabInitial.bmp" width="1000" />

Click 1 --> 2.A, to create a new notebook on your Google Drive.

Click 1 --> 2.B, to select a new file opened in GoogleColab.

After 2.B, you will see the next screen.

Icon 1 means that the file is on GoogleColab. Icon 2 means this file is on your Google Drive. Icon 3 means this file is on your Github.
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/ChooseFile.bmp" width="600" />


Then select a file after 2.B or 2.A. Your code page will be displayed as below.
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/ChooseGPU.bmp" width="1000" />
Click 1 and then 2 to make your project run in the environment you want.

After clicking 2, you will see the following choices. Make your own choice.
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/PickGPU.bmp" width="600" />

Save your choice. 
# Then let's check if the GPU has been successfully set!
Use the following code, if your output is "True" it means your project is now running in a GPU environment!

import torch

torch.cuda.is_available()

<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/GPUSuccess.bmp" width="1500" />

# More
You can use the following code to check your detailed GPU settings!

torch.cuda.is_available() --> GPU availability

torch.cuda.current_device() --> your current GPU ID

torch.cuda.device(0) --> Your current GPU address

torch.cuda.device_count() --> Available number of GPUs

torch.cuda.get_device_name(0) --> Your current GPU name
