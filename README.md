# git2025

## Prerequsites for the Workshop
- [Github Account](https://github.com/signup)
- [Git](https://git-scm.com/downloads)
    - On Windows: Make sure you set "Visual Studio Code" as your editor during setup.
- [Visual Studio Code](https://code.visualstudio.com/download?ref=progsoc.org)
- [Github CLI](https://cli.github.com/)

## Link to Slides
[Google Slides](https://docs.google.com/presentation/d/143PKXZBmfM5mBy-hAxs0ZPwLcT6JNFtqtDF-v8_BnQ8/edit?usp=sharing)

## Staging Changes

When using git, there are various stages your files can be in: untracked, modified, staged and committed.

**Untracked:** New files that have been added to your project directory.

**Modified:** Files that have been edited since your last commit.

**Staged:** Files that have been marked as ready to be included in the next commit.

**Committed:** Changes have been synced with your local git repository.

**Pushed:** Changes are now synced with the remote repository and all collaborators.

## Group Work

Have a go at modifying the sample website. If you haven't used HTML before, use the link below for sample HTML syntax.


Ideas:
- Cat Newspaper
- Write some news about Superman 

[W3Schools HTML Example Syntax](https://www.w3schools.com/html/html_examples.asp)

### Managing Merge Conflicts

Merge conflicts occur when multiple people make changes to the same lines in a file.
They show you what currently exists and your incoming change and you have to resolve it manually.
Inducing a merge conflict

To learn how to resolve merge conflicts, we can force a merge conflict manually.
This can be done as a group or individually if you're just following along by yourself.


1. 2 People should each create a new branch using `git switch -c`

2. Both people should stage and commit their changes, ensuring they change the same line in different ways

3. Both people open a pull request
4. Merge one of the pull requests
5. Trying to merge using gh pr merge for the second branch should now fail.
6. The other person will be shown by GitHub CLI how to solve the merge conflict.
Once it's resolved they'll be able to merge their branch with main!


## Additional Resources
- [Pro Git](https://git-scm.com/book/en/v2)
- [Fireship Git Video](https://youtu.be/HkdAHXoRtos)
- [2024 Git Workshop](https://docs.progsoc.org/blog/2024/03/29/intro-to-git-2024/)
