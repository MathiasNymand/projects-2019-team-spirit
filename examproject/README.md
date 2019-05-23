# Examproject

This project includes 4 parts. 
1. A dataproject
2. A modelproject
3. The examproject
4. A txt file with links to the feedback that we have given.

**PART 1:**
In the data project we are examining whether there are any correlation between unemployment rates and fertility rates on a municipality level in Denmark in the years from 2007 until 2017. First we download the tables of interest from Denmark Statistics (DST), (using API) and then merge them into a combined dataset. We are importing FOD407 which contains information about the fertility rate for each municipal in Denmark, and we also extract data from AULP01 which has information regarding the unemployment rate in Denmark on a municipality level as well. 
Utilizing this combined dataset we do some graphical explorations of the evolution of the unemployment rate and the fertility rate and the correlation between the two. Specifically, we are presenting a map showing the fertility rate and the unemployment rate for each municipal in 2007 and 2017. Furthermore, we are showing a figure where the two variables are indexed. This graph is an interactive figure where the development for both the fertility rate and the unemployment rate can be explored for each municipal in the timeline 2007-2017.


In order for the project to work it is important that the API from Statistics Denmark and GeoPandas packages are downloaded and installed. The commands for installation is available in our jupyter notebook.  Further, the shape files containing the map we are using should be downloaded from the repository in order to make the map visible.  

**PART 2:**
In the model project we implement the Green Solow Model in Python formulated by Brock and Taylor (2004). We start by defining all the necessary equations for the model, and we give a very long introduction to the model. First, we solve the transition equation analytically in sympy and calculate the steady state value of capital per effective worker. This is done by evaluating the equation with commonly agreed values of the parameters. Secondly we solve the transition equation numerically and find the steady state value of capital per effective worker.      
After solving the equations we plot the transiaiton diagram and make it interactive. This allows the reader to understand the impact of changes in the parameter values.  

Next, we look at the change in emissions, and find the level of capital where emissions are the highest. Again, this is solved analytically and again we calculate the level of capital. After the equations have been solved, we make a additional interactive plot to show the reader how the level of capital changes with the parameter values.

It is entirely on purpose that the sympy variables and and python-style parameters are left in the .py files. For different parts of the project we use the sympy variables, and other for other parts we use the numerical values. The project would be quite a lot longer if we kept re-running huge blocks of variable definitions, and therefore we have left them out.

In order for the project to work all the files from the repositories must be downloaded. This includes the .py files and the .png file. If you are using Anaconda no additional downloads will be needed for the project to run.

**PART 3:**
In the examproject we solve the models that are presented in the questions. 