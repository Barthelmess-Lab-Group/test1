# test1
This repo is for testing cloning and pushing to your own copy of a cloned repo

## instructions

Clone this repository using the green button, use the R Studio approach. 

- Copy the repo url
- In RStudio -
   - New Project ->
   - Version control ->
   - Git
   - Paste URL from cloned repo
 
Next, to be able to push to your own version of the repo

1. Go to github and create your own repo with the same name as this one (case sensitive and space sensitive - make it truly the same name)
2. Copy the url for YOUR version of the repo

3. Go to your RStudo project, and then to the terminal in RStudio (** Not** console)
- Run this line of code to redirect your project to your own version of the repo:

  ` $ git remote set-url origin http://github.com/YOU/YOUR_REPO` but replace the whole url with the url you copied in step 2 above

  Let me know if it works!
