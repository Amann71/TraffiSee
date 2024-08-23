Traffic Signs Detection


<img src="https://ai.github.io/size-limit/logo.svg" align="right" alt="Size Limit logo by Anton Lovchikov" width="120" height="178">
This is a deep learning project that uses artificial intelligence technology to easily detect traffic signs within a 100-meter range and notify the driver with an accuracy rate of 98% - 100% within seconds. In the creation of this project, many libraries were utilized, starting with Numpy (you can find the list of libraries used below). We used a massive dataset at the beginning of the project, consisting of approximately 50,000 traffic sign images. The more extensive the dataset, the higher the accuracy and speed of the project’s output. For pixel-by-pixel analysis of the elements in the datasets, we used Keras AI frameworks, which allowed the Numpy framework to compile the dataset for us, and Keras thoroughly analyzed it and stored it in the computer’s processor. Later, when it came to image processing, we used the Open CV framework, which transmits the data received from the device's camera to the base data, thus connecting the client to the system. Finally, we used TensorFlow, a very useful and popular framework that allows us to manage all these processes efficiently. We can consider TensorFlow as the backbone of our project because it processes and presents all operations to us. Below, you can see step-by-step how to use the project.

Numpy
Matplotlib
Keras
Open CV
Pickle
OS
Random
TensorFlow
The device processes the data received from the camera directly and provides output, along with statistical data.

<p align="center">
<img src="https://github.com/yusufaras104/Open_CV/blob/main/assest/images/opencv.png" alt="Size Limit comment in pull request about bundle size changes" width="686" height="289">
</p>
How It Works
First and foremost, the system’s requirements must be met for it to function properly. These are the tools that need to be installed: Numpy, Matplotlib, Keras, Open CV, OS, Pandas, Random, TensorFlow.
Then, by using the source code available in our Git repository, you can follow up on the missing tools, complete your requirements, and run the project. See here
After running the project, your device will first need to recognize and analyze the elements in the dataset.
After the scanning process, our AI tools store these data in the base and statistically define them.
After the scans and learnings, our image processing tool, Open CV, comes into play and sends the data received from the device's camera to the TensorFlow for processing by the processor.
When it comes to the TensorFlow phase, we reach the final point where all the steps above are performed one by one, and after that, the system fully outputs and informs the client side based on the input provided.
Installation of Necessary Plugins
Here, the pip file manager is used. If pip is not installed, it needs to be installed ($ python -m ensurepip --upgrade, <br>
$ python get-pip.py, $ python -m pip install --upgrade pip ).

<details><summary><b>Step-by-Step Installation</b></summary>
Numpy :
pip install numpy
Matplotlib : pip install matplotlib
Keras : $ pip install --upgrade pip, $ pip install tensorflow, $ pip install tf-nightly
Open CV :
diff
Copy code
+ git clone https://github.com/Amann71/TraffiSee
+ git -C opencv checkout <some-tag>
+ # optionally
+ git clone https://github.com/Amann71/TraffiSee
+ git -C opencv_contrib checkout <same-tag-as-opencv> 
+ # optionally
+ git clone https://github.com/Amann71/TraffiSee
+ git -C opencv_extra checkout <same-tag-as-opencv>
Pandas:
diff
Copy code
1. Download Anaconda and the latest version of Python for your operating system, run the installer, and follow the steps. Please keep in mind:

+ It is not necessary (and not recommended) to install Anaconda as root or administrator.
+ When asked if you want to start Anaconda3, respond with yes.
+ Restart the terminal after completing the installation.
+ Detailed instructions on how to install Anaconda can be found in the Anaconda documentation.

2. Start JupyterLab from the Anaconda prompt (or terminal on Linux or MacOS):

<img src="https://pandas.pydata.org/static/img/install/anaconda_prompt.png"
alt="Size Limit comment in pull request about bundle size changes"
width="686" height="289">

</p>
  ```
```diff
  3. In JupyterLab, create a new notebook (Python 3):
  ,,,
  <img src="https://pandas.pydata.org/static/img/install/jupyterlab_home.png"
  alt="Size Limit comment in pull request about bundle size changes"
  width="686" height="289">
diff
Copy code
4. In the first cell of the notebook, import pandas and check the version as follows:
<img src="https://pandas.pydata.org/static/img/install/pandas_import_and_version.png"
alt="Size Limit comment in pull request about bundle size changes"
width="686" height="289">

diff
Copy code
5. You are now ready to use pandas, and you can write your code in the subsequent cells.
</details>
