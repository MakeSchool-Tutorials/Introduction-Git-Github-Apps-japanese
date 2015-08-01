---
title: "Branches"
slug: branches
---

Branches are a way to create another copy of your source code, so that you can modify it without having to worry about the changes affecting the original version.

Git is clever in the way it structures your files and changes. It's so clever, in fact, that creating a new branch actually just requires creating a very small (41 byte!) file in your file system. That way branching is very fast and doesn't actually involve any copying.

#master and dev

Because branching is such an easy and fast operation, it's very common for developers to have many branches. Often in large projects each new feature or bug fix will get its own branch, which once completed, will be merged back in to the main (master) branch.

However, we're just getting started, so instead of worrying about creating many branches, let's just worry about two. It's very common to have a `master` branch, which only contains working builds, and a `dev` branch in which you add features and fix bugs. Only once the features and bugfixes are completed should they then be merged back into the `master` branch.
