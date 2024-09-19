# Recommendation System - Ivan Franko University

This repository contains laboratory works for the Recommendation System course at Ivan Franko University. The labs are designed to provide hands-on experience with Recommendation System models.

## Table of Contents

- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Running the Labs](#running-the-labs)
- [License](#license)

## Repository Structure

- **[Hw_1/](Hw_1/)**: Contains the first laboratory work.
  - **[README.md](Hw_1/README.md)**: Instructions and details for the first lab.
  - **[Hw_1.ipynb](Hw_1/Hw_1.ipynb)**: Jupyter notebook with the first lab tasks.
  - **[books_data.csv](Hw_1/books_data.csv)**: Dataset for the first lab.

- **[.gitignore](.gitignore)**: Specifies files and directories to be ignored by Git.
- **[README.md](README.md)**: This file, providing an overview of the repository.
- **[LICENSE](LICENSE)**: The license for the repository.
- **[requirements.txt](requirements.txt)**: Contains the required Python packages for the labs.

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/99bruno/RecSys_LNU.git
   ```
2. **Go to the repository directory:**
   ```sh
   cd RecSys_LNU
   ```
   
3. **Create a virtual environment:**
    ```sh
    python -m venv .venv
    ```
   
4. **Set up the virtual environment:**
    ```sh
    source .venv/bin/activate  # On Windows use `.venv\Scripts\activate`
    ```

5. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```

## Running the Labs

Each lab can be run independently. Navigate to the respective lab directory and execute the Python script.

- ### For example, to run the first lab:

  1. **Navigate to the first lab directory:**
      ```sh
      cd Hw_1
      ```

  2. **Run the Jupyter notebook:**
      ```sh
      jupyter notebook Hw_1.ipynb
      ```

Repeat the above steps for others.

## License

This project is licensed under the MIT **[LICENSE](LICENSE)**. See the LICENSE file for details.