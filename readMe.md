
# Fluid Dynamics with Python
### ICT Summer School 2022

Welcome to _Fluid Dynamics with Python_ in ICT Summer School 2022. 
On this course, we will learn the fundamental of fluid dynamics as well as Python programming. In addition, we will also learn Computational Fluid Dynamics (CFD) by coding solutions to the basic partial differential equations that describe the physics of fluid flow.
Some course materials are custimized for this course from a course by [Prof. Lorena Barba](http://lorenabarba.com) between 2009 and 2013 in the Mechanical Engineering department at Boston University (Prof. Barba since moved to the George Washington University).


### Learning outcomes of the course
This course introduces the fundamentals of fluid dynamics and its practices with Python. The participating students learn the government equations for fluid flow and how to compute them by using jupyterLab. Specifically, the following study aims and competencies are highlighted in this course;
•	to increase knowledge about the fundamentals of fluid dynamics
•	to increase knowledge about the governing equations for fluid flow 
•	to calculate some simplified 2-D fluid flow fields using computational fluid dynamics and jupyterLab.
•	to calculate the wind flows in the simplified 2-D city areas using actual map data and meteorological data.
•	to acquire Python programming skills for fluid flow calculations


### Prerequisites and co-requisites
Participating students have basic mathematics, such as linear algebra, vector and matrix operations, linear combination, basic multivariate calculus, partial differential equation, etc.
The students preferably have basic programming skills in Python.


### Course contents
#### Session 1: Quick introduction to Python (jupyterLab)
- How to program by using Python (jupyterLab)
- Variables / Arrays / Libraries / Assigning array variables
- How to visualize results of fluid flow calculations
#### Session 2: Basis of fluid dynamics
- Governing equations of fluid flow
#### Session 3: Fundamentals of discretization of partial differential equations
- Explicit scheme / Implicit scheme / semi-implicit scheme
- discretizing diffusion equations by using spreadsheet software
#### Session 4: Fluid dynamics simulation (computation 1) 
- One-dimensional diffusion equation
- Linear and non-linear convection equations
- Laplace equation / Poisson equation
#### Session 5: Fluid dynamics simulation (computation 2)
- Cavity flow
- Channel flow
#### Session 6: Fluid dynamics simulation (computation 3)
- wind flows in simplified 2-D city areas.
- Independent research by using fluid dynamics simulation


### Assessment criteria
#### Satisfactory
Daily exercises on the course are worth 50%, and reports about fluid dynamics simulation (python programming) are worth 50%.


### Approved / Failed
Daily exercises on the course are worth 50%, and reports about fluid dynamics simulation (python programming) are worth 50%.


### Further information
A computer with the following software is necessary: Office software (i.e., MS Office, Apple Keynote/Numbers/Pages, Libre Office) and a web browser that can execute "google colaboratory" on it.
Slides, exercise handouts, and jupyterLab examples will be provided in sessions.


### Recommended optional programme components
The student advisor will recommend optional programme components for each student based on their individual study plan.



-------
## How to use this module

In a regular-session university course, students can complete the **CFD Python** lessons in 4 to 5 weeks. 
As an intensive tutorial, the module can be completed in two or three full days, depending on the learner's prior experience. 
The lessons can also be used for self study. 
In all cases, learners should follow along the worked examples in each lesson by re-typing the code in a fresh Jupyter notebook, maybe taking original notes as they try things out. 

Lessons

> Launch an interactive session with this module using the Binder service:
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/barbagroup/CFDPython/master)

Steps 1–4 are in one spatial dimension. Steps 5–10 are in two dimensions (2D). Steps 11–12 solve the Navier-Stokes equation in 2D. Three "bonus" notebooks cover the CFL condition for numerical stability, array operations with NumPy, and defining functions in Python.

