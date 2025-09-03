# Python Workshop 2025
This workshop introduces the fundamentals of Python programming and demonstrates how it can be used across different domains. There are three Jupyter notebooks for this workshop:

1. `python_workshop_examples.ipynb` - Contains examples and demonstrations used during the workshop.
2. `python_workshop_tasks.ipynb` - Contains tasks for people to practice.
3. `python_workshop_solutions.ipynb` - Contains solutions to the tasks.


## Instructions

### Using uv

1. Install `uv` if not already installed:

    Linux, macOS, Windows (WSL)
    ```bash
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```
    Windows (Powershell)
    ```powershell
    powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
    ```

2. Install dependencies:

    ```sh
    uv sync
    ```
2. Launch Jupyter Notebook:

   ```bash
   uv run jupyter notebook
   ```
3. Open any of the three notebooks and run the cells.

### Using Google Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Either paste this repo link https://github.com/compsci-adl/python-workshop-25 or manually upload the notebook you want to use (`.ipynb` file).
3. Run each cell in order to practice or see solutions.