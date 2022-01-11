'''
Creating conda env
'''
conda create -n wineque python=3.7 -y
'''
requirements.txt
'''
pip install -r requirements.txt
git init
dvc init
dvc add data_given/winequality.csv
git add .
git commit -m "first commit"Sonetel@24
'''
