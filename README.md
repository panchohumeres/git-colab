# git-colab
Template for implementing git version control in a Google Drive folder for working with Google Colab notebooks

### Setup
1. Download main notebook file [git.ipynb](git.ipynb) and upload it in the google drive folder where your will host the local copy of your repo. Note that yo should place it one level above the actual folder where you intend to clone your repo (i.e. if the cloned repo will be at ```path/to/repo``` place it at ```path/to/```. Open it with Google Colab.
2. **Only for the first time:** Uncomment code and follow the instructions in section **0.** of the ```git.ipynb``` notebook. Those instructions are for cloning the repo inside the google drive folder.
3. replace with your credentials in the file inside the ```credentials/``` folder, using template in the [example.py](credentials/example.py) file , and rename at is you whish (any other name will be ignored by git, so your credentials will be safe).

### Git Worklow
1. In Google Colab open the main notebook file [git.ipynb](git.ipynb) **inside** your cloned repo.
2. Work as usual inside the repo.
3. For a stantandard add-commit-push git workflow after making changes in your repo, follow instructions in the section **1.** of the main notebook file [git.ipynb](git.ipynb). Keep an eye on being consistent with respect to filename and credentials in the credentials file.
