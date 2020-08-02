This is the README file for this git repo. You will be able to find [here](README) the original file from the PARSEC distribution

This repo is based originally on distribution 3.0 from PARSEC benchmark. The original source can be found [here](https://parsec.cs.princeton.edu/)

# Cloning the repo

You can initially clone this package by performing

`git clone git@github.com:arcosuc3m/parsec.git`

## Note about large input files

This repository does not include native large scale experiments for serveral reasons. First, doing so allows to keep a repos of smaller size. Second, in many cases they are not needed during development.

If you want to use them followi the following steps:

 1. Download the compressed file from the PARSEC site. Visit the site or download this [file](http://parsec.cs.princeton.edu/download/3.0/parsec-3.0-input-native.tar.gz).
 1. Uncompress the file.
 1. Copy the contents in your PARSEC source tree.

Note that the .gitignore file of this repo already ignores all files named `input_native.tar`.