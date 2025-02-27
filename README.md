# Public Transport Network graph modelling using GTFS data

For any questions regarding this software contact Renzo Massobrio (renzo.massobrio@uantwerpen.be)

----

## Installation

If you want to run the code locally in your computer, you need to follow these instructions.

**Support for macOS is not provided.**

1. Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html). 

2. Install dependencies:
    - **Only for Windows users**. Download the latest Microsoft Visual C++ Build Tools: 
       * You can download it from [here](https://visualstudio.microsoft.com/downloads/). 
       * In the installation options select "Desktop Development with C++". 
    - **Only for Linux users**. You need GCC compiler (in Ubuntu, install it with `sudo apt install build-essential`)
3. Create the conda environment that installs all the necessary dependencies

   - Open Anaconda Prompt (in Windows) or a terminal (Linux).

   - Move into the directory where this README file is located.
   
       * Windows: use `cd` to move to the target directory. For example, `cd C:\Users\user\Documents\repo-main`. If you have many disk partitions, you need to first move to the partition where the file is located, for example, 'D:' and then `cd D:\Documents\repo-main`.
   	
       * Linux: use the command `cd` in the terminal (e.g., `cd /home/user/repo-main`)
        
   - Run the following command: `conda env create -f environment.yml` 
   
4. Run the Jupyter notebook
   - Activate the newly created environment with the following command: `conda activate pt-networks`
   - Start a new jupyter instance with the following command: `jupyter notebook`
   - A new window will open in your web browser. Select the file notebook.ipynb from the list and start working on your networks :)
----

## Using the code

You can find a video tutorial on how to use this tool [here](https://surfdrive.surf.nl/files/index.php/s/Td4xD7GIDDefniP)
