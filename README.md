# Statistics Course and Tools

Here's a gathering of scripts and short examples that show some statistics tools and how they can be implemented in Python. This is by far not a complete gathering of any sorts and is more like a collection of ideas.

The idea is that these scripts might be eventually even useful as a course / class / for self learning. This readme describes each script and its purpose briefly. Every project is in a specific subfolder. Each subfolder should contain a readme that will describe the individual project.

## Python
Some scripts are written in Python and can simply be executed by

    python scriptname.py
    
Alternatively they can be run in ipython:

    ipython
    run scriptname.py
    
## Jupyter notebooks
Certain files with the qualifier .ipynb are Jupyter notebooks. You likely have Jupyter
installed already (or go ahead and install it). You can start the server
from the terminal by typing

    jupyter notebook
    
Now open the Jupyter file on your computer. Line by line interpretation
of the code can be done by hitting Shift+Enter in a given line. Lines that
are Python code start with an
 
    In [x]:

Here [x] is the number that is being executed and if you see a star [*] in square brackets, 
the code is currently being executed. If you run into trouble, there are 
many more good instructions on Jupyter Notebooks online.

## Tools
### MC uncertainty propagation (mc_unc_prop)
This routine shows how Monte Carlo error propagation is done and gives some examples.

## ToDos
 * 95% confidence interval plotting tool for a generic dataset, plus explanation on how it actually works