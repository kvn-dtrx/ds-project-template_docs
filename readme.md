# Project Title

> One-sentence summary of the project’s goal and outcome.

**TODO:** Update title

## Table of Contents

- [Disclaimer](#disclaimer)
- [Table of Contents](#table-of-contents)
- [Synopsis](#synopsis)
- [Installation](#installation)
    - [Requirements](#requirements)
    - [Setup](#setup)
    - [Clean-Up](#clean-up)
- [Usage](#usage)
    - [Subcommands](#subcommands)
    - [Examples](#examples)

## <a name="synopsis"></a>Synopsis<small><sup>[↩](#table-of-contents)</sup></small>

**TODO:** Describe:

- The business/research problem.
- The objective of the project.
- Key questions answered.

## <a name="project-structure"></a>Project Structure<small><sup>[↩](#project-structure)</sup></small>

``` text
.
├── data/             # Raw and processed data
├── notebooks/        # Jupyter notebooks
├── src/              # Source code (loading, cleaning, modeling)
├── plots/            # Charts and visualisations
├── requirements.txt  # Project configuration
└── README.md         # Project overview
```

## <a name="data"></a>Data<small><sup>[↩](#data)</sup></small>

- Source(s) of data.
- How to access (if public).
- Description of columns/features.
- Size and format.

## <a name="results"></a>Results<small><sup>[↩](#results)</sup></small>

- Summary of findings (accuracy, metrics, charts).
- Visuals or links to reports (e.g., PDF, dashboard).
- Key insights.

## <a name="installation"></a>Installation<small><sup>[↩](#table-of-contents)</sup></small>

### Requirements

- Python 3.11.3
- pyenv

### Setup

1. Navigate to a working directory of your choice, then clone the repository and enter it:

   ``` shell
   git clone https://github.com/<username>/<reponame>.git &&
       cd <reponame>
   ```

2. Choose a setup option based on your operating system and intended use:

   - `make basic-unix` / `make basic-win`: for general use or exploration (core dependencies only).
   - `make dev-unix` / `make dev-win`: for contributors (includes development tools like linters and pre-commit hooks).

   If you prefer to run the commands manually yourself or want to inspect what each `make` target does first, use the `-n` flag for a dry run. This prints the commands without executing them:

   ``` shell
   make -n <target>
   ```

3. Activate the virtual environment:

   - On macOS/Linux, run:

     ```shell
     source .venv/bin/activate
     ```

   - On Windows (PowerShell), run:

     ``` powershell
     .\.venv\Scripts\Activate.ps1
     ```

## <a name="licence"></a>Licence<small><sup>[↩](#licence)</sup></small>

🪺 License

Add your license (MIT, Apache, etc.), or link to LICENSE
---
