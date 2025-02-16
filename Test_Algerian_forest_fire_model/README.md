# Algerian Forest Fire Prediction Model

This project aims to predict forest fires in Algeria using machine learning models. The project includes data preprocessing, exploratory data analysis (EDA), model training, and deployment using Flask.

## Project Structure

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Punith-14/Test_Algerian_forest_fire_model.git
    cd Test_Algerian_forest_fire_model
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv myenv
    source myenv/Scripts/activate  # On Windows
    # source myenv/bin/activate    # On Unix or MacOS
    ```

3. Install the required packages:
    ```sh
    pip install -r reqirement.txt
    ```

## Usage

1. Run the Flask application:
    ```sh
    python application.py
    ```

2. Open your web browser and go to `http://127.0.0.1:5000/` to access the application.

## Notebooks

- `notebook/EDA.ipynb`: Contains the exploratory data analysis of the dataset.
- `notebook/modelTraining.ipynb`: Contains the model training process.

## Models

- `models/ridge.pkl`: The trained Ridge regression model.
- `models/scaler.pkl`: The standard scaler used for data preprocessing.

## Templates

- `templates/home.html`: The home page of the web application.
- `templates/index.html`: The index page of the web application.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

- The dataset used in this project is from https://archive.ics.uci.edu/dataset/547/algerian+forest+fires+dataset.
- The project uses various Python libraries including Flask, scikit-learn, and pandas.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## Contact

For any questions or inquiries, please contact punithkmv@gmail.com.
