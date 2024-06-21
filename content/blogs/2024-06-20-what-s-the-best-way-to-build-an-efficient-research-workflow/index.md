---
title: What's the best way to build an efficient research workflow?
author: Irene
date: '2024-06-20'
slug: what-s-the-best-way-to-build-an-efficient-research-workflow
categories:
  - Reserach
tags:
  - Boring
---

As the title indicated, I personally haven't find **THE** best way to do so. There is still a long way to go. But influenced by many people, I thing Github + Dropbox/Cluster works perfect, at least for now.

Github serves as a code hub where you can do version control and collaborate with co-authors. You can easily track all the changes on code. Dropbox or a computer cluster serves as cloud to store all the huge dataset. 

To start, you should learn basic Git command and how Git works (Git != Github): things like what is pull, commit, push; how to create branches (but usually for small project where there is only one or two persons work on the code, no need to use multiple branches), how to initiate git to a folder etc. The best tutorial is the official [Git documentation](https://git-scm.com/). There is a period for getting used to it. After that, you will fall in love with **COMMITTING** and **PUSHING**!

Another important thing is about the folder structure. Depending on the project, the structure would vary. But two core folders would be `code` and `data`. Few things to keep in mind:

1. In every code, refer any data files by their relative path instead of absolute path. This is important to ensure the code replicability (others don't need to change the path every time).
2. Everytime you work on the project, you should go to the project folder (related to 1)
3. It should usually be the case that one folder in`code` correpsonds to one folder in `data`.
4. Create documentation as you write down the code (Trust me, humans are REALLY forgetful). 
5. Also create readme file for `data` folders so that it can be detected by Git.

There is no much to say about the Dropbox and clustering. Keep in mind to set up the SSH and configure properly to access the remote (Github) safely.

Another thing I want to share is the use of command lines. It's really fast compared with interactive interface like VS-Code when performing tasks like renaming files, moving files, deleting files, unzipping files as well as transferring data from cloud to local or between cluster (e.g., WRDS Clouds to Mercury).  Learn essential command line will help a lot.

Well, no more to share. Will update if I learn anything new!!


