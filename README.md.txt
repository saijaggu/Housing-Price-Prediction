# Housing Price Prediction

This project uses an XGBoost regression model to predict housing prices using the 1990 California census dataset.

Flask-based web application

## Tech Stack
- Python, Flask
- XGBoost, Scikit-learn, Pandas, NumPy
- Visual Studio, Postman, Git, MLflow

1. Create and Activate Virtual Environment
	Run the following commands:
		python -m venv venv
		venv\Scripts\activate
Note: If you encounter a PowerShell script execution error, allow scripts to run by:
1. Press the Windows key and search for PowerShell
2. Right-click Windows PowerShell and select Run as Administrator
	Run the command:
		Set-ExecutionPolicy RemoteSigned

2. Upgrade pip and Install Required Packages
	Run the following commands:
		python -m pip install --upgrade pip
		pip install flask xgboost pandas numpy scikit-learn matplotlib seaborn jupyterlab mlflow
3. Verify Installed Packages
	Run the following command:
		pip show flask xgboost pandas numpy scikit-learn matplotlib seaborn jupyterlab mlflow
4. Initialize Git and Push to GitHub
	Create a new repository on GitHub named Housing Price Prediction.
	Initialize Git in your project folder and commit files by running:
		git init
		git add .
		git commit -m "Initial commit"
	Add the GitHub remote repository and push the code by running:
		git remote add origin https://github.com/saijaggu/Housing-Price-Prediction.git
		git branch -M main
		git push -u origin main



	


