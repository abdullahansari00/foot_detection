For help refer https://www.youtube.com/watch?v=yqkISICHH-U or https://github.com/nicknochnack/TFODCourse

1. Create a new virtual environment 
python -m venv {env_name}

2. Activate your virtual environment
.\{env_name}\Scripts\activate

3. Install dependencies and add virtual environment to the Python Kernel
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name={env_name}

4. Open notebook using
jupyter notebook

Select your environment

5. Run the final.ipynb file