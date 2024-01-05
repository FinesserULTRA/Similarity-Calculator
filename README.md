# Similarity Calculator

A Python program to calculate the similarity between words or strings using various methods, including SequenceMatcher.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Similarity Calculator is a Python program that calculates the similarity between words or strings using different methods, including the SequenceMatcher from the difflib library. It reads data from a CSV file, calculates the similarity percentage, and generates visualizations.

## Features

- Utilizes SequenceMatcher to calculate similarity percentages.
- Generates a CSV file with the final results.
- Creates visualizations to show the distribution of similarity percentages.

## Prerequisites

- Python (version 3.x.x)
- Required Python packages: Levenshtein, matplotlib, pandas

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/FinesserUltra/similarity-calculator.git
    ```

2. Navigate to the project directory:

    ```bash
    cd similarity-calculator
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

Run the `main.py` file to calculate similarity percentages and generate visualizations.

```bash
python main.py
```

## Example

```bash
from similarity_calculator import similarity_calculate

str1 = "example1"
str2 = "example2"
similarity_percentage = similarity_calculate(str1, str2)
print(f"Similarity Percentage: {similarity_percentage}%")
```

## Results
The program generates a CSV file (final_result.csv) containing the original data and calculated similarity percentages. Additionally, it produces visualizations to illustrate the distribution of similarity percentages.

## Contributing
Contributions are welcome! If you have any ideas, improvements, or bug fixes, feel free to open an issue or create a pull request.

## License
This project is licensed under the [MIT](LICENSE).

