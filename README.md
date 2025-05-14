## CI/CD Pipeline with GitHub Actions
This repository demonstrates a complete CI/CD pipeline using GitHub Actions for a Python application. It includes automated testing, linting, and deployment workflows to streamline the development process.


### ​ Project Structure

```bash
CI-CD-Pipeline-With-GitHub-Actions/
├── .github/
│   └── workflows/
│       └── main.yml          # GitHub Actions workflow configuration
├── __pycache__/              # Compiled Python files (auto-generated)
├── app.py                    # Main Python application script
├── test_example.py           # Unit tests for the application
├── requirements.txt          # Project dependencies
├── text.txt                  # Sample text file used by the application
└── .gitignore                # Specifies files to ignore in version control

```

## Getting Started
- Prerequisites
- Python 3.x

pip (Python package installer)

## Installation
1. Clone the repository:

```git clone https://github.com/SandeepSuthar169/CI-CD-Pipeline-With-GitHub-Actions.git
cd CI-CD-Pipeline-With-GitHub-Actions```

2. Install the required dependencies:

` pip install -r requirements.txt `

3. Running the Application

- To execute the application:
`python app.py`

This will run the main script, which processes the text.txt file and outputs the result.

4. Running Tests
To run the unit tests:

`python test_example.py`

This will execute the tests defined in test_example.py to ensure the application functions as expected.
## CI/CD Pipeline with GitHub Actions

The project utilizes GitHub Actions to automate the following tasks:

- Trigger: On every push to the `main` branch.

- Jobs:

    - Setup: Set up Python environment.

    - Install Dependencies: Install required packages. 

     - Lint: Check code formatting using `flake8`.

     - Test: Run unit tests using `pytest`.

The workflow configuration is defined in `.github/workflows/main.yml`.
