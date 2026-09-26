# PuppyEars.github.io

This repo has my work (Quinn Scheider), where I completed a simple data analysis in both R and Python on the public penguins dataset

## What you need to install/requirements:

Use of:
Quarto
uv
Python
R

## Rebuild the website from a clean clone

Clone the repository and enter its top-level directory:

```bash
git clone https://github.com/PuppyEars/PuppyEars.github.io.git
cd PuppyEars.github.io
```

Restore the Python environment:

```bash
uv sync
```

Restore the R environment:

```bash
R -e 'renv::restore()'
```

Render the website from the top-level directory:

```bash
uv run quarto render
```

The rendered website will be created in the `docs/` directory.

## Preview the website locally

Start a local preview with:

```bash
uv run quarto preview
```
Can also click direct link in my repo to access website
