# FO particle tracking model

### A partcle tracking moduel forced by a Faroese barotropic mode of the regional oceanic modeling system (ROMS) with a 100 m resolution grid for the coastal region (Simonsen & Niclasen 2021). 


## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Model Illustration](#model-illustration)
* [Status](#status)
* [Inspiration](#inspiration)
* [License](#license)
* [Contact](#contact)


## General info

	
## Technologies
The project is created with:
* Python version 3.?? or newer.
* Cython
	
## Setup
To run this project, you need to install Python. Python can be downloaded [here](https://www.python.org/downloads/).

install requirments.txt with 
>pip install -r requirments.txt

To install cython go [here](https://cython.readthedocs.io/en/stable/src/quickstart/install.html)


    Linux The GNU C Compiler (gcc) is usually present, or easily available through the package system. On Ubuntu or Debian, for instance, the command sudo apt-get install build-essential will fetch everything you need.

    Mac OS X To retrieve gcc, one option is to install Apple’s XCode, which can be retrieved from the Mac OS X’s install DVDs or from https://developer.apple.com/.

    Windows A popular option is to use the open source MinGW (a Windows distribution of gcc). See the appendix for instructions for setting up MinGW manually. Enthought Canopy and Python(x,y) bundle MinGW, but some of the configuration steps in the appendix might still be necessary. Another option is to use Microsoft’s Visual C. One must then use the same version which the installed Python was compiled with.



run 
>"python setup.py build_ext --inplace" to run cython version.

The repository can be downloaded to your local environment, where running the file runscript.py will simulate a simple test run where no external data is needed. Be aware that matplotlib 3.3.2 or newer is needed.

get gps coord from: http://192.168.43.83:3838/shiny_tekna_a_kort/

    
## Model Illustration    
A description of the model structure is shown below.

## Status
Project is: _in progress_

## Inspiration
Tróndur T. Johannesen, Torstein Balle and more.

## License
MIT License

Copyright (c) 2020 TrondurJK

## Contact
Created by [trondkraga@gmail.com](https://github.com/TrondurJK) - onkur heimasíða - feel free to contact me!

