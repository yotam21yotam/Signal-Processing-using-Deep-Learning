# Transferlearning

Here our main goal was to compare between diffrent types of transferlearning methods.
The main Notebook that you should be running is-
'MobileNet vs ResNet vs VGG + TIMIT'.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for running and testing purposes.

### Prerequisites

* python 3

Following libraries needs to be installed in order to run the project-

* pandas
* matplotlib
* numpy
* keras
* tensorflow
* glob
* Jupiter Notebook

Windows-
You will also need to install Anaconda

If your computer does not have a GPU please update GPU to 0 instead of 1 in this line as following-
Also update the CPU number with as many cores that your computer own.
```
config = tf.ConfigProto( device_count = {'GPU': 0 , 'CPU': 8} ) 
```

### Installing

Windows-

Install all packages using the conda-install command as following-

```
conda install -c anaconda pandas 
```


Ubuntu-
```
sudo apt-get install python3-pandas 
```

PyPI-
```
pip install pandas 
```


And repeat on all libraries from the 'Prerequisites' if the libraies are not installed on your local computer (or conda virtual env)


## Running the Notebook

Windows-
Open you Anaconda Navigator and Launch the Jupiter Notebook application (make sure you are on the right virtual env)

Ubuntu-
Open a Terminal window and run following command-
```
jupiter notebook 
```


The notebook will open. You can either run one cell at a time or click 'Cell' --> 'Run All'