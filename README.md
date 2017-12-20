# NasTool
NasTool is an Eclipse-based tool for deriving and generating model metrics from any domain defined by Ecore. NasTool is easy to use, only few mouse clicks are needed to automatically derive, specify and generate domain metrics from any given domain modeled on EMF Ecore. 

More information can be found at https://www.uni-marburg.de/fb12/arbeitsgruppen/swt/nebras-nassar

# Installation:
1.	Install the Eclipse Modeling Tool via: https://www.eclipse.org/downloads/packages/
2.	Install OCL in Eclipse: You can use the update manager in Eclipse to find and install it.
3.	Install the reporting tool BIRT: You can use the update manager in Eclipse to find and install it.
4.	Install Henshin (the current release): Please see the following link: https://www.eclipse.org/henshin/install.php
5.	Install EMF Refactor: NasTool  uses EMF Refactor to calculate the generated metrics on model instances. Please use the following link to install the new version of EMF Refactor using the update manager in Eclipse: https://nassarn.github.io/home/projects/emfrefactor/release
6. Install NasTool: Please use the following link to install the new version of NasTool using the update manager in Eclipse: https://nassarn.github.io/home/projects/nastool/release
7.	Make sure that your Eclipse uses JavaSE-1.8 or later.



# Getting Started:

NasTool is easy to use. To run the NasTool, you need only one mouse-right click on a given model (Ecore file) and then to find the following path: Nas Tool -> generate concrete metrics. Once you clicked on it, you will get a user-friendly wizard page for choosing the target plug-in project which will contain all the generated classes of the derived metrics.

The tool has a view component which provides statistical information about the number of the pattern matches and the derived metrics for each applied pattern as well as the total number of the matches. To display the view component in eclipse, please go to  windows -> show view –> other -> Nas Tool Category-> Nas Tool View.

To calculate the generated metrics on instance models:
1. Make sure that the target project, i.e., the project which holds the generated classes of derived metrics, is deployed in your Eclipse.
2. Right click on an instance model in the tree-based editor and then choose  EMF Quality Assurance (using existing techniques) -> Calculate metrics.

Note:
- The target project, i.e., the project which holds the generated classes of derived metrics, has to be a plug-in project. Note, once you create a plug-in project, the options: “Generate an activator” and “This plug-in is a singleton” have be activated.
- To configure the generated metrics on instance models: Right click on the project which holdes the instance models and then choose properties->EMF Quality Assurance->Metrics configuration.
