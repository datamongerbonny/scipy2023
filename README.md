# scipy2023
## Python for answering geospatial questions
"mapping of interpretable urban morphology of basic urban elements as an intermediate step, to which socioeconomic patterns can then be related"

## Nebari for SciPy 2023 tutorials - Participant’s Guide 🪴

Nebari is an open source data science platform. You quickly set up and deploy an opinionated JupyterHub distribution, with built-in integrations and features for collaboration.

This guide is for SciPy 2023 tutorial participants and presenters using Nebari at scipy.quansight.dev.

✨ Tip: You can use Google Docs’ Outline on the left to jump to different sections of this document.
Get Started 💻

# Step 0: Registration (one time)
To start using Nebari, you need to register for an account using this Google Form.

You need to register only once, you can then use this username and passwords to access scipy.quansight.dev for the rest of the tutorial days, even for other tutorials that are using Nebari.

# Step 1: Sign-in to scipy.quansight.dev
Once registered, go to scipy.quansight.dev and click on “Sign in with Keycloak”:



In the authentication window that opens, enter the username and password that you set in the Registration Form, and hit “Sign In”:


# Step 2: Start your machine
The following Nebari Hub Control window should open. Click on “Start My Server”:


Select the appropriate instance for your tutorial (ask your tutorial presenter) and click “Start”:

Note: Most tutorials run well on the Small Instance. If you’re in the PyVista tutorial, you will see a third server option that you can select.


A JupyterLab window should open automatically:


# Step 3: Clone your tutorial materials
Your tutorial material is mostly hosted in a GitHub repository. You can clone the materials to your Nebari machine using the JupyterLab Git extension or through the terminal.

Ensure you’re in the root directory of your file system before cloning a repository. Your current location should look like:



Option 1: JupyterLab Git extension
On the JupyterLab window, click on the “Git” extension icon in the left sidebar, then click on “Clone a Repository”:




In the pop-up that opens, paste the link for the git repository you wish to clone, then click “Clone”. Check the instructions for your specific tutorial, or ask your tutorial presenter for this link.

Note: For some tutorials, you may need to first create your personal fork and clone the forked repository.




You should see the tutorial materials appear in your file system.
Option 2: Git CLI (from Terminal)

From the Launcher tab, open a new Terminal:



Type in git clone <link-to-remote-git-repository> and, press Enter.


You should see the tutorial materials appear in your file system:



# Step 4: Select your tutorial environment
After cloning the materials, open the corresponding folder and navigate to the tutorial notebooks.

Every tutorial has a corresponding “environment” that has already been created for you. This environment has all the packages you need to run your tutorial notebooks. 

To select the environment, click on “Kernel” in the top left corner in the notebook tab:



In the pop-up that opens, select the environment for your particular tutorial from the dropdown, and click “Select”:

If you ignore the “global-global” prefix, the environments are named after the tutorial names.



You can now run the cells in your notebook, and follow along with the tutorial!

Note: Some tutorials will have the correct environment automatically selected. If not, you need to select the correct environments manually for all the notebooks in your tutorial.
# Step 5: Close your machine (after the tutorial)
After your tutorial is complete, you can close your machine. In the menu bar, click on “File” and then “Hub Control Panel”:

In the new tab that opens, click “Stop My Server”:


Your work will be auto-saved. You can log back in anytime during the tutorial days to access your workspace. :)




## Get a copy of this repo and enter its directory.

git clone https://github.com/datamongerbonny/scipy2023.git

It should attempt to open a browser tab to the Jupyter process running on your computer, and provides some URLs in the terminal in case that doesn't work.
