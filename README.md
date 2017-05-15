# Accent Detection With Tensorflow and Librosa
Senior Project To Detect Accent Using Tensorflow and Librosa

This project was done using Windows 10 with a Nvidia GTX860M graphics card. 
You can accomplish the same using a computer without a graphics card by downloading the CPU version of Tensorflow. However, note that with the CPU version, it will take much longer for Tensorflow to build your models.
## Step 1
First we need to install Python 3.5.x
Go to 
https://www.python.org/ftp/python/3.5.2/python-3.5.2-amd64-webinstall.exe
and download and install python.

Then, open up the command prompt and type:

python -V

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

We can see what packages we currently have in our tensorflow environment. This will be important during the rest of the installation process to make check that we have installed everything correctly.

hi

hii

conda create -n tensorflow
activate tensorflow
python -V
conda list
conda install python=3.5.2
conda install -c conda-forge librosa
