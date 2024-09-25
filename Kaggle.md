# Guide to Use GPU in Kaggle
Using a GPU in Kaggle is simple and useful for deep learning or other computationally intensive tasks. Here’s how you can enable and use a GPU in Kaggle:
## Steps to Enable GPU in Kaggle:
### 1. Register an account and sign in:
If you haven't had a Kaggle account, please register first. Then sign in to Kaggle.
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/Kaggle/homepage.png" width="800" />
### 2. Create or Open a Kaggle Notebook:
After signing in Kaggle, you can see a menu bar on the left side of the interface.  
Go to "Code" and create a new notebook or open an existing one in "Your Work".  
If you want to create a new notebook:  
1. Click the Create button.  
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/Kaggle/createnotebook_1.bmp" width="200" />  
2. Choose the "create notebook" to see you create a new notebook.
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/Kaggle/createnotebook_2.bmp" width="200" />  
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/Kaggle/createnotebook_3.bmp" width="800" />  
You can change your notebook name.
The notebook in Kaggle is similar to the Jupyter notebook. You can add code blocks or markdown blocks.
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/Kaggle/createnotebook_4.bmp" width="800" />

### 3. Enable GPU in the Notebook:  
If you want to use GPU in Kaggle, you need to verify your account using your mobile phone number.  
On the right side of the interface, scroll down and you can find a description here, click the link to verify your phone number:  
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/Kaggle/createnotebook_5.bmp" width="800" />  

Click on the “Settings” tab on the right side of the notebook interface.
Scroll down to the Accelerator section.
From the GPU dropdown menu, select a GPU. This will give you access to GPU hardware.
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/Kaggle/chooseGPU.bmp" width="800" />  

Once you select GPU, the setting will be applied immediately, and the notebook will restart using a GPU.  
 
You can verify that a GPU is available in your session by running the following Python code:  
```bash
import torch
torch.cuda.is_available()
```  

### Tips for Efficient GPU Usage:
1. Model Training: Make sure to transfer your model and data to the same GPU in deep learning frameworks like TensorFlow and PyTorch. For example, in PyTorch:  
   ```bash
   device = torch.device("cuda" if torch.cuda.is_available() else "cpu")
   model = model.to(device)
   data = data.to(device)
   ```
   
2. Check GPU Resource Limits: Kaggle provides limited GPU time, so make sure to optimize your code to make the best use of the GPU. You get around 30 hours of GPU time per week.
   and you can also see the space limits in "Draft Session".
   <img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/Kaggle/draftsession.bmp" width="800" />  

### Input and Output:
When using your own datasets and models, you can upload them in the input section:
<img src="https://github.com/Lxx007/FreeGPU/blob/main/Pictures/Kaggle/input.bmp" width="800" />  

To get the output file generated in Kaggle, please check this link:
https://www.kaggle.com/discussions/getting-started/168312  

Other documents you can check here: https://www.kaggle.com/docs
