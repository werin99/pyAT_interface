# Interface for pyAT 
This code is an interface running in Jupyter Notebook or Google Colab, removing the necessity of programming skills, to run basic accelerator physics calculations using pyAT in a "clean" environment.
Many of the calculations, element definitions and analysis from pyAT are NOT available!

The interface is developed to allow easy access for early stage students to use a powerful simulation tool without extensive previous knowledge. The modules in the code are chosen and designed to follow simulation exercises in a course given at Lund University, Sweden.

A strong feature of the implementation is that it is possible to run in the cloud on any device, even your mobile phone.

The Google Colab version is also available directly in Colab: https://colab.research.google.com/drive/1uOLLd8QILGk0empEv1FgIUR25RKu4rky?usp=drive_link

The main difference in the implementation is that the accelerator lattice is described in a Pandas DataFrame. This makes is easier to change and input the lattice without computer skills, BUT limits the parameters and element types possible to define. This can however easily be expanded for more advanced applications.

Reference:
Using Accelerator Toolbox in a teaching environment, S. Werin, J. Bjorklund Svensson, F. Curbis and J. Lundquist, proceedings IPAC 2026, Deauville, France 2026


