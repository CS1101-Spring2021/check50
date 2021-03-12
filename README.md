# check50 [![Build Status](https://www.travis-ci.org/cs50/check50.svg?branch=develop)](https://www.travis-ci.org/cs50/check50)

check50 is a testing tool for checking student code. As a student you can use check50 to check your CS50 problem sets or any other Problem sets for which check50 checks exist. check50 allows teachers to automatically grade code on correctness and to provide automatic feedback while students are coding.

You can find documentation and instructions for writing your own checks at https://cs50.readthedocs.io/projects/check50/.

## CS1101 Specific Instructions

### Installing this check50

Uninstall the default check50 package from your device.
```sh
$ python3 -m pip uninstall check50
```

Clone this repository and don't `cd` into it. Now install this version of check50 in editable mode.
```sh
$ python3 -m pip install -e check50
```

### Pushing to the right Repo

⚠ If you clone this repository, using the script to push is not required. This is only if you cloned the original repository and added this repo as a remote named `cs1101 `.

After committing your changes, use the shell script included with the repository to push your commits to the Organisation repository.
```sh
$ bash cs1101push.sh
```
If you want, you can change the permissions of the file and run it as an executable.
