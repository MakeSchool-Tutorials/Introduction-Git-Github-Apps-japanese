---
title: "What is Git?"
slug: what-git
---

Let's get started talking about one of the most important tools a developer can learn: *Git*.

Git is a distributed version control system. When we say Git is a *version control system*, we mean that it is a tool you can use to create snapshots of your projects throughout the development process. Git is *distributed* because you can keep copies of these snapshots in multiple places. Usually we'll have one copy on our computer and another hosted somewhere like [GitHub](https://github.com/).

We use Git because we want to:

1. Have a backup copy of our projects. Hard drives die and laptops get stolen. We don't want to lose all of our work due to an unfortunate mishap.
2. Be able to see the progress we have made on projects and keep track of changes over time.
3. Share our code publicly. Keeping a portfolio of your projects can be extremely helpful when looking for a job. A lot of companies expect you to have a GitHub so they can check out your past work.
4. Be able to work with other developers all around the world. Almost all projects with more than one person rely on Git (or another *version control system*) to help organize collaboration. Employers will expect you to be familiar with Git.

You can think of Git as "Dropbox for developers".

# Why not use Dropbox?

Dropbox allows you to keep a remote copy of your projects -- why don't we just use that? When you look a bit closer, you'll realize that Dropbox only accomplishes one of our goals -- it keeps a backup copy of our projects incase of unfortunate mishaps.

There is a limited revision history but files are synced as soon as they are saved. This means its extremely hard to revert a whole project to an older version. We see changes only at the file level. Git uses *commits* to save a snapshot of the whole project all at once. We can even include messages with our commits to remind us what we changed!

Dropbox is not an ideal system for personal projects. The situation starts to look even worse when it comes to collaboration! Two people working out of the same Dropbox folder will often break each other's code as they work since files sync as soon as they are saved.

Since Git uses commits, "conflicts" (instances where you and your collaborator both changed the same code) are resolved through *merging* those commits. This allows multiple people to work without worrying about changing the same files. They know they can just resolve any differences by merging once there are at least two stable commits.

# What you will learn

In this tutorial you will get started with the very basics of Git.

You will:

1. Create a GitHub account to host your projects
2. Configure [Github Desktop](https://desktop.github.com/), a graphical interface for using Git
3. Create a *repository* for your first project
4. Create a *commit* to save your first project
5. *Push* that *commit* to a *remote repository* hosted by GitHub

Let's get you set up with Git and get your first project up on GitHub!
