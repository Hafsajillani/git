### Introduction to Git

Git is a fundamental tool used in nearly every software engineering job. But what exactly is Git? Imagine using Google Docs or Microsoft Word, both of which have a really useful feature called version history. Google Docs saves a copy of your document at different points in time, allowing you to view all the copies in a version history. This feature makes it easy for you to go back to previous versions of your document or restore your document in case you mess up. Git is essentially the same thing, but for your code. It allows you to save past versions of every file in your codebase. Whenever you need to, you can view the code from the past or restore your code back to a past version. It's essentially a safety net when developing software.

![discard1](https://github.com/Hafsajillani/git/assets/103882246/6a4ea59d-a1f1-443b-bfc5-014472ae3eb1)


### Git Versioning vs. Google Docs Versioning

One big difference between Google Docs and Git is that Google Docs automatically creates versions of your documentation for you. Every once in a while, it saves a version, and you can go back to it later. But with Git, we have to create our versions manually. You might wonder why we still create our versions manually and why we can't automate this process.

- **Automation Challenges**: Git can't automatically save versions of our code like Google Docs because code often doesn't work until it's finished. Unlike documents, unfinished code can lead to errors.
- **Code Completeness**: The state of our code impacts automated versioning because we want to avoid saving incomplete or faulty code.
- **Error Prevention**: Manual versioning helps ensure code quality by allowing us to review and verify the code before saving it as a version.

  ![git7](https://github.com/Hafsajillani/git/assets/103882246/2b67fd58-3df2-47bd-8d86-d5535395c25e)


### Introduction to Git Branching

The way Git works is that it goes back to a previous version, and you start adding new versions on top of the previous version. You'll notice that in the Git history, Git starts branching off the previous version. In Google Docs, it basically takes whatever your document was at that time and then just copies it over to the current document.

- **Branching Concept**: Git creates new versions and branches by branching off the previous version. Each branch represents a different line of development.
- **Branch Navigation**: Branch names make it easy to switch between different commits or versions of your code.
- **Command Usage**: Basic Git commands for branching include **`git branch`** to list all branches, **`git checkout <branch_name>`** to switch to a branch, **`git checkout -b <new_branch_name>`** to create and switch to a new branch, and **`git merge <branch_name>`** to merge a branch into the current branch.

One important thing to note is that Git log does not show unnamed branches.

![summarygit](https://github.com/Hafsajillani/git/assets/103882246/67ee3359-1f41-4401-9c6e-707bae113597)
