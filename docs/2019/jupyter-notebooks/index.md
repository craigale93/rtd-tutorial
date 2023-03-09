---
title: "Jupyter Notebooks"
date: "2019-09-04"
---

  
Jupyter notebooks are web applications that combine text, code and output ([https://jupyter.org/](https://jupyter.org/)). Jupyter supports over 40 programming languages.

Jupyter notebooks can be used to analyze data stored in openBIS.  
  

It is possible to connect to a JupyterHub server and launch Jupyter notebooks directly from the openBIS interface. This feature is not available by default, but needs to be enabled and configured by a _system admin_. JupyterHub docker containers are available from our download page: [openBIS download.](https://wiki-bsse.ethz.ch/display/bis/openBIS+Download+Page) Further documentation can be found here: [JupyterHub for openBIS](https://unlimited.ethz.ch/display/openBISDoc2010/JupyterHub+for+openBIS)  
  

Jupyter notebooks can be opened at every level of the openBIS hierarchy (Space, Project, Experiment/Collection, Object, Dataset) from the More... dropdown menu, as shown below

![](images/Screenshot-2020-05-29-at-09.31.49-300x202.png)

 Jupyter notebooks can also be launched from the main menu, under Utilities, as shown below.

![](images/Screen-Shot-2019-06-27-at-14.16.01-211x300.png)

To create a notebook, it is necessary to enter:  
  

1. The dataset(s) needed for the analysis. 
2. The owner of the Jupyter notebook. Jupyter notebooks are saved back to openBIS as datasets, and these belong either to an Experiment/Collection or to an Object. The owner is the Experiment/Collection or Object where the notebook should be stored.
3. The directory name. This is the name of the folder that will be created on the JupyterHub server.
4. Notebook name. This is the name of the Jupyter notebook

![](images/jupyter-1024x316.png)

Jupyter notebooks can also be opened from a _Project_, _Experiment_, _Experimental Step_ choosing the corresponding option in the **More** drop down menu. When opening notebooks from an _Experiment_ or _Experimental Step_, all connected datasets are automatically selected. 

##   
Overview of Jupyter notebook opened from openBIS.

  
The Jupyter notebook opened from the openBIS interface contains some pre-filled cells. All cells need to be run. The information of two cells should be modified: Name of the dataset where the notebook will be stored and Notes (in red below).

![](images/jupyter-1.png)

If you get this message "_Session is no longer valid. Please login again_" replace the code in the cell after _Connect to openBIS_ with the following:

![](images/Screenshot-2020-05-29-at-09.22.51-1024x206.png)

Enter your username in the cell and when you run the cell, you will be prompted to enter your password. 

If you are running the latest JupyterHub version released in July 2021 (available at [https://hub.docker.com/u/openbis](https://hub.docker.com/u/openbis)) you do not need to enter username and password, as authentication uses the openBIS session token. If your session token is not renewed you can enter it manually, as shown below:

             ![](images/Screenshot-2021-08-12-at-15.55.42.png)

The session token can be copied from the **User Profile** under the **Utilities** Main Menu in the ELN.

Your script should be written in the section named _Process your data here_, that contains one empty cell (see below). You can, of course, add additional cells.

![](images/jupyter-2-1024x470.png)

After the analysis is done, the notebook can be saved back to openBIS, by running the last few cells which contain the information about where the notebook will be stored (as shown below).

![](images/jupyter-3-1024x514.png)

A JupyterLab openBIS extension is also available: [JupyterLab openBIS extension](https://www.npmjs.com/package/jupyterlab-openbis)

This enables connectivity between JupyterLab and openBIS.
