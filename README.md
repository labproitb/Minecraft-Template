# Minecraft-Template

Template repository for Tubes 1 IF2210 2021/2022. Feel free to replace this README with your own content.

## What's Inside
This template consists of:
- config folder containing all the config files (items and recipes)
- tests folder containing two sample test files (input and answer)
- main.cpp containing the sample main code
- check.cpp containing the code for checking
- makefile for compiling and testing

## Running the Makefile
Make sure you are using Linux with C++17. WSL also works if you are using Windows.
```
sudo apt-get install make g++
make all
```
Using the sample main file, it should return that 1 out of 2 tests passed.

## Adding More Tests
You can add more tests by adding more files to the tests folder. Tests consists of two files, input with "in" extension and answer with "ans" extension. Each test should have exactly one EXPORT command which exports the current inventory into an "out" file in the tests folder. Please refer to the sample tests. Checking will be done by comparing the answer file and the output file.

As the test is done by comparing the output files, you can freely use standard output in your program.

Automated testing will not work if you are using GUI (obviously).