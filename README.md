# Decision Theory Problems

This repository contains a collection of decision theory problems, each located within the `problems` directory. Every problem is structured within its own folder, containing a `README.md` file with a brief explanation and a Jupyter notebook with a detailed problem description and implementation. The implementations use influence diagrams, also known as decision networks ([Howard and Matheson, 1984](https://gwern.net/doc/statistics/decision/1983-howard-readingsondecisionanalysis-v1.pdf)), with the Python library [PyAgrum](https://pyagrum.readthedocs.io/).

## Problems
- [**Oil Field Purchase**](problems/oil_field_purchase): A decision-making problem where an oil company evaluates purchasing an oil field under uncertainty.

## Setup
This project uses UV as the package manager. To set up the project:

1. Install UV if you haven't already:

```shell
curl -sSf https://astral.sh/uv/install.sh | sh
```

2. Create a virtual environment and install dependencies:
 
```shell
uv sync
```

### Some relevant bibliography:

1. **Howard, R.A., Matheson, J.E., & Strategic Decisions Group**. (1983). *Readings on the Principles and Applications of Decision Analysis: General collection*. Strategic Decisions Group. ([PDF](https://gwern.net/doc/statistics/decision/1983-howard-readingsondecisionanalysis-v1.pdf))

2. **Russell, S. J., & Norvig, P.** (2021). *Artificial Intelligence: A Modern Approach* (4th ed.), Chapter 16. Pearson.

3. **Rios Insua, S., Bielza Lozoya, C., & Mateos Caballero, A.** (2002). *Fundamentos de los Sistemas de Ayuda a la Decisión*. Ra-ma.  
