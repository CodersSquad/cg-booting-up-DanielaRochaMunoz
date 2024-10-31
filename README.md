[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/swKMSSMl)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=16850860&assignment_repo_type=AssignmentRepo)
# Computer Graphics Booting Up

## Let's start with ModernGL

This lab stands to prepare the moderngl development environment. Below the steps and requirements for initial coding tasks. Please make sure to edit the python provided files; for dependencies, you can add the files you need.

1. Install moderngl and its dependencies
2. Make sure that the following programs run
    - [`01_hello_world.py`](./01_hello_world.py)
    - [`06_multiple_objects.py`](./06_multiple_objects.py)
    - [`09_models_and_images.py`](./09_models_and_images.py)
        - _Modify this program to change the box's texture to a correctly aligned TEC logo_
3. Document how to execute the 3 programs in the section below.

* For documentation and missing dependencies, follow these links:
    - https://github.com/moderngl/moderngl
    - https://moderngl.readthedocs.io/

## How to run your program

To run the programs on a Linux machine (Ubuntu 22.04) or on Windows, follow these steps:

### On Windows:

1. First, my teacher Obed gave us a link for the activity: [https://classroom.github.com/a/swKMSSMl](https://classroom.github.com/a/swKMSSMl). When I entered, I had to log in to GitHub Classroom.
2. After accepting the assignment, I saw that my repository was created: https://github.com/CodersSquad/cg-booting-up-DanielaRochaMunoz.
3. I tried to use the "Open in Visual Studio Code" button, but it didn’t work, so I did this:
    - I went to the GitHub page of the repository.
    - I clicked on the "Code" button and copied the HTTPS link.
    - I opened **Visual Studio Code** on my computer and selected to clone a repository. I pasted the link and it cloned the repo.
4. Now I could see all the files for the activity, including the .py scripts and the README.
5. I installed the necessary dependencies using this command in the terminal:  
   `pip install moderngl pygame PyGLM==2.7.3 numpy Pillow moderngl-window objloader`
6. For the last exercise, I searched for the images I needed, saved them in the project folder, and changed the code to use those images.

### On Ubuntu (Linux):

1. Make sure you have Python 3 and pip installed on your machine.
2. Clone the GitHub repository using this command:  
   `git clone https://github.com/CodersSquad/cg-booting-up-DanielaRochaMunoz`  
   `cd cg-booting-up-DanielaRochaMunoz`
3. Install the necessary dependencies with this command:  
   `pip install moderngl pygame PyGLM==2.7.3 numpy Pillow moderngl-window objloader`
4. Run the .py files using this command, replacing filename.py with the file you want to run:  
   `python filename.py`
5. For the file `09_models_and_images.py`, make sure the images you downloaded are in the same project folder and that the code has the correct path to those images.

## Grading Policy

- 25% - `01_hello_world.py` is running with no errors
- 25% - `06_multiple_objects.py` is running with no errors
- 25% - `09_models_and_images.py` is running with the requested change (TEC logo texture)
- 25% - Documentation on how to run your programs