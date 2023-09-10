# Solution

Complete each task. Then, follow the instructions as to what to copy and paste into the empty code block.

> **Note:** Carefully read the instructions for each task. Sometimes you will be asked to record the _command(s)_ you wrote while other times you will be asked to record the _output_ of the command you wrote.

## 1

Create a new directory called `git-lab/`. Then, navigate inside of that directory.

Copy and paste _the command(s)_ you used into the code block below.

```
mkdir git-lab/
cd git-lab/
```

## 2

Initialize the directory as a git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
Initialized empty Git repository in /Users/pursuitfellowgodoy/git-lab/git-lab/.git/
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
git add readme.md
git commit -m "updated"
```

## 5

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   readme.md
```

## 6

Add the following text to your `readme.md` file.

```
I am learning to use git.
```

Then, check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
diff --git a/readme.md b/readme.md
index e69de29..33dffdd 100644
--- a/readme.md
+++ b/readme.md
@@ -0,0 +1,2 @@
+I am learning to use git.
+
(END)

```

## 7

Commit your changes and include a sensible commit message. Then, check your repository's history.

Copy and paste _the command(s)_ you used into the code block below.

```
git add readme.md
 git commit -m "added content to readme"
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
git add readme.md
git commit -m "added an additional sentence"
git status
```
