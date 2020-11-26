# Exercises
Below are the exercises to perform between sessions 1 and 2.
If you have any trouble, try reading the [Git documentation](https://git-scm.com/doc) or search on the internet.
If you're really stuck on something, you can contact the trainer through teams.

## Exercise 1: Your own git repositories
In this excercise, you will work with your own local repository and perform basic actions to version your files. Then we'll take a quick look at how to work with a .gitignore file and finally we'll set up another (linked) repository.

### 1.1 Init, branches and commits ([hints](./Hints/Exercise-1-1.md))
1. Initialize a repository (repo A)
2. Create a file a file named "README.md" with some text in it
3. Add the text file to the index (stage the changes)
4. Commit the changes
5. Create a branch "exercise-1-1" and switch to it
6. Create a text file with "Exercise 1.1" in it
7. Stage the changes
8. Commit
9. Add the word "edited" to the text file and commit again
10. Merge the branch into master

### 1.2 .gitignore ([hints](./Hints/Exercise-1-2.md))
1. Make a branch "exercise-1-2" and switch to it
2. Add a .gitignore file that ignores .png and .jpg files
3. Add some images with these extensions and another text file with "Exercise 1.2" in it to your working folder
   - Tip: Use `git add .` to stage all files at once.
4. Add and commit a file with .jpg extension without changing the .gitignore file
5. Merge the branch into master

### 1.3 Remotes ([hints](./Hints/Exercise-1-3.md))
1. Clone the repository to a different folder (repo B)
2. Check the status, there should be no local changes and 
3. Make a branch "exercise-1-3" (in repo B) and switch to it
4. Add a text file containing "Exercise 1.3" and commit it
5. Push the branch (set the upstream like is hinted)
6. In repo A, merge the branch into master
7. In repo B, switch to master and check the status
8. Do a fetch and check the status again
9. Do a pull and check the status again

### 1.4 Tagging ([hints](./Hints/Exercise-1-4.md))
1. Add a text file containing "Exercise 1.4" and commit it
2. Tag the most recent commit with a tag named "final"

### 1.5 Pushing ([hints](./Hints/Exercise-1-5.md))
1. Get the url to your repo at [GitHub](https://github.etc)
2. Set the remote of repo A to your repo
3. Push repo A to GitHub (you'll need -f or --force to overwrite the existing repository)

## Exercise 2: Forking and contributing ([hints](./Hints/Exercise-2.md))
In this exercise, you will fork this exercises repo and contribute to it though a Pull Request.
*The repo might have been forked for you automatically when you joined the organization on GitHub. In this case, you can skip step 1.*

1. Fork the main repo
2. Add a branch with your first name
3. Add a file named <NAME>.md to the "Exercise 2" folder with a URL to your repo
4. Commit it
5. Create a PR from your branch to the repo
