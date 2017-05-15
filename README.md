# Accent Detection With Tensorflow and Librosa
University of California, San Diego 

Department of Electrical Engineering

ECE 191 Senior Project

Team Members

Kamran Aladross, Michael Burdett, Wade Chen, Max Coehing 


This project was done using Windows 10 with a Nvidia GTX860M graphics card. 
You can accomplish the same using Ubuntu or Mac OSX, as well as without a graphics card. Simply download the CPU version of Tensorflow from their website. Note that with the CPU version, it will take much longer for Tensorflow to build your models.

## Step 0 - Installing Cuda Toolkit and Cuda DNN (For GPU Version Only)

If you have an Nvidia GPU that is compatible with tensorflow, you will want to install the GPU version of Tensorflow in order to maximize your systems efficiency.

We will first need to download Nvidia's Cuda Toolkit through the following link

http://developer.nvidia.com/cuda-downloads

Next, we will need to download Cuda DNN through the following link

https://developer.nvidia.com/rdp/cudnn-download

Note that you will first need to sign up on Nvidia developer website.

*It is umportant that you download version 5.1 for windows 10.*

Now that you have downloaded both the toolkit and the DNN, you must run the cuda_8.0.61_win10.exe file to install the Cuda toolkit. Once the install has finished, you must extract the files from cudnn-8.0-windows10-x64-v5.1.zip.

Now, Go to C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v8.0 and copy the files from the extracted cudnn folders into the same labeled folders.

The Cuda Toolkit has now been dealt with, and being that your GPU is compatible with the current version of Tensorflow, you should be able to start setting up a GPU Tensorflow Environment.

## Step 1 - Setting up our Tensorflow environment in Python
First we need to install Python 3.5.x
Go to 
https://www.python.org/ftp/python/3.5.2/python-3.5.2-amd64-webinstall.exe
and download and install python.

Then, open up the command prompt and type:
```
python -V
```
You should see that your current python version is correct.

Next, we need to install anaconda.

https://www.continuum.io/downloads#windows

Once anaconda is installed, you can check its version with:

anaconda -V

Now that we have anaconda installed, we can start installing the rest of the modules needed for our project.

Again in the Command Prompt, type

conda create -n tensorflow

This creates a tensorflow environment in anaconda. After, type

activate tensorflow

Now we are in our tensorflow environment.

By typing 

conda list

We can see what packages we currently have in our tensorflow environment. This will be important during the rest of the installation process to make check that we have instaled everything correctly.

I am not sure if the next step is a redundancy, but after hours of failed attempts at setting up a working Tensorflow and librosa environment, we recommend that you install python in the tensorflow environment just to be safe.

conda install python=3.5.2


Next, we will install librosa (a Python library for audio and music analysis).

conda install -c conda-forge librosa

Then, 



hi

hii

conda create -n tensorflow
activate tensorflow
python -V
```conda list```
conda install python=3.5.2
conda install -c conda-forge librosa
