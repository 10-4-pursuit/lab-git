# Solution

Complete each task. Then, follow the instructions as to what to copy and paste into the empty code block.

> **Note:** Carefully read the instructions for each task. Sometimes you will be asked to record the _command(s)_ you wrote while other times you will be asked to record the _output_ of the command you wrote.

## 1

Create a new directory called `git-lab/`. Then, navigate inside of that directory.

Copy and paste _the command(s)_ you used into the code block below.

```
cd .. // Into Pursuit Folder
mkdir git-lab
ls // To check directory was made 
cd git-lab
```

## 2

Initialize the directory as a git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
Initialized empty Git repository in /Users/gyancarlospinto/cmd_line_practice/Pursuit/git-lab/.git/
```

## 3

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)
```

## 4

Create a new file called `readme.md`. Then stage that file.

Copy and paste _the command(s)_ you used into the code block below.

```
touch readme.md
```

## 5

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	readme.md

nothing added to commit but untracked files present (use "git add" to track)
```

## 6

Add the following text to your `readme.md` file.

```
I am learning to use git.
```

Then, check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   readme.md
```

## 7

Commit your changes and include a sensible commit message. Then, check your repository's history.

Copy and paste _the command(s)_ you used into the code block below.

```
git commit -m "Learning Git"
git log
```

## 8

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
On branch main
nothing to commit, working tree clean
```

## 9

Stage your changes and then make another commit with a sensible commit message.

Copy and paste _the command(s)_ you used into the code block below.

```
git add .
git commit -m "Git Wizardry"
