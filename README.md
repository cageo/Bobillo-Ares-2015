# Strain_Modeler
3D analysis progressive strain

Readme: Instructions for the use of the software StrainModeler developed in the paper:

StrainModeler: A MATHEMATICA based program for 3D analysis of finite and progressive strainî 
By Nilo C. Bobillo-Ares a, Jesus Aller b, Fernando Bastida b, Omar Menendez a, Richard J. Lisle c
a Departamento de Matematicas, Universidad de Oviedo, 33007 Oviedo, Spain
b Departamento de GeologÌa, Universidad de Oviedo, Jesus Arias de Velasco s/n, 33005 Oviedo, Spain
c School of Earth and Ocean Sciences, Cardiff University, Cardiff CF10 3AT, UK
The system contains two types of notebooks: 
1. StrainModeler.nb is the complete collection of the provided functions.
2. StrainModeler-Directions.nb and StrainModeler-Planes.nb are two examples that show how StrainModeler can be applied to the analysis of the deformation of a line and a plane respectively.

Workflow

To use StrainModeler follow the ensuing steps:
1. Open MATHEMATICA.
2. Open the notebook StrainModeler.nb. The following message pops up:
"Do you want to automatically evaluate all the initialization cells in the notebook StrainModeler.nb?"
You must click the ìYesî button. All the cells will be automatically executed. This teaches MATHEMATICA to analyze strains.
3. Open one of the example notebooks (StainModeler-Directions.nb or StrainModeler-Planes.nb). Executing sequentially all the cells, one at a time, you can see how StrainModeler works. The cells that contain inputs that the user must introduce are highlighted with an orange background color. Introducing in these cells the data corresponding to a specific deformation, the user can obtain the results for this deformation. 
4. A notebook provides numerical and graphical outputs. All the outputs can be hidden writing a semicolon at the end of the corresponding line. This is the option that is used by default in the StrainModeler notebooks for the numerical outputs. The user can visualize them by deleting the semicolon at the end of the line.  
5. You can open a new notebook and, imitating the examples, construct your own set of instructions in order to solve a specific problem. See the Vademecum.pdf file that contains a specification of all the functions of StrainModeler in the current version.
Remember that when you close MATHEMATICA, it forgets the definitions that it has learnt. Beginning a new session requires to follow the steps above.

