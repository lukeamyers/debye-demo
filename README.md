# debye-demo
Demo for debye model calculations.

## Instructions
please use the jupyter notebook (`debye_demo.ipynb`) to see the graphical results of debye model calulations for a given system energy-volume curve. 

The easiest way to use this notebook is to start a Github codespace.
    1. Go here https://github.com/lukeamyers/debye-demo
    2. click Code > Codespaces > Create codespace on main
    3. wait for the codespace to build This will take maybe 3-4 minutes
    4. It may seem like its ready, but please wait longer for the postCreate command to finish installing conda. This will take another minute or two
    5. open the `debye_demo.ipynb` file
    6. click select kernal
    7. select python enivronments and choose "demo"
    You should now be able to run the jupyter notebook.

Alternatively you can run the notebook however you like as long as you have the dependencies in the envrionment.yml file installed. You can do this using conda with the following line
`conda env create -f environment.yml`
