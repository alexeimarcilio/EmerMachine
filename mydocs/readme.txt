
Create environment for Emeritus Machine Learning class






To begin go to the 2021MachinePortilla directory

1. deactivate the current "base" environment - need to do twice

	conda deactivate
	conda deactivate

2. Fix the prompt

	export PS1="$ "

cd ~/Desktop/Courses/


Used the conda navigator to create a new environment using the requirements.txt file.

Open terminal 
deactivate 3 times
open and pick env from Jupyter 
check 

# Create environment

# Update condo
conda update conda

# Create environment
conda create -n emeritusm python=3.9 anaconda

3. Activate the python environment

	conda activate /Users/alexeimarcilio/.conda/envs/machine_port

4. Run the jupyter notebook - to confirm it's correct use which jupyter command

	jupyter notebook

5.  In the jupyter notebook you can use the version command to check env:

	import pandas as pd
	pd.__version__

6. When you select a new notebook file the option that will appear is:

	Python [conda env:.conda-machine_port] *


Usefull Commands

conda env list
