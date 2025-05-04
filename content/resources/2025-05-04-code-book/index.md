---
title: Code Book
author: Irene Tan
date: '2025-05-04'
slug: code-book
categories:
  - Resources
tags:
  - Slightly interesting
---

Often times Irene doesn't remember things so well. So, it's good to put some common codes (particularly command lines in Linux) here that she can refer to.

Log in to cluster (WRDS as an example)

```
ssh irenetan@wrds-cloud.wharton.upenn.edu
```


`>` operator directs a command's output to a file and overwrite the file. `>>` append the output to a existing file:

```
echo "Ok, this is crazy:)" > a_meme.txt
echo "Ok, this is crazy:)" > memes.txt
```

Get info about working directory

```
cd
pwd
ls -a # list all files
ls -l # list with detailed info
ls -t # sort files
ls xxx | wc -l # count the number of files in xxx directory
```

Move (rename), copy, remove 

```
mv source destination 
cp source destination 
scp file_to_copy.csv irenetan@wrds-cloud.wharton.upenn.edu:/home/folder/
rm xxx # remove a file
rm -r xxx # remove the whole folder
```

Zip and rm

```
zip -rm path_of_out_zip.zip folder_to_zip
```

There are also more for slurm or debian cluster info checking but I totally can't think of any right now.


