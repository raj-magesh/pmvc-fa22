# AS.050.375/675.FA22 Probabilistic Models of the Visual Cortex

This repository contains [Python](https://docs.python.org/3/tutorial/index.html) code in the form of interactive [Jupyter notebooks](https://docs.jupyter.org/en/latest/) that are meant to provide practical demonstrations of theoretical concepts discussed in class. You'll be using this code in your homework assignments!

- If you're new to programming/Python/Jupyter Notebooks, we recommend running the code on [Google Colab](https://colab.research.google.com/). Be sure to copy the data files under `homework_1/data` as well!
- If you'd prefer to run notebooks locally, we provide Conda environment files (`environment.yml`) that you can use to generate reproducible environments by running `conda create -f <path_to_environment.yml>`.

Here's a link to [the notebook for Homework 1](https://github.com/raj-magesh/pmvc-fa22/blob/main/homework_1/homework_1.ipynb)!

## Warnings!

- Colab will stop your runtime if it continues for too long, which means you may lose your work. Be sure to save your notebook often!
- If you're on a Windows machine, you might face issues with the `.data` files in HW1 due to different line endings in Linux/MacOS (LF) vs Windows (CR+LF). Do contact me if you have trouble with this!

## Guide to Homework 1

### Setting up Colab

0. Sorry, you'll need to create a Google account to use Colab.
1. Download the files in [this repository](https://github.com/raj-magesh/pmvc-fa22) by clicking the green `Code` button followed by `Download ZIP`.
2. Extract the files from the ZIP archive using whatever tool your OS provides.
3. Open a [Google Colab](https://colab.research.google.com/) instance.
4. Navigate to `File > Open notebook` (or `Ctrl+O`).
5. On the GitHub tab, enter the URL as `raj-magesh/pmvc-fa22` and click the search button.
6. Click on the `homework_1/homework_1.ipynb` link.
7. Click on the `Connect`/`Reconnect` button (top-right, next to `Editing`). This will connect your notebook to a Google server where the code will be run.
8. Click on the small folder icon on the left pane. This should open a panel on the left with a file browser interface.
9. Right-click on the file browser panel, click `New folder`, and create a new directory called `data`.
10. Right-click the `data` directory and click `Upload`, then select all the files under `homework_1/data` that you got in Step 2 after extracting the ZIP archive.
11. You are ready to run the notebook!

### Working with notebooks

The notebook contains multiple cells. Each is either a Markdown cell (plain-text documentation) or a code cell (Python, can be executed). The Markdown cells contain information that you should read through. The code cells can be run by pressing the run button on the top-left of each cell or by pressing `Ctrl+Enter` when in the cell.

For Homework 1, most of the code is written for you. These utility functions should make it easy for you to solve the assignment: your job will primarily be to evaluate the functions with different parameters and interpret the output. If you have any trouble, start a Canvas discussion, attend office hours, or email us!
