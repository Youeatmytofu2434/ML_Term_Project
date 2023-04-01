- Move to your desired folder using COMMAND PROMPT/GIT BASH
- Clone ML term project using: 
	- git clone https://github.com/Youeatmytofu2434/ML_Term_Project.git
- Move to the cloned folder: 
	- cd ML_Term_Project
- Create a virtual environment: 
	- python3 -m venv . 
	- or python -m venv depending on your python setup
- MUST ACTIVATE the newly created virtual environment:
	- source Script/activate ( if you're using Git Bash )
	- .\Scripts\activate ( if you're using CMD )
- Update pip version:
	- python.exe -m pip install --upgrade pip 
- Install all required packages:
	- pip install -r requirements.txt

DONE

NOTES:
- 'Term_Project' folder will be your main working dir
- Must ACTIVATE the venv every time you want to run a .py file using the packages installed in the venv
- To deactivate the venv: .\Scripts\deactivate ( for CMD ) or source Scripts/deactivate ( for GIT BASH )
	- Or just simply exit the CMD
- When you want to push your changes to git. Please push only the 'Term_Project' folder
	- git add Term_Project 
	- git commit -m 'message'
	- git push


