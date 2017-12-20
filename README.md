# NasTool
NasTool is an Eclipse-based tool for deriving and generating model metrics from any domain defined by Ecore. NasTool is easy to use, only few mouse clicks are needed to automatically derive, specify and generate domain metrics from any given domain modeled on EMF Ecore. 

More information can be found at https://www.uni-marburg.de/fb12/arbeitsgruppen/swt/nebras-nassar

# Installation:
1.	Install the Eclipse Modeling Tool via: https://www.eclipse.org/downloads/packages/
2.	Install OCL in Eclipse: You can use the update manager in Eclipse to find and install it.
3.	Install the reporting tool BIRT: You can use the update manager in Eclipse to find and install it.
4.	Install Henshin (the current release): Please see the following link: https://www.eclipse.org/henshin/install.php
5.	Install EMF Refactor: NasTool  depends on EMF Refactor to calculate the generated metrics on model instances. Please use the following link to install the new version of EMF Refactor using the update manager in Eclipse: https://nassarn.github.io/home/projects/emfrefactor/release
6. Install NasTool: Please use the following link to install the new version of NasTool using the update manager in Eclipse: https://nassarn.github.io/home/projects/nastool/release
7.	Make sure that your Eclipse uses JavaSE-1.8 or later.

# Remarks for using NasTool:
The target project, i.e., the project which holds the classes of generated metrics, has to be a plug-in project. Note, once you create a plug-in project, the options: “Generate an activator” and “This plug-in is a singleton” have be activated.
