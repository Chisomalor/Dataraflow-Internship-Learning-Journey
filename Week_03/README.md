# Week 3 — JSON, Error Handling, pip, Virtual Environments and SQL

## Overview

Week 3 introduced several practical Python skills that started making Python feel more like a real tool for working with data.

## Topics Covered

- Python modules
- `math`
- `datetime`
- `strftime()`
- JSON
- `json.dump()`
- `json.load()`
- `json.dumps()`
- `json.loads()`
- Error handling with `try` and `except`
- `ZeroDivisionError`
- `ValueError`
- Invalid JSON / `JSONDecodeError`
- `pip`
- Virtual environments
- Package installation and verification
- Specific package versions
- Introduction to SQL and databases

## Virtual Environment Setup

One of my practical tasks was creating and configuring a virtual environment in VS Code.

```bash
python -m venv myenv
```

I initially encountered a PowerShell execution-policy restriction, so for the current session I used:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
```

Then I activated the environment:

```bash
myenv\Scripts\activate
```

Installed `requests`:

```bash
pip install requests
```

And verified it:

```bash
pip show requests
```

I also learned that a specific package version can be installed using `==`:

```bash
pip install requests==2.31.0
```

## Practical Work

* **Notebook:** [Week_03_Take_Home.ipynb](./Week_03_Take_Home.ipynb)


## Medium Article

[Read my Week 3 story on Medium](https://medium.com/@chisomlydia99/week-3-of-learning-python-the-week-json-pip-and-virtual-environments-finally-made-sense-81c8898ff714)
## Key Lesson

The biggest lesson from Week 3 was learning to stop and understand *why* something works instead of only memorising syntax.

Some of the distinctions that finally became clearer were:

- `dump` vs `dumps`
- `load` vs `loads`
- `pip` vs `venv`
- `datetime.now()` vs `strftime()`
- Python code vs terminal commands

**Next:** Continue building Python and data skills through the remaining weeks of the DataraFlow internship.
