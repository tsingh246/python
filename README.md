# python
Update Anaconda navigator
conda deactivate
conda update anaconda-navigator



Change working directory for jupyter notebooks on Anaconda
jupyter notebook --generate-config
This will generate a file at C:\Users\tsingh\.jupyter
    
edit this file to uncomment and make sure the code is properly indented as per python files
    
c.NotebookApp.notebook_dir = 'C:/jupyter_notebooks'
    
