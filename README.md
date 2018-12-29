# How to clone a repo
What does this mean? Cloning a repo just means copying the folder (repo) on to your desktop.
```
// Command syntax 
git clone [link]

// Example
git clone https://github.com/Gonzalo8642/git.git 
```

# How to pull updates
What does this mean? Pulling means to get any updates from the master repo.
We do this using the pull command.
```
// Command syntax 
git pull

// Example
git pull
```
# How to commit a change
What does this mean? How to upload your change to the master file.
First we must add all files that have been edited. To do this we use the add command.
```
// Command syntax
git add [file name/wildcard]

// Example. This adds all files
git add *
```
Now that our files have been added we have to add a comment explaining what our edit does. 
For this we use the commit command.
```
// Command syntax
git commit -m '[explaining what my edit does]'

// Example of a commit after we added an html page
git commit -m 'Added landing_page.html and updated index.html documentation'
```
