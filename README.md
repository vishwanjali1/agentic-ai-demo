Welcome! 👋

This repository contains  Jupyter notebooks for agentic AI. It is developed in windows machine and contains the basic steps for setting up python virtual environment

# agentic-ai-demo Setps to setup the initial environment for windows machine

# Step1 : Create Virtual enviornment

```bash
python -m venv agenticai_venv

# Step2 : Activate Virtual environment
agentic_venv\Scripts\activate

# Step3: Upgrade pip (if required)
python -m pip install --upgrade pip

# Step4: Install Requirments
pip install -r requirements.txt

# Step5 : Register kernel
ipython kernel install --user --name=agentic_venv

# Step 6: Select correct kernel in Jupyter
Change the Kernel in jupyter notebook

