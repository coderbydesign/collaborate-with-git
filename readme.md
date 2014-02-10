<h1>Github Collaboration</h1>

<h2>1. Getting an Existing Project on Github</h2>

* Create a github account

* Install git on your computer. `sudo install git` Or refer to <a href="http://githowto.com">http://githowto.com </a>
	
* Configure git on your computer. Make sure these correspond with your github account settings.
```git config --global user.name "Your Name"```

```git config --global user.email "your_email@whatever.com"```
	
* cd to your gem’s project root directory

* Initialize a git project in this directory `git init`

* Add all files in your project to your local git repository `git add .`

* Commit your project’s current state to git version control `git commit –m “commit notes”`

* Go to your github account and create a repo for your project to reside

* When you create the repo, you will be redirected to notes for connecting your local machine’s repo to your github repo:
```git remote add origin git@github.com:github-handle/repo-name.git```

* Push your commits to the remote repository 
```git push -u origin master```
 
