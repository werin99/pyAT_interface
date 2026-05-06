# Interface for pyAT 
This code is an interface running in Jupyter Notebook or Google Colab, removing the necessity of programming skills, to run basic accelerator physics calculations using pyAT in a "clean" environment.
Many of the calculations, element definitions and analysis from pyAT are NOT available!

The interface is developed to allow easy access for early stage students to use a powerful simulation tool without extensive previous knowledge. The modules in the code are chosen and designed to follow simulation exercises in a course given at Lund University, Sweden.

A strong feature of the implementation is that it is possible to run in the cloud on any device, even your mobile phone.

The Google Colab version is also available directly in Colab: https://colab.research.google.com/drive/1uOLLd8QILGk0empEv1FgIUR25RKu4rky?usp=sharing

The main difference in the implementation is that the accelerator lattice is described in a Pandas DataFrame. This makes is easier to change and input the lattice without computer skills, BUT limits the parameters and element types possible to define. This can however easily be expanded for more advanced applications.

Reference:
Using Accelerator Toolbox in a teaching environment, S. Werin, J. Bjorklund Svensson, F. Curbis and J. Lundquist, proceedings IPAC 2026, Deauville, France 2026

## Running in Colab
This is directly available through this link:
https://colab.research.google.com/github/werin99/pyAT_interface/blob/master/pyAT_interface_Colab.ipynb 

To save changes you have to save to your own Google Drive. From there you can also store different files for different sessions.

## Running in another Jupyter Notebook environment
You can either download the pyAT_interface_JN.ipynb directly from here
- Click to open the file
- press the "three dots" at the top right corner and choose "Download"

In many Jupyter Notebook sessions you can directly "clone" (download all files) from a GitHub repository.
Clone using this link: 

https://github.com/werin99/pyAT_interface.git

You will get a new folder in the left panel "pyAT_interface". 
Open the folder and select "pyAT_interface_JN.ipynb"
(While the Colab version will run, it will also display a lot of code.)

## Needed modules
Some modules are needed. While many are standard some might be needed to install, especially if you run in your own Jupyter Notebook environment.
"accelerator-toolbox" is in principle never available and has to be installed.
This is done by the code itself when running in Colab and should work also in other environments.
(To install manually: "pip install accelerator-toolbox")

These modules are also needed (all are by default available in Colab and EOSC)
- numpy
- matplotlib
- pandas
- ipywidgets
- IPython

