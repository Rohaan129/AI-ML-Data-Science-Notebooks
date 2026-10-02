# Python for Data Science: Practice Notebooks

Hands-on Jupyter notebooks I built while learning the core Python data libraries. Each topic lives in its own folder with its notebook, the files it needs, and a README explaining what's covered.

## Topics

| Folder | What it covers |
|---|---|
| [NumPy](NumPy/) | Arrays, indexing, reshaping, broadcasting, linear algebra, random sampling, vectorization, sparse matrices, image processing |
| [Pandas](Pandas/) | Series & DataFrames, indexing (`loc`/`iloc`), missing data, merging & joining, groupby, reading & writing CSV/JSON/Excel/text, string operations, plotting |

More topics will be added as folders alongside these.

## Getting started

```bash
git clone <this-repo-url>
cd <repo-folder>
pip install -r requirements.txt
jupyter notebook
```

Then open the notebook inside the topic folder you want. Run each notebook from its own folder, because the notebooks load data files by name.

## Credits

Some examples, explanations and datasets are adapted from public tutorials, mainly GeeksforGeeks, and reworked into my own notes. Feedback and corrections are welcome. Feel free to open an issue.
