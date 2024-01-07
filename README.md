# simple-python-pyinstaller-app

This repository is for the
[Build a Python app with PyInstaller](https://BuildKite.io/doc/tutorials/build-a-python-app-with-pyinstaller/)
tutorial in the [BuildKite User Documentation](https://buildkite.com/docs/).

The repository contains a simple Python application which is a command line tool "add2vals" that outputs the addition of two values. If at least one of the
values is a string, "add2vals" treats both values as a string and instead
concatenates the values. The "add2" function in the "calc" library (which
"add2vals" imports) is accompanied by a set of unit tests. These are tested with pytest to check that this function works as expected and the results are saved
to a JUnit XML report.

The delivery of the "add2vals" tool through PyInstaller converts this tool into
a standalone executable file for Linux, which you can download through BuildKite
and execute at the command line on Linux machines without Python.
