# SlapThatLikeButton-TestingStarterProject
A starter project to show how to set up and use automated testing in Python

## Notes

03-17-2022:  
Unfortunately spent 5 hours debugging my misunderstanding of pyenv vs. system

https://yellowdesert.consulting/2018/02/04/python-on-mac-one-of-the-good-ways/

https://github.com/pyenv/pyenv#understanding-path

https://opensource.com/article/20/4/pyenv  
To temporaryily change the PATH variable for the shell to find the version of python run by pyenv within shell instance.
```
PATH=$(pyenv root)/shims:$PATH
```
Necessary to for TOX execution to create venv for different versions of python.
