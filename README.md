# Teal Insights Statement of Work #1 report

The structure of the repository is based on [https://github.com/christophscheuch/isc-proposal-econdataverse](https://github.com/christophscheuch/isc-proposal-econdataverse).

The report follows a [white paper format](https://writingcenter.gmu.edu/writing-resources/different-genres/white-papers): introduction with context, problem, solution criteria, solution, recommendations, conclusions.

## One-time setup

### Prerequisites

* [Graphviz](https://graphviz.org/download/)
* [Quarto](quarto.org)
* [Python 3.13](https://www.python.org/downloads/release/python-3130/?featured_on=pythonbytes)

### Set up the Python virtual environment

```
python3 -m venv .venv
```

### Install Python dependencies

```
source .venv/bin/activate
pip3 install -r requirements.txt
```

## Rendering the report

```
source .venv/bin/activate
quarto render report.qmd --to pdf
```
