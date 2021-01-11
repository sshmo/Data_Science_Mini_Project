# Data Science Mini Project

There are 2 questions in this mini project:
  
 1. [blu Marketting](https://github.com/sshmo/Data_Science_Mini_Project/tree/master/blu%20Marketing): Given the fact that transportation costs is an important factor for clients, provide guidlines for clients transportation.
    
 2. [Movie Database](https://github.com/sshmo/Data_Science_Mini_Project/tree/master/Movie%20database): query a database for somespecific questions.

## How to run

Step 1 — clone the repo:
  
    mkdir data_project
    cd data_project
    git clone https://github.com/sshmo/Data_Science_Mini_Project.git .

Step 2 — Set Up Python
    
    sudo apt update
    sudo apt install python3-pip python3-dev
    
Step 3 — Create a Python Virtual Environment for Jupyter

    sudo -H pip3 install --upgrade pip
    sudo -H pip3 install virtualenv
    mkvirtualenv data
    workon data
    
Step 4 — Install requirements

    pip3 install -r requirements.txt
  
Step 5 — Run Jupyter Notebook
        
    jupyter notebook

Step 6 — Open the files in Jupyter
        
    open the file ./blu Marketting/blu_Marketting.ipynb for blu Marketting project
    open the file ./Movie database/Movie_database.ipynb for Movie database project
