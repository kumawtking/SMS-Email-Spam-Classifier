# SMS-Spam-Classifier
This model can classify any SMS/Emails into Spam or Not Spam Message.

# The SMS-Spam-Classifier UI 

![image](https://user-images.githubusercontent.com/65019778/157433092-0924b807-3371-47b1-97cb-19f52ff688b8.png)

![image](https://user-images.githubusercontent.com/65019778/157433771-7fc980a1-2c6b-4f12-879e-f6cf12857888.png)



# Basic Linux Commands

conda env list

mkdir utils

touch utils/__init__.py #to treat utility as a package

touch utils/model.py

touch utils/all_utils.py (keep all helper functions in all_utils folder)

from utils.model import class

touch requirements.txt

conda create -n spam python==3.8 -y

conda activate venv

pip freeze > requirements.txt

pip install -r requirements.txt

git clone --

git add . && git commit -m "docstring updated" && git push origin main

git remote -v #shows the remote repository URL

git pull #to bring changes from remote repository and merge into local branch

git branch -M # to rename current branch

git checkout "committed id no" (to go to specific version)

pip install notebook #to install jupyter notebook in the vs code

jupyter notebook
cp sample\ notebook/demo.ipynb .

#to see utils as a pckage, just type python in the terminal

import utils

utils.__version__ #check utils package version
