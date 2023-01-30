# 5. Introduction to Python Programming

## 5.1.1 Python Overview
   - Python is an interpreted, interactive, object-oriented programming language.
   - It was created by Guido van Rossum and released in 1991.
   - Python is an interpreted, interactive, object-oriented programming language.
   - Python supports multiple programming paradigms beyond OOP, such as procedural and functional programming.
   - Python is portable | Runs comfortably on Linux, macOS, and Windows based machines.
   - Python programming language can be used for:
     - Web development (server-side)
     - Software development
     - Mathematical use-cases
     - System scripting

## 5.1.2 Python Versions & Releases
   - Python stable releases have been coming out roughly every 6 to 18 months since 1991 and is likely to continue
   - As of version 3.9, Python will have a major new release every 12 months
   - Python versions are numbered “A.B.C” or “A.B”:
     - A is the major version number
     - B is the minor version number 
     - C is the micro version number
   - For getting more details around the latest Python releases, [click here >>](https://www.python.org/downloads/) .
   - There are two production-ready versions of Python: 2.x and 3.x.
   <p float="left">
     <img src="https://user-images.githubusercontent.com/121426292/215429126-24642115-2319-407d-a56b-f43cd0fb052e.png" data-canonical-src="https://user-images.githubusercontent.com/121426292/215429126-24642115-2319-407d-a56b-f43cd0fb052e.png" width="200" height="100" />
     <img src="https://user-images.githubusercontent.com/121426292/215431448-5a882e8c-1052-4c9a-a289-77a652e3ad89.png" data-canonical-src="https://user-images.githubusercontent.com/121426292/215431448-5a882e8c-1052-4c9a-a289-77a652e3ad89.png" width="200" height="100" />
   </p>
     The recommended version is 3.x, which is supported by most widely used libraries.<br/>
     Note: Although 2.x is still widely used, it is not maintained anymore.
   
## 5.1.3 Python Installation and Setup
   - [Download the latest Python runtime version and Install](https://www.python.org/downloads/)
   - Download and Install any IDE (PyCharm, Visual Studio Code, Atom, IntelliJ)
   - [Download and Install Azure Functions Core Tools](https://learn.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=v4%2Clinux%2Ccsharp%2Cportal%2Cbash#install-the-azure-functions-core-tools)
   - [Download and Install the Azure CLI version 2.4 or later](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli)

## 5.1.4 Python Syntax
   - Python uses indentation for blocks, instead of curly braces.
   - Both tabs and spaces are supported, but the standard indentation requires standard Python code to use four spaces.
   ```x = 1
      if x == 1:    
          # indented four spaces    
          print(“X value is 1”)
   ```
   - The number of spaces is up to the programmer, the most common use is four spaces | it has to be at least one.
   
## 5.1.5 Python Comments
   - Comments can be used to explain Python code logic and in order to make it more readable.
   - Comments are ignored by the interpreter while executing the program.
   - Comments in Python starts with "#" | anything comes after the "#" in the same line with be considered as comments
   - Example: <br/>
     ``` # This is a commented sentence in Python```<br/>
     ``` print('Python is awesome...!')```
