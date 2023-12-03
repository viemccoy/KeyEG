# LSL P300 speller
This repository contains a P300 speller based on [LSL](https://github.com/sccn/labstreaminglayer) and tkinter.

## Installation

### Dependencies
The whole projects supports `python>=3.6.1`.

### Installing the package
Run the following to install the `bstadlbauer.p300speller` package:
```
pip install bstadlbauer.p300speller
```

## Getting Started
After installation, an entrypoint is avaibable to start the speller, just run
```
start-speller
```
and a window should open.

## Questions and Issues
If there are any questions or you run into an issue, please file a 'Issue' at the top.

## Contributing
If you want to contribute, please file also file an issue first where the new feature can be discussed, in general
contribution is welcome!

This project uses [poetry](https://python-poetry.org/) to manage its dependencies. Visit their website on how to install
poetry for you operating system.
To setup the development environment, do the following:
```
git clone https://github.org/bstadlbauer/lsl-p300-speller
poetry install
pre-commit install
```
To ensure consistent formatting and linting pre-commit hooks (managed through [`pre-commit`](https://pre-commit.com/))
are used.

# Acknowledgement
This tool was developed by myself as part of a project done at the
[Institute of Neural Engineering](https://www.tugraz.at/institutes/ine/home/).
The work was supervised by Assoc.Prof. Dipl.-Ing. Dr.techn. Reinhold Scherer.
