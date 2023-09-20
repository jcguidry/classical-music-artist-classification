<p align="center">
  <img src="./assets/classical-music.jpg" />
</p>

# Music Classification Mini-Project

Given Midi music files, predict the artist.

## Project Objective

The primary aim of this project is to build a machine learning classifier capable of identifying whether a given MIDI file was composed by one of four classical composers: Bach, Beethoven, Schubert, or Brahms. The classifier should be able to process audio data in intervals of 15, 30, or 60 seconds, with a default setting of 30 seconds.

## Data

The dataset consists of several hundred annotated MIDI files, corresponding to compositions from the four composers. The data is provided in `data/raw/training/` and is originally sourced from [Musicnet](https://arxiv.org/pdf/1611.09827.pdf).

### Data Format

- MIDI files
- Composition name precedes the first underscore in the file name
- Composition artist (target) is given in as the parent folder name

## Solution, Methods, and Results

- For an overview of the problem, solution, methods, and results, please see the [project presentation](composer-classification-presentation.pdf).
- For specific details on the implementation, please see the Jupyter Notebooks for [data creation and preprocessing](./notebooks/01_datacreation.ipynb) and [model training and evaluation](./notebooks/02_training.ipynb).
  - Alternatively, these notebooks have been as [HTML files](./notebooks/reports) to view locally.

## Quickstart Guide

1. **Clone the Repository**: Run `git clone <repository_url>` to clone the project.
2. **Run Setup Script**: Navigate to the project directory and execute `./setup.sh`. This creates a Python virtual environment named `my_venv` with proper dependencies.
3. **Activate Environment and Run Jupyter Notebook**: 
    - Option 1: Execute `source my_venv/bin/activate` followed by `jupyter notebook`.
    - Option 2: Use an IDE such as VS Code to activate the environment and run the Jupyter Notebook.
