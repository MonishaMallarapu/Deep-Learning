## Deep-Learning
My Deep Learning path

TensorFlow makes it easy to create machine learning models. I was stuck with few roadblocks while installing the Tensorflow module through Anaconda Navigator. Even after installing Tensorflow module, I was not able load tensorflow through Jupyter Notebook. The reason I found was the version of python. In most of the cases the python 3.6 is not supportive for Tensorflow. So, I reverted the python version to 3.5 and installed Tensorflow with the following command:<br>

$ conda create -n tensorflow python=3.5<br>
$ activate tensorflow<br>

This creates a new environment in Anaconda Navigator. Add the required modules to this environment and it's good to start experimenting with Tensorflow.<br>
