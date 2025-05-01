# Jan 2025, Python Labs by Kannan Singaravelu

Note: `Python Labs` are designed to be a hands-on learning experience and are not meant to replace learning Python from the basics. These labs require a basic understanding of Python programming. If you are new to Python, please refer to the Python primers for foundational knowledge. Please note that the tools and approaches used in the labs may differ from the primers, as the labs are more practical and hands-on.

The labs are intended to be run in a virtual environment using Python 3.10. We will be using `uv` to create and manage the virtual environment. `UV` is an extremely fast Python package and project manager, written in Rust. For more information, visit `https://docs.astral.sh/uv`.  Follow the steps below to set up the environment, activate it, and install the required libraries.


## Steps to set up the environment and install the required libraries
1. Installing uv                            
    `pip install uv`

2. Create a virtual environment with Python 3.10 
    Note: Use a virtual environment with Python 3.10 for this program.
    `uv venv --python 3.10`

3. Activate the virtual environment
    `source .venv/bin/activate`

4. Specify required python libraries in requirements.txt

5. Install required python libraries 
    `pip install -r requirements.txt`

6. Download & Install Visual Studio Code
    `https://code.visualstudio.com/download`    
    Note: you will need to install appropriate microsfot extensions for python, jupyter including pylance, etc.

7. Open the notebooks, use any of the following methods:
    a. Use the command `code .` to launch Visual Studio Code from the terminal.
    b. Use the command `jupyter lab` to launch Jupyter Lab from the terminal.

8. When you are done with the lab, close the Jupyter Lab and exit the virtual environment.
    `deactivate` from the terminal.


Important: Please note that the virtual environment is only active for the duration of the session. If you wish to use the virtual environment for other purposes, you will need to activate it again. Python Labs are designed to be run in a virtual environment, and you should not install any libraries outside of it. The Python Labs content is shared as HTML files for you to replicate the labs in your own environment. It will not be shared as `.ipynb` files, as this aligns with good software engineering practices.
