# NLW Python Barcode
This is a Python project that uses Flask to create a web server. The main functionality of this project is to create tags using barcodes.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
You need to have Python installed on your machine. You can download it from here.

### Installing

1. Clone the repository and navigate to the project directory
```sh
git clone git@github.com:mateusbirtann/python-barcode.git
```

3. Create a virtual environment.
```sh
python -m venv .venv
```

4. Activate the virtual environment
```sh
source .venv/bin/activate
```

5. Install the required packages
```sh
pip install -r requirements.txt
```

### Running the Application
You can start the server by running the following command:
```sh
python run.py
```
The server will start on 0.0.0.0 and port 3000.

### Features
The main feature of this project is the /create_tag endpoint which is defined in run.py and handled by the TagCreatorController class.

### Code Quality
This project uses pylint for code quality. You can run pylint using the following command:

The project also uses pre-commit hooks to ensure code quality before each commit. The configuration for these hooks can be found in .pre-commit-config.yaml.

## Technologies Used

- [Flask](https://flask.palletsprojects.com/): A micro web framework written in Python. It's used to create the web server.

- [python-barcode](https://pypi.org/project/python-barcode/): A library for creating barcodes in Python. It's used to generate the barcodes for the tags.

- [Pillow](https://pillow.readthedocs.io/): An image processing library in Python. It's used in conjunction with python-barcode to generate images of the barcodes.

- [pylint](https://www.pylint.org/): A static code analysis tool for Python. It's used to ensure code quality.

- [pre-commit](https://pre-commit.com/): A framework for managing and maintaining pre-commit hooks. It's used to ensure that pylint is run before each commit.