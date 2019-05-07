# SINA
## Environment Setup

### Prerequisites
1. Install Anaconda
2. Install Git



### Creating the Conda Environment
1. Clone this repo by opening a terminal or comand prompt, and entering the following command:

    $ git clone https://github.com/KennyMJL/SINA
2. Navigate into the repo directory using:

    $ cd SINA

3. Run the following command to create a dedicated conda environment for this project, called "SINA":

    $ conda env create -f SINA_env.yml

### Using the Conda Environment
1. Open a terminal or Anaconda prompt (on Windows) and navigate to the repo directory, and activate the conda enviornment by running:

    $ conda activate SINA
2. With the terminal or cmd window that you used to run the last command, you should now be able to run any __python scripts__ in this repo by running:

    $ python \<path to script\>
    
    To open __Juypter notebooks__ run:

    $ jupyter notebook
    
    Jupyter will automatically open in your web browser. You can open notebooks by navigating to them through this web interface.

### Adding new packages to the Conda Environment
1. Add any additional python packages to dependencies list in 'SINA_env.yml'
2. Run:

    $ conda env update -f SINA_env.yml

    Conda will automatically install any packages in SINA_env.yml that aren't already installed.
