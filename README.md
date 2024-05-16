# COVID TRACKER API

The covid tracker API project was created to simulate real-life API. This project was created as an Application Under Test related to xml for the API testing with Python project [here](https://github.com/victoriaajuwon/tau-api-testing-in-python).

## Table of Contents
- [SetUp](#Setup)
- [IMPORTANT NOTE](#NOTE)
- [Purpose](#Purpose)


### Setup

1. Clone the repository.
   ```sh
    git clone https://github.com/victoriaajuwon/python-covid-tracker.git
    ```
2. On another terminal, navigate to the root directory in your terminal
    ```sh
    cd python-covid-tracker
    ```
3. You need to ensure you have a virtual environment set up for the project
4. You can pip.  To install pip, follow this [link](https://pip.pypa.io/en/stable/installation/)
5. Install dependencies using pip
    ```sh
    # Create virtualenv, inside the root directory, use the code below
    python -m venv venv
    # Activate virtualenv for windows
    .\venv\Scripts\activate
    # Activate virtualenv for Linux/MacOS
    source venv/bin/activate
    # Install dependencies
    python -m pip install
    ```
6. List of the dependencies used are
   - Flask
7. You can run the project
    ```sh
    # To run the project, use the code below
    python covid-tracker.py
8. View the server on ```http://127.0.0.1:3000```
9. Test the API with Postman using the GET method on ```http://127.0.0.1:3000/api/v1/summary/latest```
### NOTE

- #### Code
  - Code was gotten from [autoamtionhacks](https://github.com/automationhacks) from the[people-api rpository](https://github.com/automationhacks/people-api)


### Purpose
The purpose of this project is to create AUT for learning and understanding how to use Python to automate API testing related to XML.
