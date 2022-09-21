# `In Git's Heart`

**GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere. This tutorial teaches [GitHub](https://github.com/) essentials like repositories, branches, commits, and pull requests. For more you can go [here](https://www.w3schools.com/whatis/whatis_github.asp).**

**In order to setup git on your sandbox, your first step is going to be accessing the website and there will be an address of the form  (https://{your username}.github.io/{packagename}/), for example, the sandbox project is rendered at this address: https://sticsrpacks.github.io/sandbox/**

![Isika](https://repository-images.githubusercontent.com/124369770/d12e6800-b47a-11e9-85a3-5fe53e198d49)

---
## `How to create a repository.`

* `Install git and create a GitHub account`
* `Create a local git repository`
* `Add a new file to the repo`
* `Add a file to the staging environment`
* `Create a commit`
* `Create a new branch`
* `Create a new repository on GitHub.
`
---

**The standard key commands in order to apply the changes to the main server of GitHub are 3 core elements ↓
```shell 
(“git add .” -> ”git commit -m “NAME” -> “git push”)
```
---
## `What is Branching?`


***In simple words, an Branch is a copy of a project, which you can edit and the changes don’t apply to the original project.***

***The git branch command can be used to create a new branch. When you want to start a new feature, you create a new branch off main using git branch new_branch. 
Once created, you can use git checkout new_branch to switch to that branch.***

## `How can we address conflicts?`

Merge conflicts occur when competing changes are made to the same line of a file, or when one person edits a file and another person deletes the same file. For more information, see ''[About merge conflicts](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/about-merge-conflicts)''


`
Tip: You can use the conflict editor on GitHub to resolve competing line change merge conflicts between branches that are part of a pull request.
`

---

                                      So long! #Holbie
   ![Image](data:image/png;base64,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)