# DevOps course at IU

## Overview

This is Python web application written using [Flask framework](https://flask.palletsprojects.com/en/2.2.x/) and [WorldTimeAPI](http://worldtimeapi.org) showing Moscow time.

## Getting Started

### Local installation

Before running the application, please install its prerequisites:

* [Python 3.7+](https://www.python.org/downloads/)
* [pip](https://pip.pypa.io/en/stable/installation/)

To run from the master branch, follow the instructions below:

1. Clone web application repository locally.

    ```bash
    clone https://github.com/ease-ln/labs.git
    cd devOps/app_python/
    ```

2. Create virtual environment.

    ```bash
    python -m venv ./venv/
    .\venv\Scripts\activate
    ```

3. Install packages.

    ```bash
    pip install -r requirements.txt
    ```

4. Run the application.

    ```bash
    flask run
    ```

### Usage

You can run app and open [localhost](http://localhost:5000/) to view current Moscow time.

### Development&Contacts

Any problems or suggestions? You can contact me via [telegram](https://t.me/ease_l).
