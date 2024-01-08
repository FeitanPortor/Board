# University Prediction Application

## Overview

This Tkinter-based GUI application predicts universities based on various criteria using machine learning. It provides a user-friendly interface for input and displays predicted results.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Processing](#data-processing)
- [Graphical User Interface (GUI)](#graphical-user-interface-gui)
- [Prediction Functionality](#prediction-functionality)
- [Code Organization](#code-organization)
- [Libraries Used](#libraries-used)
- [How to Use](#how-to-use)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/university-prediction.git
    cd university-prediction
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

Run the script:

```bash
python university_prediction.py
```

## Data Processing

- Reads data from `dataset_university.csv`.
- Cleans data by removing spaces from column names.
- Drops unnecessary columns.
- Factorizes categorical data for numerical representation.
- Creates dictionaries mapping factorized codes back to original categories.

## Graphical User Interface (GUI)

- Provides a welcoming interface with a title, "Welcome To Career Point," and a light blue background.
- Dropdown menus for selecting values for various criteria (country, city, region, etc.).

## Prediction Functionality

- User selects values from dropdown menus.
- Clicking "Submit" uses a machine learning model (`model.pkl`) to predict a university.
- Predicted university names are displayed on the GUI.

## Code Organization

- Organized into functions for readability and maintainability.
- Separation of data processing, GUI creation, and prediction functionalities.

## Libraries Used

- `Tkinter`: For GUI creation.
- `pandas`: For data manipulation and cleaning.
- `joblib`: For loading the machine learning model.

## How to Use

1. Run the script, and the GUI window will appear.
2. Select values for each criterion from the dropdown menus.
3. Click the "Submit" button to get predictions.
4. Predicted university names will be displayed on the GUI.

Ensure that required CSV files (`dataset_university.csv`) and the machine learning model (`model.pkl`) are available in the project directory.

## Contributing

Feel free to contribute! Check out the [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).
```

Remember to replace placeholders like `your-username` with your actual GitHub username and update the paths or file names if needed. Additionally, consider adding a `CONTRIBUTING.md` file for detailed contribution guidelines.
