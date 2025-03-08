# Data Cleaning for Marketing Campaigns

## Project Description
Data cleaning is an essential skill for data engineers, encompassing reading, modifying, splitting, and storing data.

In this project, you will apply data-cleaning techniques to process information about marketing campaigns run by a bank. The tasks involve modifying values, adding new features, converting data types, and saving data into multiple files.

## Features
- Read and preprocess raw marketing campaign data.
- Modify, clean, and transform datasets.
- Add new features based on existing data.
- Convert data types for consistency.
- Save processed data into multiple formats.

## Installation

### Prerequisites
Ensure you have Python installed (recommended version: 3.8+). You can check your Python version with:

```bash
python --version
```

### Install Required Dependencies
First, create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

Then install dependencies:

```bash
pip install -r requirements.txt
```

## Usage
To run the data cleaning process, execute the following command:

```bash
jupyter notebook notebook.ipynb
```


## Documentation
This project uses **Sphinx** to generate documentation. To build the docs:

```bash
cd docs
make html
```

The generated documentation will be available in `docs/_build/html/index.html`.

## Continuous Integration
This project uses **Travis CI** for continuous integration. Ensure your `.travis.yml` file includes:

```yaml
language: python
python:
  - "3.8"
install:
  - pip install -r requirements.txt
script:
  - pytest
```

To enable Travis CI:
1. Link your GitHub repository to [Travis CI](https://travis-ci.com/).
2. Push changes to trigger the CI pipeline.

## Contributing
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.


