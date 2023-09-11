# IDS706-Python-Template
[![CI](https://github.com/Jingzhi-cyber/IDS706-Python-Template/actions/workflows/cicd.yml/badge.svg)](https://github.com/Jingzhi-cyber/IDS706-Python-Template/actions/workflows/cicd.yml)

It sets up an environment on codespaces and uses Github Actions to run a Makefile for the following: make install, make test, make format, make lint.

Here are the descriptions of the files: 

.devcontainer includes a Dockerfile and devcontainer.json. The 'Dockerfile' within this folder specifies how the container should be built, and other settings in this directory may control development environment configurations.

workflows includes GitHub Actions, which contain configuration files for setting up automated build, test, and deployment pipelines for your project.

.gitignore is used to specify which files or directories should be excluded from version control when using Git.

Makefile is a configuration file used in Unix-based systems for automating tasks and building software. It contains instructions and dependencies for compiling code, running tests, and other development tasks.

README.md is the instruction file for the readers.

requirements.txt is to specify the dependencies (libraries and packages) required to run the project.

test_main.py is a test file for main.py that can successfully run in IDEs.

main.py is a Python file.