* [Quick Python Intro](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/00_Quick_Python_Intro.ipynb)
—For Python novices, this lesson introduces the numerical libraries (NumPy and Matplotlib), Python variables, use of whitespace, and slicing arrays.
* [Step 1](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/01_Step_1.ipynb)
—Linear convection with a step-function initial condition (IC) and appropriate boundary conditions (BCs).
* [Step 2](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/02_Step_2.ipynb)
—With the same IC/BCs, _nonlinear_ convection.
* [CFL Condition](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/03_CFL_Condition.ipynb)
—Exploring numerical stability and the Courant-Friedrichs-Lewy (CFL) condition.
* [Step 3](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/04_Step_3.ipynb)
—With the same IC/BCs, _diffusion_ only.
* [Step 4](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/05_Step_4.ipynb)
—Burgers’ equation, with a saw-tooth IC and periodic BCs (with an introduction to Sympy).
* [Array Operations with NumPy](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/06_Array_Operations_with_NumPy.ipynb)
* [Step 5](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/07_Step_5.ipynb)
—Linear convection in 2D with a square-function IC and appropriate BCs.
* [Step 6](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/08_Step_6.ipynb)
—With the same IC/BCs, _nonlinear_ convection in 2D.
* [Step 7](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/09_Step_7.ipynb)
—With the same IC/BCs, _diffusion_ in 2D.
* [Step 8](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/10_Step_8.ipynb)
—Burgers’ equation in 2D
* [Defining Functions in Python](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/11_Defining_Function_in_Python.ipynb)
* [Step 9](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/12_Step_9.ipynb)
—Laplace equation with zero IC and both Neumann and Dirichlet BCs.
* [Step 10](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/13_Step_10.ipynb)
—Poisson equation in 2D.
* [Step 11](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/14_Step_11.ipynb)
—Solves the Navier-Stokes equation for 2D cavity flow.
* [Step 12](http://nbviewer.jupyter.org/github/barbagroup/CFDPython/blob/master/lessons/15_Step_12.ipynb)
—Solves the Navier-Stokes equation for 2D channel flow.



-------
## Dependencies

To use these lessons, you need Python 3, and the standard stack of scientific Python: NumPy, Matplotlib, SciPy, Sympy. And of course, you need [Jupyter](http://jupyter.org)—an interactive computational environment that runs on a web browser.

This mini-course is built as a set of [Jupyter notebooks](https://jupyter-notebook.readthedocs.org/en/latest/notebook.html) containing the written materials and worked-out solutions on Python code. To work with the material, we recommend that you start each lesson with a fresh new notebook, and follow along, typing each line of code (don't copy-and-paste!), and exploring by changing parameters and seeing what happens. 


#### Installing via Anaconda
We *highly* recommend that you install the [Anaconda Python Distribution](http://docs.continuum.io/anaconda/install). It will make your life so much easier. 
You can download and install Anaconda on Windows, OSX and Linux. 

After installing, to ensure that your packages are up to date, run the following commands in a terminal:

```Bash
conda update conda
conda update jupyter numpy sympy scipy matplotlib
```

If you prefer Miniconda (a mini version of Anaconda that saves you disk space), install all the necessary libraries to follow this course by running the following commands in a terminal:

```Bash
conda update conda
conda install jupyter
conda install numpy scipy sympy matplotlib
```


#### Without Anaconda
If you already have Python installed on your machine, you can install Jupyter using pip:

```Bash
pip install jupyter
```

Please also make sure that you have the necessary libraries installed by running

```Bash
pip install numpy scipy sympy matplotlib
```


### Running the notebook server

Once Jupyter is installed, open up a terminal and then run 

```Bash
jupyter notebook
```

This will start up a Jupyter session in your browser!


> This lecture refers "CFD Python: the 12 steps to Navier-Stokes equation.", _Journal of Open Source Education_, **1**(9), 21 (2018) https://doi.org/10.21105/jose.00021 by Barba, Lorena A., and Forsyth, Gilbert F.
