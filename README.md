# Machine Learning College

Machine learning coursework, with a separate folder for each task.

## Tasks

| Folder | Topic | Notebook |
| --- | --- | --- |
| [task1](task1/) | Medical insurance charges prediction with linear regression | [task1.ipynb](task1/task1.ipynb) |

## Structure

```text
machine-learning-college/
├── README.md
├── requirements.txt
└── task1/
    ├── README.md
    └── task1.ipynb
```

## Setup

Use Python 3.12, the version used for the current notebook.

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

Open a task notebook in VS Code with the Python and Jupyter extensions, select
the `.venv` kernel, and run the cells from top to bottom.

For JupyterLab instead:

```bash
python -m pip install jupyterlab
python -m jupyter lab
```

Task 1 downloads its dataset through KaggleHub, so its first run needs an internet
connection. Downloaded datasets and the virtual environment are not committed.

## Adding a task

Create the next numbered folder (`task2/`, `task3/`, and so on). Keep its notebook,
supporting code, and task instructions together, then add it to the task table
above. Shared Python dependencies belong in the root `requirements.txt`.
