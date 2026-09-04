# Introduction to Pandas and Numpy

This repository introduces Pandas and NumPy, the two libraries that anchor most data work in Python. Working through the notebooks, you will load tabular and array data, transform and combine it, run a small exploratory analysis, and produce basic plots.

## Learning Objectives

By the end of this repository, you should be able to:

- Explain why Pandas and NumPy are foundational tools for data scientists
- Use Pandas DataFrames and NumPy arrays to load, inspect, and transform data
- Combine datasets with concatenation, merges, and joins
- Perform exploratory data analysis (EDA)
- Produce basic plots to surface patterns and communicate findings
- Work with date and time data using Pandas datetime functionality

## Learning Path

The modules build on each other in order.

### 1 - Pandas

Core Pandas: DataFrames, selection, visualization, and a first end-to-end EDA.

| File                                                                                           | Description                                                                      |
| ---------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- |
| [**01 - Introduction To Pandas**](1_Pandas/01_Introduction_to_Pandas.ipynb)                   | First contact with `Series`, `DataFrame`, indexing, and `.loc` / `.iloc` |
| [**02 - Pandas Practice Functionalities**](1_Pandas/02_Pandas_Practice_Functionalities.ipynb) | Hands-on exercises on selection, filtering, and aggregation                      |
| [**03 - Introduction To Visualization**](1_Pandas/03_Introduction_to_Visualization.ipynb)     | Basic plotting with Pandas and Matplotlib                                        |
| [**04 - More Pandas Practice**](1_Pandas/04_More_Pandas_Practice.ipynb)                       | Deeper practice on transformations and visualizations                            |
| [**05 - Even More Pandas Practice**](1_Pandas/05_Even_More_Pandas_Practice.ipynb)             | An end-to-end EDA exercise on a real dataset                                     |

### 2 - Numpy

NumPy arrays and vectorized numerical operations.

| File                                                                      | Description                                             |
| ------------------------------------------------------------------------- | ------------------------------------------------------- |
| [**01 - Introduction To Numpy**](2_Numpy/01_Introduction_to_Numpy.ipynb) | NumPy arrays, dtypes, shapes, and vectorized operations |
| [**02 - Numpy Practice**](2_Numpy/02_Numpy_Practice.ipynb)               | Exercises on slicing, broadcasting, and reductions      |

### 3 - More Pandas

Datetime handling, combining DataFrames, and a last practice.

| File                                                                            | Description                                              |
| ------------------------------------------------------------------------------- | -------------------------------------------------------- |
| [**01 - Datetime**](3_More_Pandas/01_Datetime.ipynb)                           | Parsing, resampling, and working with date and time data |
| [**02 - Combining Dataframes**](3_More_Pandas/02_Combining_Dataframes.ipynb)   | Concatenation, merges, and joins                         |
| [**03 - The Last Pandas Practice**](3_More_Pandas/03_The_Last_Pandas_Practice.ipynb) | Last Pandas exercises bringing the topics together       |

### Additional Folders and Files

| File / Folder                             | Description                                                                                                      |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| [**Live Session**](Live_session.ipynb) | Notebook used during the live coding session                                                                     |
| [**Data**](data/)                           | CSV datasets used by the notebooks (`abalone`, `bike_share`, `iris`, `seattle-weather`, `winequality`) |
| [**Assets**](assets/)                       | Images embedded in the notebooks|
| [**Solutions**](solutions/)                   | Worked solutions to the exercises in the notebooks|
| [**pyproject.toml**](pyproject.toml) | Project configuration and dependencies |
| [**uv.lock**](uv.lock) | Reproducible dependency lock file |

## Setup

> [!NOTE]
> Throughout these steps, text in angle brackets like `<repo-name>` is a
> **placeholder**. Replace it including the `< >` brackets with your own
> value. For example, `cd <repo-name>` becomes `cd my-pandas-project`.

### 1. Create the Repository from the Template

Click **Use this template** on GitHub.

When creating the repository:

- Set yourself as the **Owner**
- Choose a repository name
- Disable **Include all branches**
- Click **Create repository**

> [!IMPORTANT]
> If you are working in pairs or groups, only **one person** should complete this step.

---

### 2. Add Collaborators (Pairs/Groups Only)

If working with teammates:

1. Open the repository on GitHub
2. Go to **Settings → Collaborators**
3. Add your teammates as collaborators
4. Share the repository link with your team

---

### 3. Clone the Repository

Copy the SSH URL from the **Code** button on GitHub, then run:

```bash
git clone <copied-ssh-url>
```

The copied SSH URL will look like:
`git@github.com:<your-username>/<repo-name>.git`.

---

### 4. Move into the Project Folder and Install Dependencies

This installs all dependencies and creates a virtual environment in `.venv/`.

```bash
cd <repo-name>
uv sync
```

---

### 5. Open the Notebooks

> [!NOTE]
> Open VS Code from the project root so it detects the environment created by `uv sync`.

Launch VS Code in the project root:

```bash
code .
```

Then open a notebook and select the Python environment created by `uv sync` as the kernel.

## References & Further Reading

- [**10 Minutes To Pandas**](https://pandas.pydata.org/docs/user_guide/10min.html): Official short introduction for new pandas users.
- [**Pandas Getting Started Tutorials**](https://pandas.pydata.org/docs/getting_started/intro_tutorials/index.html): Task-focused official tutorials covering loading, selecting, plotting, and combining data.
- [**NumPy Quickstart**](https://numpy.org/doc/stable/user/quickstart.html): Official primer on arrays, shapes, and vectorized operations.
- [**Python Plotting With Matplotlib (Real Python)**](https://realpython.com/python-matplotlib-guide/): A clear, practical guide to Matplotlib's figure/axes model and its integration with pandas.
- [**Kaggle Learn Pandas**](https://www.kaggle.com/learn/pandas): A free hands-on course that applies pandas to real datasets.
