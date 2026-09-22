# PuppyEars.github.io

This repo has my work (Quinn Scheider), where I completed a simple data analysis in both R and Python on the public penguins dataset

## What you need to install/requirements:

Use of:
Quarto
uv
Python
R

## Rebuild the website from a clean clone

Clone the repository in a terminal using the git clone commands:

git clone https://github.com/PuppyEars/PuppyEars.github.io.git
cd PuppyEars.github.io

Then run:
uv sync

Then, within RStudio Console, run:
renv::load()
renv::restore()

Now we back in the terminal, render the website using the below command:

uv run quarto render
