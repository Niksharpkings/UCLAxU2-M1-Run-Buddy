### Git Bash:

**command-line interface (CLI)** or **terminal** -> Git Bash

`pwd` command stands for "print working directory." **print** refers to displaying something to the screen

`ls`. This command lists the files and folders within the current directory. If `pwd` is like asking, "Where am I?" then `ls` is like asking, "What's here?"

`cd <directory-name>` command allows you to move in and out of directories.

`cd ..` took us back a level (or "up" a directory).

`mkdir <directory-name>` command creates a new folder.  `mkdir` `<NameTheFolder>`

`rmdir` `<NameTheFolder>` command removes a folder.

`clear` clears everything in the CLI screen

`touch <file-name>` command creates a new file.

`rm` `<NameTheFile>` command removes a file.

`rm -rf` `<NameTheFolder>` command removes a folder.

`rm -R` `<NameTheFolder>` command removes a folder and its contents.

`mv` `<NameTheFile>` `<NameTheNewFile>` command moves a file.

`mv` `<NameTheFolder>` `<NameTheNewFolder>` command moves a folder.

`cp` `<NameTheFile>` `<NameTheNewFile>` command copies a file.

`cp` `<NameTheFolder>` `<NameTheNewFolder>` command copies a folder.

`cp` command copies files and directories.

`cp` `<source>` command copies files and directories.

`cp` `<source>` `<destination>` command copies files and directories.

`cp` `<source>` `<destination>` `<source>` command copies files and directories.

`cp` `<source>` `<destination>` `<source>` `<destination>` command copies files and directories.

`cat` `<NameTheFile>` command prints the contents of a file to the screen.

`echo` `<NameTheString>` command prints a string to the screen.

`echo` `<NameTheString>` `>` `<NameTheFile>` command prints a string to a file.

`echo` `<NameTheString>` `>>` `<NameTheFile>` command appends a string to a file.

`>` redirects the output of a command to a file. `>` `<NameTheFile>`

`>>` appends the output of a command to a file. `>>` `<NameTheFile>`

`<` redirects the input of a command from a file. `<` `<NameTheFile>`

`|` redirects the output of a command to the input of another command. `|` `<NameTheCommand>`

`>` and `>>` are called **redirection operators**. They redirect the output of a command to a file.

`<` is called a **redirection operator**. It redirects the input of a command from a file.

`|` is called a **pipe**. It redirects the output of a command to the input of another command.

`git init` command creates a new Git repository.

`git init` `<NameTheRepository>` command creates a new Git repository with the specified name.

`git status` command shows the status of changes as untracked, modified, or staged.

`git add` command stages files, preparing them to be committed to the repository.

`git commit` command permanently stores file changes in the repository.

`git log` command shows a list of all previous commits.

`git diff` command shows the difference between the working directory and the staging area. command shows the difference between the staging area and the most recent commit. command shows the difference between the working directory and the most recent commit.

`git checkout` command restores a file to a previous version.

`git reset` command un-stages files that were previously staged. command undoes commits and erases the changes made in them. command erases all commits after the specified commit, preserving changes locally.

`git remote` command manages set of tracked repositories. command shows all remote URLs next to their corresponding short names. command adds a new remote repository. command renames a remote. command removes a remote repository.

`git push` command sends committed changes of master branch to your remote repository. command sends commits of any branch to your remote repository. command sends all branches to your remote repository.

`git pull` command fetches and merges changes on the remote server to your working directory.

`git clone` command makes a copy of an existing Git repository from a particular URL.

`git branch` command lists all the branches in your repository. command creates a new branch. command renames a branch. command deletes the specified branch.

`git merge` command merges the specified branch’s history into the current branch.

`git stash` command temporarily stores all the modified tracked files.

`git tag` command lists all the tags in your repository. command creates a new lightweight tag. command creates an annotated tag. command deletes the specified tag.

`git config` command gets and sets repository or global options. command gets and sets the author name to be used for all commits by the current user. command gets and sets the author email to be used for all commits by the current user.

`git help` command shows a list of all the available Git commands. command shows documentation for a particular command.

`git show` command shows the metadata and content changes of the specified commit.

`git stash` command temporarily stores all the modified tracked files.

`git stash list` command lists all stashed changesets.

`git stash apply` command restores the most recently stashed files.

`git stash drop` command discards the most recently stashed changeset.

`git stash pop` command restores the most recently stashed files and discards the changeset from the stash list.

`git stash clear` command discards all stashed changesets.

`git stash branch` command creates and checks out a new branch named `<branch>` and restores the most recently stashed files on it.

`git stash save` command stashes the modified tracked files in preparation for a clean working directory.

`git stash save` `<message>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash show` command shows the metadata and content changes of the specified stashed changeset.

`git stash show` `-p` command shows the metadata and content changes of the specified stashed changeset.

