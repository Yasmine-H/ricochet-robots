# ricochet-robots
This project aims to provide a simulator of the board game "Ricochets Robot" and a set of algorithms to solve this game

## Prepare environment
At the root of the project, make a virtual environment called "venv"
> python3 -m venv venv

Activate your environment
> source venv/bin/activate

Install the required libs
> python -m pip install -r requirements.txt

Add the new kernel to your jupyter config
> ipython kernel install --user --name=venv

Launch jupyter notebook
> jupyter notebook

Open board.ipynb, make sure the selected kernel is "venv" (on the upper right, below the logout button, you should see "venv") then launch all the cells, you should see the board appear at the end of the notebook and the robots move inside it. 
