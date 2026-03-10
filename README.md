# CS4412_Spring26_Project
This project is aimed toward an analysis of a dataset of 24 million Google reviews. This project aims to answer three interrelated discovery questions, two of which are related to discovering groups of reviewers and businesses respectively. The last asks which users and restaurants exhibit anomalous behavior.

Link: https://mcauleylab.ucsd.edu/public_datasets/gdrive/googlelocal/
How to use:
Fork this project in Pycharm. Under the project folder create a new directory called Data. Download the data and metadata files from the link provided in order to use the scripts within the Jupyter Notebook.

Setup and Usage Guide
Follow the steps below to fork the project, download the dataset, and be able to run the scripts within the Jupyter Notebook.

1. Fork the Repository
\* Navigate to the project's GitHub repository in your web browser.
\* Click the Fork button in the top-right corner of the page.

2. Clone the Fork to Your Computer
\* Open PyCharm.
\* Select Get from Version Control (or go to VCS → Get from Version Control).
\* Copy the URL of your forked repository from GitHub.
\* Paste the URL into the Repository URL field.
\* Choose a local directory where the project will be stored.
\* Click Clone.
\* PyCharm will download the repository and create a local project directory.

3. Create the Data Directory
Inside the project folder:
\* Right-click the project root in the Project panel.
\* Select New → Directory.
\* Name the folder: *Data*

4. Download the Dataset

\* Open the dataset page:
https://mcauleylab.ucsd.edu/public_datasets/gdrive/googlelocal/
\* Download the required data files and metadata files.
\* Move all downloaded files into the Data directory you created in the project.

5. Install Required Python Packages
\* Before running the notebook, install the dependencies listed in the requirements.txt.
    pip install -r requirements.txt

6. Open and Run the Notebook
\* In PyCharm, locate the .ipynb notebook file in the project.
\* Open the notebook.
\* Ensure the Python interpreter is set correctly.
\* Run the notebook cells sequentially.
\* The scripts will load data from the Data folder and perform the analyses defined in the notebook.
\* *Note, a few of these scripts will require 20GB of RAM to run. Run this on the K-Core dataset from the download page if your computer is not powerful enough and you still wish to run the scripts*