`git stash show` `-p` `<stash>` command shows the metadata and content changes of the specified stashed changeset.

`git stash show` `<stash>` command shows the metadata and content changes of the specified stashed changeset.

`git stash apply` `<stash>` command restores the specified stashed changeset.

`git stash drop` `<stash>` command discards the specified stashed changeset.

`git stash branch` `<branch>` `<stash>` command creates and checks out a new branch named `<branch>` and restores the specified stashed changeset on it.

`git stash push` command stashes the modified tracked files in preparation for a clean working directory.

`git stash push` `-m` `<message>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash push` `-m` `<message>` `<pathspec>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash push` `<pathspec>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash create` command stashes the modified tracked files in preparation for a clean working directory.

`git stash create` `<message>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash create` `<message>` `<pathspec>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash create` `<pathspec>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` `-m` `<message>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` `-m` `<message>` `<commit>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` `<commit>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` `-m` `<message>` `<tree>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` `<tree>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` `-m` `<message>` `<parent>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` `<parent>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` `-m` `<message>` `<tree>` `<parent>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` `<tree>` `<parent>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` `-m` `<message>` `<tree>` `<parent>` `<pathspec>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` `<tree>` `<parent>` `<pathspec>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` `-m` `<message>` `<tree>` `<parent>` `<author>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` `<tree>` `<parent>` `<author>` command stashes the modified tracked files in preparation for a clean working directory.

`git stash store` `-m` `<message>` `<tree>` `<parent>` `<author>` `<committer>` command stashes the modified tracked files in preparation for a clean working directory.

`git commit --amend` command amends the most recent commit.

`git commit --amend` `-m` `<message>` command amends the most recent commit.

`git commit --amend` `-m` `<message>` `<file>` command amends the most recent commit.

`git commit --amend` `<file>` command amends the most recent commit.

`git commit --amend` `-m` `<message>` `<file>` `<file>` command amends the most recent commit.

`git commit --amend` `<file>` `<file>` command amends the most recent commit.

`git commit --amend` `-m` `<message>` `<file>` `<file>` `<file>` command amends the most recent commit.

`git commit -m "Initial commit"` command commits all staged changes.

`git commit -m "Initial commit"` `<file>` command commits all staged changes.

`git commit -m "Initial commit"` `<file>` `<file>` command commits all staged changes.

`git commit -m "Initial commit"` `<file>` `<file>` `<file>` command commits all staged changes.

`explorer .` command opens the current directory in Windows Explorer.

`explorer` `<path>` command opens the specified directory in Windows Explorer.

`explorer` `<path>` `<path>` command opens the specified directory in Windows Explorer.

`code .` command opens the current directory in Visual Studio Code.

`code` `<path>` command opens the specified directory in Visual Studio Code.

`echo %PATH%` command displays the current value of the PATH environment variable.

`echo` `<string>` command displays the specified string.

`@echo off` command disables command echoing.

`@echo on` command enables command echoing.

`q` command quits the current command prompt.

`exit` command quits the current command prompt.

---

### HTML

HTML (Hypertext Markup Language)

`<!DOCTYPE html>`  Tells the browser to interpret as a HTML documen
`<html lang="en">` Represents the root of an HTML document and tells the browser that the language of the document is English
`<head>`  Start of the head element tag. Contains information about the document for the browser, but not the content mportant to include because it specifies the range of characters (letters, numbers, symbols, etc.) that can be used.
`<meta charset="UTF-8" />` Tells the browser to use the UTF-8 character set. charset' meta element should be the first thing in '`<head>`'. UTF-8 accommodates just about any character, from foreign language symbols to emojis.
`<meta name="viewport" content="width=device-width, initial-scale=1.0" />`  Tells the browser to use the device's width as the width of the page, and to scale the page to fit the device's width
`<title>Run Buddy</title>`  The title of the document, which is displayed in the browser's tab
`</head>`  Ending of the head element tag
`<body>`  Contains and/or displays the content of the document

# `<h1>RUN BUDDY</h1>`  "level 1" heading element

## `<h2>RUN BUDDY</h2>`  "level 2" heading element

### `<h3>RUN BUDDY</h3>`  "level 3" heading element

#### `<h4>RUN BUDDY</h4>`  "level 4" heading element

##### `<h5>RUN BUDDY</h5>`  "level 5" heading element

###### `<h6>RUN BUDDY</h6>`  "level 6" heading element

What We Do What You Do Your Trainers Reach Out  text in the body element
`</body>`  Ending of the body element tag
`</html>`  Ending of the html element tag

![1676106168140](image/Class-Notes/1676106168140.png)

`<div>` elements here, which are like containers, to hold relevant information together. stands for "content division."

`<section>` element tag  represents a generic standalone section of a document, which doesn't have a more specific semantic element to represent it. Sections should always have a heading, with very few exceptions.