1\. create a vscode virtual environment

**python -m venv mlp**



2\. activate environment

**mlp\\Scripts\\activate**



3\. install required packages by using 

**pip install pandas numpy matplotlib seaborn scikit-learn joblib streamlit**



4\. create requirements.txt file

**pip list**

This shows all installed libraries and their versions.

**pip freeze > requirements.txt**

This will create a requirements.txt file in your current directory with exact versions of all installed packages.



5\. Dump dataset into environment 



6\. Make README.md file



7\. create a file for model training 

**model\_training.ipynb**



8\. write line by line code for data preprocessing and model training



9\. Save model and scaler after training and evaluation 



10\. create a python file to check model is valid or not

**python model\_check.py**



11\. Create a app.py file with entire code



12\. Run file by using this

**streamlit run app.py**



13\. create a repository in GitHub



14\. push all the code in local to GitHub

**echo "# Testing\_project" >> README.md**

**git init** 

**git add .**

**git commit -m "Initial commit: added Streamlit app and models"**

**git remote add origin  https://github.com/Amitmakode/Testing\_project.git**

**git branch -M main**

**git push -u origin main**





git init

git add .

git commit -m "Initial commit"

git remote add origin https://github.com/yourusername/repo.git

git branch -M main

git push -u origin main



15\. create a streamlit account and authenticate with your GitHub account



16\. copy app.py file's url from GitHub and paste into streamlin 



17.follow deployment procedure for app



























