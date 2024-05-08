# Backend

## Table of Contents

- [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Running the Backend](#running-the-backend)


This is the backend of our application.

## Setup

### Prerequisites

- Python 3.9, 3.10, or 3.11
- pip package manager

### Installation

1. Create a Python virtual environment:

    ```sh
    python3 -m venv .venv
    ```

2. Activate the virtual environment:

    - On Windows, run: `.venv\Scripts\activate`
    - On Unix or MacOS, run: `source .venv/bin/activate`

3. Install the required Python packages:

    ```sh
    pip install -r app/backend/requirements.txt
    ```

## Running the Backend

After setting up, you can run the backend with the following command:

```sh
python app/backend/main.py