![Tests](https://github.com/mrLennyboy/SlapThatLikeButton-TestingStarterProject/actions/workflows/tests.yml/badge.svg)
# SlapThatLikeButton-TestingStarterProject
A starter project to show how to set up and use automated testing in Python

## Notes

03-17-2022:  
Unfortunately spent 5 hours debugging my misunderstanding of Pyenv vs. system Python version paths.

https://yellowdesert.consulting/2020/10/24/tox-testing-multiple-python-versions-with-pyenv/
Insight of testing multiple python version with Pyenv, and debug of InterpreterNotFound error,  
since tutorial skips information.

https://github.com/pyenv/pyenv#understanding-path
Documentation on setup for proper Pyenv path with homebrew but used temp path for tutorial. 

https://opensource.com/article/20/4/pyenv  
To temporaryily change the PATH variable for the shell to find the version of python run by pyenv within shell instance.
```
PATH=$(pyenv root)/shims:$PATH
```
Necessary for TOX execution to create venv for different versions of python.
