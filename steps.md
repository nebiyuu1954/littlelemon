////////////////////////////////////////////////////////////////////////////
///////// MODULE 1
////////////////////////////////////////////////////////////////////////////

	1, create the repo 
		1,	$ git init littlelemon
		
		2,	add the necessary starter files and  project files to the folder and check the status
				$ cd littlelemon
				$ git status
		
		3,	check your on the On branch master
		
		4,	Add the files to the staging area of the repository
				$ git add .
		
		5,	Configure the repository with relevant credentials
				$ git config --global user.email "you@example.com"
				$ git config --global user.name "Your Name"
		
		6,	Commit the files that have been added to the staging area
				$ git commit -m "first commit"
		
		7,	Create a New Repository
				Repository Name: Enter a name for your repository (e.g., littlelemon).
				Description: (Optional) Add a description of your project.
				Public/Private: Choose whether you want the repository to be public or private.
				Initialize this repository with: Do not select this option, as you already have a local repository.
		
		8,	establishes a connection between your local repository and the remote repository on GitHub. 
			After running this command, you can use other Git commands to interact with the remote repository, such as pushing your changes or pulling updates. 	
				$ git remote add origin https://github.com/username/littlelemon.git
		
		9,	$ git push -u origin master		

		using github
		
		1,	create a repo make it public
			Copy the GitHub repository URL
		
		2,	create a folder same as the repo name
				cd littlelemon
		
		3,		$ git clone https://github.com/malharSS/first-repo.git
		
		4,	Enter the repository and check the list of files.
				$ cd first-repo
				$ ls -la
				total 5
				drwxr-xr-x 1 **********4096  0Dec  209:58 ./
				drwxr-xr-x 1 **********4096  0Dec  2 09:58 ../
				drwxr-xr-x 1 **********4096  0Dec  209:58 .git/
				-rw-r--r-- 1 ********** 4096 14 Dec  2 09:58 README.md
		5, 	create and change the neccesary files
		
		6,	$ git status
		
		7,	Add the steps.md to the stage.
				$ git add newfile.txt
		
		8,	commit changes 
				$ git commit -m "updated steps.md"  
				
		9, git push -u origin master
		
		
		
	2, install all the dependecies
		
		1, pipenv install and activate pipenv shell
		
		2, pipenv install django

		3, django-admin startproject littlelemon		
		
		4, python manage.py startapp restaurant 
		
		5, important step - control+shift+p then select the python interpreter 
						  - then put in the name of your created project to restart the terminal to activate the enviroment
						  
		6, git add . (to add multiple files to the staging area)

		7, git push origin master
		




















































		